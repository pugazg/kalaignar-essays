# P2 Integrity Repair — scans 56–81

Publication: `சிந்தனையும் செயலும்`  
Repository: `pugazg/kalaignar-essays`  
Defective checkpoint: `c43bfc804fff68f0617c8122d09f9a08a0ee3eab`  
Parent: `df8773a4ccc3facee7129c609020579fffcd80a4`

## Defect found

The checkpoint claimed scans **1–81 P2 VERIFIED** and Units **1–17 assemblies VERIFIED**, but the commit comparison shows only **12 of the required 26 page records** for scans 56–81 were changed.

Page records actually written by `c43bfc8`:

`0057, 0058, 0059, 0062, 0063, 0065, 0066, 0067, 0070, 0072, 0073, 0081`

Missing canonical page writes:

`0056, 0060, 0061, 0064, 0068, 0069, 0071, 0074, 0075, 0076, 0077, 0078, 0079, 0080`

Therefore the tracker claim and the canonical page layer were internally inconsistent.

## Repair action

1. Restore the fourteen missing page records from the source-reviewed P2 staging layer.
2. Recheck scan 56 directly against the controlling PDF; preserve the source-visible opening **`சங்க இலக்கியப் பூக்காடுகளில்`**.
3. Keep the already-written twelve page records in place.
4. Remove derived assemblies 11–17 from the canonical P3 layer. They were created while the page layer was incomplete, and direct comparison of Unit 11 shows assembly drift from the canonical/source layer (for example `பூங்காடுகளில்` versus source `பூக்காடுகளில்`, and `அவருடைய மகனுக்கு` versus source `அவளுடைய மகனுக்கு`).
5. Reset P3 verified assembly count to **10 / 50** while retaining the repaired P2 page-layer count of **81 / 226**.
6. Block scans 82–111 until Units 11–17 are rebuilt strictly from canonical page records and an explicit consistency gate passes.

## Non-regression rule

A tracker may never advance beyond the actual canonical page files. A derived article assembly may never be treated as verified if any included page record is missing, placeholder, non-verified, or differs from the assembly text.

## Next gate

Rebuild Units 11–17 from scans 56–81 and prove page/assembly equality before resuming P2 at scan 82.

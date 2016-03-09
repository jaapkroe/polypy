# polypy
polygon (ring network) discovery from XYZ files.

polypy is a python script to analyze (shortest-path) rings in structures read from xyz-files. 
It can be used for example to identify defects in crystal structures or molecules.

**features**
- Shortest-path ring search using Franzblau statistics [Phys. Rev. B 44, 4925]
- Output structures marked for visualization (see screenshots)
- detect subgraphs; defect clusters; atom chains; neighbor shells
- Progress bars!

**obtain code**
The only file required is "polypy", simply download it or clone this repository.

**EXAMPLE**
    polypy filename.xyz                                       *use default settings*
    polypy -s -d0 --pbc "15.0 21.0 12.0" filename.xyz         *print simplified info file, (d0) search until inifinite depth, and use periodic boundary conditions*
    

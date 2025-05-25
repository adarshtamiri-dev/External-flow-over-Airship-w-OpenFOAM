# External Flow over Complex Bodies with k-Epsilon Model – OpenFOAM Case File
## Force Coefficients ✅ 
## Drag Coefficients ✅
## Easy Adjustment of AOA ✅
## Mesh Generation with CfMesh ✅ 
## 🧪 Optimized Layer Generation using SHM ✅

This repository contains an OpenFOAM case setup which is good for most external aerodynamic flow interactions over surface bodies. Though originally built for a specific geometry, the setup is highly adaptable and can be easily extended to similar external flow problems.


  
##🔧 Features

  k-Epsilon RANS Model: Balanced for accuracy and stability in external aerodynamic scenarios.

  Optimized Mesh Generation: Utilizes cfMesh for automated, high-quality meshing suitable for complex (Curved Geometries) external domains.

  Efficient Case Tuning: Boundary conditions, solver settings, and relaxation factors are pre-optimized to reduce iteration time and promote convergence.

## Applications

This setup is ideal for:

   External flow over streamlined bodies

   Initial testing of aerodynamic shapes

   Parametric studies with different configurations

##🚀 For Usage

   Clone the repo

   Adjust geometry (constant/triSurface or STL file)

   Edit meshDict and mesh the domain using cfMesh

   Run the simulation using simpleFoam

##📁 Structure

   system/ – Simulation controls and solver settings

   constant/ – Mesh, turbulence model, and physical properties

   0/ – Initial and boundary conditions

##But why CfMesh?
  
  Easy Configuration. (Simpler than SnappyHexMesh)
  
  Easy control over patch names (Simply combining patch.stl files)
  
  Good for Curved/ Complex Geometry alignments.
  
  Good for automation 
  
  Good bye to heavy blockMeshes and snapping out of them.
  
  Cons: The additional features (Better control and Bigger Meshes) are not Open-Sourced. Poor on layer generation in small gaps.

##📝 Notes

   Designed with adaptability in mind

   Can be extended to more advanced turbulence models or refined further

   Suitable for educational or research-level aerodynamic testing.

   Tailor the case setup for your case and adjust the parameters accordingly.
  
   Optimization is not gauranteed for cases that don't match the Current Repository. 

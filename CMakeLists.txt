message(STATUS "Powercrust: Building as a Remote VTK module")
 
set(Module_SRCS
  vtkPowerCrustSurfaceReconstruction.cxx
  )

vtk_module_library(Powercrust ${Module_SRCS})

project (FluidX3D)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(fluidx3d
  src/graphics.cpp
  src/info.cpp
  src/kernel.cpp
  src/lbm.cpp
  src/lodepng.cpp
  src/main.cpp
  src/setup.cpp
  src/shapes.cpp
  )


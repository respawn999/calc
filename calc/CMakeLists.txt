# CMakeList.txt : CMake project for calc, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (calc "calc.cpp" "calc.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET calc PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.

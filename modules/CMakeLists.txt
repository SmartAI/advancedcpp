# Enable modules and scanning for this directory
set(CMAKE_EXPERIMENTAL_CXX_MODULES ON)
set(CMAKE_CXX_SCAN_FOR_MODULES ON)
set(CMAKE_EXPERIMENTAL_CXX_IMPORT_STD ON)

add_executable(math math_main.cpp math_impl.cpp)

target_sources(math
  PUBLIC FILE_SET CXX_MODULES FILES math.cppm
)



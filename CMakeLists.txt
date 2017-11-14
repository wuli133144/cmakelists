

project(add_x)

#include_directories(${project_source_dir}/include/)
#aux_source_directory(${cmake_current_source_dir}/src/ sourcefiles)
add_subdirectory(src bin)

INSTALL (PROGRAMS run.sh DESTINATION bin)


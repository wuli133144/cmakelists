cmake_minimum_required(version 2.8)

project(add_x)

include_directories(${cmake_current_source_dir}/include/)
aux_source_directory(${cmake_current_source_dir}/src/ sourcefiles)

add_executable(add_x ${sourcefiles})

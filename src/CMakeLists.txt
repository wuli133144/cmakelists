
project(add_x)

include_directories(${project_source_dir}/include/)
add_executable(add_x  main.c utils.c)

INSTALL(PROGRAMS ../run.sh DESTINATION bin)

cmake_minimum_required(VERSION 3.5.2)

add_executable(access access.c)
add_executable(filetype filetype.c)
include_directories(../include)

#find_library(ERROR_LIB NAMES error PATHS "../lib/")
target_link_libraries(access ${PROJECT_BINARY_DIR}/lib/liberror.so)
target_link_libraries(filetype ${PROJECT_BINARY_DIR}/lib/liberror.so)




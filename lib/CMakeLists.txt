cmake_minimum_required(VERSION 3.5.2)

include_directories(../include)
SET(LIBERROR_SRC error.c)
add_library(error SHARED ${LIBERROR_SRC})


set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib)

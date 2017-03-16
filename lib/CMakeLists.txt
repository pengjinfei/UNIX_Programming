cmake_minimum_required(VERSION 3.5.2)

include_directories(../include)
aux_source_directory(. LIBAPUE_SRC)
#SET(LIBERROR_SRC bufargs.c cliconn.c clrfl.c daemonize.c error.c errorlog.c lockreg.c)
#set(LIBAPUE_SRC error.c)
add_library(apue3 SHARED ${LIBAPUE_SRC})


set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib)

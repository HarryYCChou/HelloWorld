# cmake minimun required version
cmake_minimum_required (VERSION 3.16)
# project name
set(PROJECT_NAME HelloWorld)
# set project name
project (${PROJECT_NAME})
# searching current source codes of src dir
aux_source_directory(src SRCS)
# add build target to project
add_executable (${PROJECT_NAME} ${SRCS})
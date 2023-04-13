# CMake 最低版本号要求
cmake_minimum_required (VERSION 2.8)

# 项目信息
project (Demo5)

ADD_SUBDIRECTORY(src bin)

INSTALL(FILES COPYRIGHT README DESTINATION share/doc/MathFunctions/)
INSTALL(DIRECTORY doc/ DESTINATION share/doc/MathFunctions/)
INSTALL(PROGRAMS runDemo.sh DESTINATION bin)
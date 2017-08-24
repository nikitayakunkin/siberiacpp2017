cmake_minimum_required(VERSION 2.8.7)

#SET(CMAKE_C_COMPILER C:/MinGW/bin/gcc)
#SET(CMAKE_CXX_COMPILER C://MinGW//bin//g++)
#SET(CMAKE_CXX_COMPILER "C://Program Files//Microsoft Visual Studio 12.0//VC//bin//cl.exe")


project(hello CXX)

set(${PROJECT_NAME}_SRC
C:/ProgsToCode/confs/siberia2017/src/main.cpp
)

add_executable(${PROJECT_NAME} ${${PROJECT_NAME}_SRC})

cmake_minimum_required(VERSION 3.10.2.0)
project(CMAKE_TRY_COMPILE CXX)
set(CMAKE_VERBOSE_MAKEFILE 1)
set(CMAKE_CXX_FLAGS "")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} ${COMPILE_DEFINITIONS}")
set(CMAKE_EXE_LINKER_FLAGS "${CMAKE_EXE_LINKER_FLAGS} ${EXE_LINKER_FLAGS}")
include_directories(${INCLUDE_DIRECTORIES})
set(CMAKE_SUPPRESS_REGENERATION 1)
link_directories(${LINK_DIRECTORIES})
cmake_policy(SET CMP0065 OLD)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "/home/c-vis/cycle-vision-cv/jetson-inference/utils/python/python/CMakeFiles/CMakeTmp")
add_executable(cmTC_30392 "/usr/share/cmake-3.10/Modules/CMakeCXXCompilerABI.cpp")
target_link_libraries(cmTC_30392 ${LINK_LIBRARIES})

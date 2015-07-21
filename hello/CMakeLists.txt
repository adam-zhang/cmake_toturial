project(Hello)
cmake_minimum_required(VERSION 2.8)
include_directories(${PROJECT_SOURCE_DIR}/lib)
add_subdirectory(lib)
set(sources appMain.cpp)
add_executable(Hello ${sources})
target_link_libraries(Hello
	libHello)

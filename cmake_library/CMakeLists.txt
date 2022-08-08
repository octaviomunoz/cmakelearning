cmake_minimum_required(VERSION 3.22)

project(Library)

add_subdirectory(my_library)

add_executable(A main.cpp)

target_link_libraries(A
	my_library)

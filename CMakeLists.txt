cmake_minimum_required (VERSION 3.20)

project (circleTheCat)

add_executable (${CMAKE_PROJECT_NAME} WIN32)

add_subdirectory (include)
add_subdirectory (src)
add_subdirectory (resources)


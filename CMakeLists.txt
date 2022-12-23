cmake_minimum_required(VERSION 3.10)

project(SomeGraphicApp VERSION 0.1)

add_subdirectory(${PROJECT_SOURCE_DIR}/glfw)
add_subdirectory(${PROJECT_SOURCE_DIR}/src)

target_include_directories(SomeGraphicApp PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/glfw/include)

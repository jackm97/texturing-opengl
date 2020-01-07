cmake_minimum_required(VERSION 3.0)

project(Texture)

include_directories("./include/")

add_executable(Texture "main.cpp" "glad.c" "Shader.cpp")
target_link_libraries(Texture "-lGL -lglfw3 -lX11 -lpthread -lXrandr -lXi -ldl")

cmake_minimum_required(VERSION 3.17)

project(Project_Olivia)

add_executable(${PROJECT_NAME} glad.c
src/Mesh.cpp
src/EBO.cpp
src/main.cpp
src/shaderClass.cpp
src/VAO.cpp
src/VBO.cpp
src/Texture.cpp
src/Camera.cpp
)

target_link_libraries(${PROJECT_NAME} GL dl glfw)

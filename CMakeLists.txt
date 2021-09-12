cmake_minimum_required(VERSION 3.0)

set(PROJECT_NAME "OpenGL template")
set(VERSION_MAJOR 1)
set(VERSION_MINOR 0)

project(${PROJECT_NAME} VERSION ${VERSION_MAJOR}.${VERSION_MINOR} LANGUAGES CXX)

add_subdirectory(app)

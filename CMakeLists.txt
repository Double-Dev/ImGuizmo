cmake_minimum_required(VERSION 3.16)
project(ImGuizmo)

# Setting up a static library.
add_library( imguizmo STATIC
    ImGuizmo.h
    ImGuizmo.cpp )
target_include_directories(imguizmo PUBLIC ${ImGuizmo_SOURCE_DIR})
target_include_directories(imguizmo PUBLIC ${ImGuizmo_SOURCE_DIR}/../imgui)
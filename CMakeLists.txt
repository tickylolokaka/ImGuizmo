add_library(imguizmo ImGuizmo.h ImGuizmo.cpp)
add_subdirectory("../imgui-docking" "${CMAKE_SOURCE_DIR}/Onyx/lib/imguizmo")
target_link_libraries(imguizmo imgui-docking)
target_include_directories(stb INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

project(cpp_graph)

add_library(cpp_graph STATIC Graph.cc Node.cc)
set_property(TARGET cpp_graph PROPERTY POSITION_INDEPENDENT_CODE ON)

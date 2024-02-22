cmake_minimum_required(VERSION 3.21.0)

project(oid-devel)

# Application
add_subdirectory(src/OpenImageDebugger)

# Test application to debug oid
add_subdirectory(src/OpenImageDebugger/testbench)


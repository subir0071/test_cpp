cmake_minimum_required(VERSION 3.10)
project(MyCppProject)

set(CMAKE_CXX_STANDARD 17)

add_executable(my_cpp_project src/main.cpp)

# Add tests (Optional, if using GoogleTest or similar)
enable_testing()
add_executable(test_main test/test_main.cpp)
add_test(NAME TestMain COMMAND test_main)

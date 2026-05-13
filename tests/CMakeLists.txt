# Simple test runner
add_executable(test_runner test_main.cpp)
target_link_libraries(test_runner PRIVATE cpp_project_lib)
target_include_directories(test_runner PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/../include
)

add_test(NAME BasicTests COMMAND test_runner)

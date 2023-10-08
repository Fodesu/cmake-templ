include_directories(${thirdpart_dir}/googletest/googletest/include)

add_executable(tmp tmp.cpp)

target_link_libraries(tmp gtest_main)


add_test(NAME example COMMAND tmp)

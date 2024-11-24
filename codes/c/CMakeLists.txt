cmake_minimum_required(VERSION 3.10)
project(hello_algo C)

# 设置C++标准：通过 set(CMAKE_CXX_STANDARD 11) 指定项目使用 C++11 标准。
# 包含目录：通过 include_directories(./include) 指定了包含头文件的目录。
# 添加子目录：通过多个 add_subdirectory 命令，将各个章节（如 chapter_computational_complexity、chapter_array_and_linkedlist 等）添加到项目中。这些子目录通常包含各自的 CMakeLists.txt 文件，用于进一步配置各自的源文件和目标。

set(CMAKE_C_STANDARD 11)

include_directories(./include)

add_subdirectory(chapter_computational_complexity)
add_subdirectory(chapter_array_and_linkedlist)
add_subdirectory(chapter_stack_and_queue)
add_subdirectory(chapter_hashing)
add_subdirectory(chapter_tree)
add_subdirectory(chapter_heap)
add_subdirectory(chapter_graph)
add_subdirectory(chapter_searching)
add_subdirectory(chapter_sorting)
add_subdirectory(chapter_divide_and_conquer)
add_subdirectory(chapter_backtracking)
add_subdirectory(chapter_dynamic_programming)
add_subdirectory(chapter_greedy)

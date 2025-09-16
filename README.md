# 🧠 Memory Handling in C++

This is a simple C++ project demonstrating **basic memory handling**:

- Raw pointers (`new` / `delete`)
- Arrays on the heap
- Modern C++ smart pointers (`unique_ptr`, `shared_ptr`)

cmake_minimum_required(VERSION 3.10)
project(MemoryHandling)

set(CMAKE_CXX_STANDARD 17)

add_executable(memory-handling src/main.cpp)

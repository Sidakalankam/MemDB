cmake_minimum_required(VERSION 3.28)
project(MemDB)

set(CMAKE_CXX_STANDARD 17)

add_executable(MemDB
        server.cpp
        avl.cpp
        avl.h
        common.h
        hashtable.cpp
        hashtable.h
        heap.cpp
        heap.h
        list.h
        thread_pool.cpp
        thread_pool.h
        zset.cpp
        zset.h
)

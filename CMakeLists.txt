cmake_minimum_required(VERSION 3.23)
project(BTreeDemo)

set(CMAKE_CXX_STANDARD 14)

#add_executable(BTreeDemo itemtype.cpp itemtype.h table.cpp table.h btree.cpp btree.h btmake.cpp)
add_executable(BTreeDemo itemtype.cpp itemtype.h table.cpp table.h btree.cpp btree.h btread.cpp)

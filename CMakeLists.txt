cmake_minimum_required(VERSION 3.22.1)

project("demo-visualstudio2")

# set(CMAKE_STRIP llvm-strip)
# set(CMAKE_EXE_LINKER_FLAGS "${CMAKE_EXE_LINKER_FLAGS} -s")

add_executable(${CMAKE_PROJECT_NAME} 
    src/ATM.cpp
    src/Account.cpp
    src/Bank.cpp
    src/BaseDisplay.cpp
    src/TestObjectFactory.cpp
    src/dbutil.c
    src/main.cpp
)

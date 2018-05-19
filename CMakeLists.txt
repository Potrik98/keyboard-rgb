cmake_minimum_required(VERSION 3.8)
project(keyboard)

set(CMAKE_CXX_STANDARD 17)

set(SOURCE_FILES main.cpp)

add_executable(keyboard ${SOURCE_FILES})

target_link_libraries(keyboard
        usb-1.0
)
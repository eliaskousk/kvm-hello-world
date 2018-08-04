cmake_minimum_required(VERSION 3.8)
project(kvm_hello_world)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        code16.s
        code32.s
        code32p.s
        code64.s
        kvm-hello-world.c)

add_executable(kvm_hello_world ${SOURCE_FILES})
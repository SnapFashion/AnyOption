cmake_minimum_required(VERSION 2.8)

project(anyoption)

add_library(anyoption SHARED anyoption.cpp anyoption.h)
install(TARGETS anyoption
    LIBRARY DESTINATION /usr/local/lib
    )

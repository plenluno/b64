# Copyright (c) 2013 Plenluno All rights reserved.

cmake_minimum_required(VERSION 2.8)

project(b64)

include_directories(
    include
)

add_library(b64 STATIC
    src/b64.c
)

# Copyright (C) 2022 Jens Pots.
# License: AGPL-3.0-only.

cmake_minimum_required(VERSION 3.21)
project(hostsfile C)

set(CMAKE_C_STANDARD 11)

add_executable(hf src/hostsfile.c)

CMAKE_MINIMUM_REQUIRED(VERSION 3.5)
PROJECT(id3v2lib)

SET(CMAKE_C_STANDARD 99)
SET(CMAKE_POSITION_INDEPENDENT_CODE 1)
SET(CMAKE_C_FLAGS "-Wall -Wextra -pedantic")

SET(VERSION_MAJOR 1)
SET(VERSION_MINOR 0)

ADD_SUBDIRECTORY(src)

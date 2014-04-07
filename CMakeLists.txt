cmake_minimum_required(VERSION 2.8.4)

project(yac-man)

if (${CMAKE_SYSTEM_NAME} MATCHES "Linux")
    message(STATUS "Linux on-board")
elseif (${CMAKE_SYSTEM_NAME} MATCHES "Win32")
    message(STATUS "Windows on-board")
elseif (${CMAKE_SYSTEM_NAME} MATCHES "CYGWIN")
    message(STATUS "Cygwin")
endif()


cmake_minimum_required(VERSION 3.2)

project(LeddarTest
    DESCRIPTION "Tests for the Leddar component of the LeddarTech SDK"
    LANGUAGES CXX)

add_executable(${PROJECT_NAME}
    main.cpp)
target_link_libraries(${PROJECT_NAME}
    Leddar)

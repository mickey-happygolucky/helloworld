cmake_minimum_required(VERSION 3.16)
project(helloworld)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(${PROJECT_NAME}
  main.cpp
  )

install(TARGETS ${PROJECT_NAME}
        DESTINATION bin)

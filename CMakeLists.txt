cmake_minimum_required(VERSION 3.25)
project(CMakeActionTest)

add_executable(cmake-action-test
  main.c
  )

enable_testing()

add_test(NAME cmake-action-test
  COMMAND cmake-action-test
  )

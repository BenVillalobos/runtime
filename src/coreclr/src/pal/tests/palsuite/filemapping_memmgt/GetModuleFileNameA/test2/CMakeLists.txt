set(SOURCES
  GetModuleFileNameA.cpp
)

add_executable(paltest_getmodulefilenamea_test2
  ${SOURCES}
)

add_dependencies(paltest_getmodulefilenamea_test2 coreclrpal)

target_link_libraries(paltest_getmodulefilenamea_test2
  ${COMMON_TEST_LIBRARIES}
)

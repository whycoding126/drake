if(GTEST_FOUND)
  add_executable(adder_test adder_test.cc)
  target_link_libraries(adder_test drakeSystemFramework ${GTEST_BOTH_LIBRARIES})
  add_test(NAME adder_test COMMAND adder_test)
endif()

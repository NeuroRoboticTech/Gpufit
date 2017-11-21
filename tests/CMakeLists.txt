
# Tests

if( CPU_ONLY )
  add_boost_test( "Cpufit" Consistency )
else()
  add_boost_test( "Cpufit;Gpufit" Consistency )
endif()


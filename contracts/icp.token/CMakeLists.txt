add_contract(icp.token icp.token ${CMAKE_CURRENT_SOURCE_DIR}/icp.token.cpp)
target_include_directories(icp.token
   PUBLIC
   ${CMAKE_CURRENT_SOURCE_DIR})

set_target_properties(icp.token
   PROPERTIES
   RUNTIME_OUTPUT_DIRECTORY "${CMAKE_CURRENT_BINARY_DIR}")

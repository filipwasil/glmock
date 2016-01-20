project(glmock)
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../gtest/googletest/include)
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../gtest/googlemock/include)
add_library(glmock SHARED glmock.cpp)

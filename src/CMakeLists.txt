set( CMAKE_CXX_FLAGS "-std=c++11")

add_definitions(-std=c++11)

# libraries first
add_subdirectory(caesar)

# executables second
add_subdirectory(exes)

project(lab6)

set(CMAKE_CXX_STANDARD 17)

add_executable(lab6
  ./main.cpp)

set(CMAKE_CXX_FLAGS
  "${CMAKE_CXX_FLAGS} -Wall -Wextra")


* Use `target_link_libraries()` to link `.so` or `.a` files.
* If the library is in the same folder, give its full path.
* For system libraries, link by name (no path needed).




```

cmake_minimum_required(VERSION 3.10)
project(my_app)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# headers
include_directories(${CMAKE_SOURCE_DIR}/include)

# executable
add_executable(my_app src/main.cpp)

# static library
target_link_libraries(my_app PRIVATE ${CMAKE_SOURCE_DIR}/libname.a)


```



```

cmake_minimum_required(VERSION 3.10)
project(my_app)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(my_app main.cpp)

# .so in same directory
target_link_libraries(my_app PRIVATE ${CMAKE_SOURCE_DIR}/libfile.so)


```
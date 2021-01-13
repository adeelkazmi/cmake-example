add_library (Library SHARED externs.cpp api.cpp)
target_include_directories (Library PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

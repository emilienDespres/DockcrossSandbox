add_executable (main main.cpp)

install (PROGRAMS ${CMAKE_CURRENT_BINARY_DIR}/mainDemo
    DESTINATION bin
    RENAME ${CMAKE_PROJECT_NAME}-mainDemo)
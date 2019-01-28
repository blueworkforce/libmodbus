
include_directories(${PROJECT_SOURCE_DIR}/src)

add_executable(client unit-test-client.c)
target_link_libraries(client modbus)

add_executable(server unit-test-server.c)
target_link_libraries(server modbus)


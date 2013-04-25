add_executable(eva_srv eva_srv.c)
add_executable(eva_cli eva_cli.c)

target_link_libraries(eva_srv ev)

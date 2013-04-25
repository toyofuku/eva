
include_directories("/usr/local/Cellar/libev/4.11/include")
link_directories("/usr/local/Cellar/libev/4.11/lib")

add_executable(eva_srv eva_srv.c)
add_executable(eva_cli eva_cli.c)

target_link_libraries(eva_srv ev)

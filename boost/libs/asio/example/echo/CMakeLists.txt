foreach(
    example
    blocking_udp_echo_server
    async_udp_echo_server
    blocking_udp_echo_client
    blocking_tcp_echo_server
    async_tcp_echo_server
    blocking_tcp_echo_client
)
boost_add_executable(
    ${example}
    DEPENDS
    boost_thread
    boost_system
)
endforeach(
)

foreach(
    example
    client
)
boost_add_executable(
    ${example}
    DEPENDS
    boost_system
    TARGET_PREFIX
    "daytime4-"
)
endforeach(
)

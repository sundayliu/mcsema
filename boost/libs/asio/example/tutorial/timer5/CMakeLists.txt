foreach(
    example
    timer
)
boost_add_executable(
    ${example}
    DEPENDS
    boost_thread
    boost_system
    TARGET_PREFIX
    "timer5-"
)
endforeach(
)

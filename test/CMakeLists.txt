add_executable(
    skippercxxtest
    test.cpp
)

target_link_libraries(
    skippercxxtest
    PRIVATE
    skippercxx
)

add_test(
    NAME skippercxxtest
    COMMAND skippercxxtest
)

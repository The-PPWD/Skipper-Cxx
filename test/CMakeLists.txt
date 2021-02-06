add_executable(
    skippercxxtest
    constants/pi.cpp
)

target_link_libraries(
    skippercxxtest
    PRIVATE
    skippercxx
)

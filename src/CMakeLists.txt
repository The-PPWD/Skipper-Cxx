add_library(
    skippercxx
    constants/pi.cpp
)

target_include_directories(
    skippercxx
    PUBLIC
    ${PROJECT_SOURCE_DIR}/include
)

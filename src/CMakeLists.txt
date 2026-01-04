add_executable(pelo
    main.cpp
)

# Make headers in /include visible to this target
target_include_directories(pelo PRIVATE
    ${PROJECT_SOURCE_DIR}/include
)

add_executable(tick_test_model models_gtest.cpp hawkes_models_gtests.cpp)

target_link_libraries(tick_test_model
    ${TICK_LIB_ARRAY}
    ${TICK_LIB_BASE}
    ${TICK_LIB_MODEL}
    ${TICK_TEST_LIBS}
    )

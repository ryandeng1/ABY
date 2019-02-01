
add_executable(mul mul.cpp ../aes/common/aescircuit.cpp)
target_link_libraries(mul ABY::aby ENCRYPTO_utils::encrypto_utils)

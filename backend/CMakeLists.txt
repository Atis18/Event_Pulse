cmake_minimum_required(VERSION 3.20)

project(EventPulseBackend LANGUAGES CXX)

add_executable(eventpulse src/main.cpp)

target_compile_features(eventpulse PRIVATE cxx_std_20)
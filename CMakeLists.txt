cmake_minimum_required(VERSION 3.14)
project(TE2_DatosII)

set(CMAKE_CXX_STANDARD 14)

add_executable(TE2_DatosII main.cpp src/Client.cpp include/Client.hpp include/Observer.hpp include/Subject.hpp src/WeatherData.cpp include/WeatherData.hpp)
cmake_minimum_required(VERSION 3.14)
project(TE2_DatosII)

set(CMAKE_CXX_STANDARD 14)

add_executable(TE2_DatosII Observer/main.cpp Observer/src/Client.cpp Observer/include/Client.hpp Observer/include/Observer.hpp Observer/include/Subject.hpp Observer/src/WeatherData.cpp Observer/include/WeatherData.hpp)
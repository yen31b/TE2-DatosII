cmake_minimum_required(VERSION 3.14)
project(untitled5)

set(CMAKE_CXX_STANDARD 14)

add_executable(TE2_DatosII main.cpp src/Client.cpp include/Client.h include/Observer.h include/Subject.h src/WeatherData.cpp include/WeatherData.h)
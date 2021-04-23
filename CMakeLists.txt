cmake_minimum_required(VERSION 3.19)
project(ITP_NewProject)

set(CMAKE_CXX_STANDARD 20)

add_executable(ITP_NewProject main.cpp Passenger.cpp Passenger.h Driver.cpp Driver.h PassengerGateway.cpp PassengerGateway.h DriverGateway.cpp DriverGateway.h Application.cpp Application.h)
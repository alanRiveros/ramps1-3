cmake_minimum_required(VERSION 3.9)
project(firmware)

set(CMAKE_CXX_STANDARD 11)

add_executable(firmware
        FiveD_GCode/Extruder/configuration.h
        FiveD_GCode/Extruder/extruder.h
        FiveD_GCode/Extruder/intercom.h
        FiveD_GCode/Extruder/temperature.h
        FiveD_GCode/FiveD_GCode_Interpreter/cartesian_dda.h
        FiveD_GCode/FiveD_GCode_Interpreter/extruder.h
        FiveD_GCode/FiveD_GCode_Interpreter/intercom.h
        FiveD_GCode/FiveD_GCode_Interpreter/pins.h
        FiveD_GCode/FiveD_GCode_Interpreter/Temperature.h
        FiveD_GCode/FiveD_GCode_Interpreter/vectors.h)

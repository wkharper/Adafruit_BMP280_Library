# MIT License

cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_BMP280.cpp" 
                       INCLUDE_DIRS "."
		       REQUIRES arduino-esp32 Adafruit_BusIO Adafruit_Sensor)
project(Adafruit_BMP280)

cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_AW9523.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES Adafruit_BusIO arduino-esp32)

project(Adafruit_AW9523)

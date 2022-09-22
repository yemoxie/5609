cmake_minimum_required(VERSION 3.23)
project(CP5609_Lab3)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(CP5609_Lab3
        BoardCells.cpp
        BoardCells.h Controller.cpp Controller.h Common.h Cookie.cpp Cookie.h GameCell.cpp GameCell.h BoardObject.h
        ListBoardObjects.cpp ListBoardObjects.h main.cpp moc_Controller.cpp moc_GameCell.cpp moc_Model.cpp Model.cpp Model.h Player.cpp Player.h Wall.cpp Wall.h QT/Tutorial3.cpp QT/Tutorial4.cpp QT/Tutorial5.cpp QT/Tutorial6.cpp)

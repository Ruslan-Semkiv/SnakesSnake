cmake_minimum_required(VERSION 3.26)
project(SnakesSnake)

set(CMAKE_CXX_STANDARD 17)

add_executable(SnakesSnake main.cpp
        Game/Game.cpp
        Game/GameException.cpp
        Tools/FileManager.cpp
        Tools/Random.cpp
        Tools/Time.cpp
        Tools/Console.cpp
        World/Apple.cpp
        World/Field.cpp
        World/Score.cpp
        World/Snake.cpp
        World/Walls.cpp
        Tools/InputManager.cpp
)

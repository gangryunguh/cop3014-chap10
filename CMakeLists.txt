cmake_minimum_required(VERSION 3.14)
project(cop3014_chap10)

set(CMAKE_CXX_STANDARD 11)

foreach(file Pr10-1 Pr10-2 Pr10-3 Pr10-4
        Pr10-5 Pr10-6 Pr10-7 Pr10-8 Pr10-9
        Pr10-10 Pr10-11 Pr10-12 Pr10-13 Pr10-14
        Pr10-15 Pr10-16 Pr10-17 Pr10-18 Pr10-19
        Pr10-20 Pr10-21 Pr10-22 Pr10-23 Pr10-24)
    add_executable(${file}.exe ${file})
endforeach()

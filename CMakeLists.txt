cmake_minimum_required(VERSION 3.17)
project(Heroes)

set(CMAKE_CXX_STANDARD 14)

add_executable(Heroes main.cpp Hero.h Race.h Weapon.h Archer.h Warrior.h Human.h Orc.h Bow.h Axe.h)

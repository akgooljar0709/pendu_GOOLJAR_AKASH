cmake_minimum_required(VERSION 3.16.3)

# set the project name
project(Pendu)

include_directories(include)

set(SOURCES src/dico.c
			src/main.c)


# add the executable
add_executable(smain
			   ${SOURCES})
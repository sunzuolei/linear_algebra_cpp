#project name
PROJECT(E)
INCLUDE_DIRECTORIES(../)

SET(ALL_CODE_LIST e.cpp)
MESSAGE(${ALL_CODE_LIST})

#add executable file
ADD_EXECUTABLE(E ${ALL_CODE_LIST})

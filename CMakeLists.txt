cmake_minimum_required(VERSION 3.8)
project(cppzmq)

###############
# ASI default settings
list(APPEND CMAKE_MODULE_PATH "$ENV{ASV_CMAKE}")
include(asv_cmake_defaults)
asv_cmake_defaults( )
###############

# includes
install(
    FILES zmq.hpp zmq_addon.hpp
    DESTINATION include/cppzmq
    )

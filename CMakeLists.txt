cmake_minimum_required(VERSION 3.0.0)
project(cppzmq)

###############
# ASI default settings
list(APPEND CMAKE_MODULE_PATH "$ENV{ASI}/cmake/Modules")
include(asv_cmake_defaults)
asv_cmake_defaults( )
###############

# includes
install(
    FILES zmq.hpp zmq_addon.hpp
    DESTINATION include/cppzmq
    )

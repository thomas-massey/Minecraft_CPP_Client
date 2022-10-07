# CMakeList.txt : CMake project for Minecraft_CPP_Client, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("Minecraft_CPP_Client")

# Add source to this project's executable.
add_executable (Minecraft_CPP_Client "Minecraft_CPP_Client.cpp" "Minecraft_CPP_Client.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Minecraft_CPP_Client PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.

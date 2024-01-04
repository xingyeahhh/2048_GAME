# CMakeList.txt : CMake project for 2048_GAME, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (2048_GAME "grid.cpp" "grid.h" "game.h" "game.cpp" "main.cpp")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET 2048_GAME PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.

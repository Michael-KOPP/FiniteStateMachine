cmake_minimum_required (VERSION 3.8)

set(CMAKE_CXX_STANDARD 20)

add_executable(LockingFSM "FiniteStateMachine.cpp")

target_link_libraries(LockingFSM PRIVATE finite_state_machine)


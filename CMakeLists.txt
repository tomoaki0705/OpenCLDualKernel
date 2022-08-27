# minimum requirement
cmake_minimum_required(VERSION 3.6)

# solution
project(sampleOpenCL)

SET(TARGET_NAME dualKernel)

# set include directory
include_directories("/home/firefly/opencv-fork/3rdparty/include/opencl/1.2")

add_executable(${TARGET_NAME} main.cpp)

# set the link
#target_link_libraries(${TARGET_NAME} ${OpenCV_LIBS})

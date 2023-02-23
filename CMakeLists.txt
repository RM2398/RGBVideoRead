cmake_minimum_required(VERSION 3.1)

project(
  lineFollower
  VERSION 1.0
  LANGUAGES CXX)

find_package(OpenCV REQUIRED)

# add_executable(ImageColors main.cpp)
add_executable(RGB-Videoread Videoread.cpp)
# add_executable(HSV-Videoread VideoreadHSV.cpp)


# target_link_libraries(ImageColors ${OpenCV_LIBS})
target_link_libraries(RGB-Videoread ${OpenCV_LIBS})
# target_link_libraries(HSV-Videoread ${OpenCV_LIBS})

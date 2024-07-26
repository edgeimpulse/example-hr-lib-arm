# example-hr-lib-arm
Example of building SDK with hr library

# Key changes from example-standalone-*
- You must define macro EI_CLASSIFIER_HR_LIB=1
  - In this example, this is done in the CMakeLists file
- You must pass libhr.a into the liner
  - In CMake here, this is done via: target_link_libraries(${PROJECT_N} PRIVATE ${CMAKE_SOURCE_DIR}/libhr.a)

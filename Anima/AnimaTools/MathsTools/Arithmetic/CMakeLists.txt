add_subdirectory(AverageImages)

if (USE_RPI AND RPI_FOUND)
  add_subdirectory(DenseTransformArithmetic)
endif()

add_subdirectory(AverageLinearTransforms)
add_subdirectory(CovarianceImages)
add_subdirectory(ImageArithmetic)
add_subdirectory(LinearTransformToSVF)
add_subdirectory(LinearTransformArithmetic)

# SmartRedis-scrap


TODO:
1. Instructions on how to run mutli-GPU : include modules & why

CMake Warning at deps/linux-x64-gpu/libtorch/share/cmake/Caffe2/Modules_CUDA_fix/upstream/FindCUDA.cmake:790 (message):
  Failed to execute '/lus/scratch/smartsim/local/cudatoolkit/11.7/bin/nvcc
  --version'
Call Stack (most recent call first):
  deps/linux-x64-gpu/libtorch/share/cmake/Caffe2/Modules_CUDA_fix/FindCUDA.cmake:11 (include)
  deps/linux-x64-gpu/libtorch/share/cmake/Caffe2/public/cuda.cmake:29 (find_package)
  deps/linux-x64-gpu/libtorch/share/cmake/Caffe2/Caffe2Config.cmake:88 (include)
  deps/linux-x64-gpu/libtorch/share/cmake/Torch/TorchConfig.cmake:68 (find_package)
  CMakeLists.txt:184 (FIND_PACKAGE)


CMake Warning at deps/linux-x64-gpu/libtorch/share/cmake/Caffe2/public/cuda.cmake:31 (message):
  Caffe2: CUDA cannot be found.  Depending on whether you are building Caffe2
  or a Caffe2 dependent library, the next warning / error will give you more
  info.
Call Stack (most recent call first):
  deps/linux-x64-gpu/libtorch/share/cmake/Caffe2/Caffe2Config.cmake:88 (include)
  deps/linux-x64-gpu/libtorch/share/cmake/Torch/TorchConfig.cmake:68 (find_package)
  CMakeLists.txt:184 (FIND_PACKAGE)


CMake Error at deps/linux-x64-gpu/libtorch/share/cmake/Caffe2/Caffe2Config.cmake:90 (message):
  Your installed Caffe2 version uses CUDA but I cannot find the CUDA
  libraries.  Please set the proper CUDA prefixes and / or install CUDA.
Call Stack (most recent call first):
  deps/linux-x64-gpu/libtorch/share/cmake/Torch/TorchConfig.cmake:68 (find_package)
  CMakeLists.txt:184 (FIND_PACKAGE)

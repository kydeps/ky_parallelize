find_package(glog)

add_library(ky_parallelize parallelize.cc)
target_link_libraries(ky_parallelize PRIVATE glog::glog)
KyDepsPackageLibraryTarget(ky_parallelize "ky")

project(ndmanager-plugins-src)
cmake_minimum_required(VERSION 2.8.6)

add_subdirectory(process)
add_subdirectory(process_extractchannels)
#add_subdirectory(process_extractleds)
add_subdirectory(process_extractspikes)
add_subdirectory(process_medianfilter)
add_subdirectory(process_medianthreshold)
add_subdirectory(process_merge)
add_subdirectory(process_nlxconvert)
add_subdirectory(process_pca)
add_subdirectory(process_removeartefacts)
add_subdirectory(process_resample)
add_subdirectory(process_smrconvert)
add_subdirectory(xpathReader)

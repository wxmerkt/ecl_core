###############################################################################
# FILES
###############################################################################

file(GLOB HEADERS RELATIVE ${CMAKE_CURRENT_SOURCE_DIR} *.hpp)
  
install(FILES ${HEADERS} DESTINATION include/ecl/containers/common)

# Date  : 2024-12-18
# Author: tuwenbo

target_include_directories(${EXECUTABLE_NAME} PRIVATE
  "${CMAKE_CURRENT_LIST_DIR}/Include"
)

target_sources(${EXECUTABLE_NAME} PRIVATE
  "${CMAKE_CURRENT_LIST_DIR}/Source/Templates/system_stm32h7xx.c"
)

file(GLOB MODBUS_SRC
    "*.h"
    "*.c"
)

set(CMAKE_INCLUDE_CURRENT_DIR 1)

add_library(modbus SHARED ${MODBUS_SRC})


# Copyright (C) G2Labs Grzegorz Grzęda - All Rights Reserved
# Unauthorized copying of this file, via any medium is strictly prohibited
# Proprietary and confidential
# Written by Grzegorz Grzęda <grzegorz.grzeda@g2labs.pl>, 03.2023
target_include_directories(${PROJECT_NAME}
    PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}
)

target_sources(${PROJECT_NAME}
    PRIVATE font.c
)

add_subdirectory(fonts)

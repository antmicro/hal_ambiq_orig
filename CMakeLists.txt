# Ambiq HAL
#
# Copyright (c) 2023 Antmicro Ltd <www.antmicro.com>
#
# SPDX-License-Identifier: Apache-2.0

if(CONFIG_HAS_AMBIQ_HAL)
    zephyr_include_directories(
        CMSIS/AmbiqMicro/Include
        devices
        utils
        )
    add_subdirectory(mcu)
    add_subdirectory(boards)
endif()

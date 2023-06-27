# Ambiq HALA
#
# Copyright (c) 2023 Antmicro Ltd <www.antmicro.com>
#
# SPDX-License-Identifier: Apache-2.0

if(CONFIG_BOARD_APOLLO4P_EVB)
    zephyr_include_directories(apollo4p_evb/bsp)
    zephyr_sources(apollo4p_evb/bsp/am_bsp_pins.c)
    zephyr_sources(apollo4p_evb/bsp/am_bsp.c)
endif()

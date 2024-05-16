# Copyright (c) 2022 The ZMK Contributors
# SPDX-License-Identifier: MIT

zephyr_library_amend()

zephyr_library_sources_ifdef(CONFIG_GPIO_PCF857X gpio_pcf857x.c)
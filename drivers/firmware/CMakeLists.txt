# SPDX-License-Identifier: Apache-2.0

# zephyr-keep-sorted-start
add_subdirectory_ifdef(CONFIG_ARM_SCMI scmi)
add_subdirectory_ifdef(CONFIG_TISCI tisci)
# zephyr-keep-sorted-stop

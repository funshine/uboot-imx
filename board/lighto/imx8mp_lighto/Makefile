#
# Copyright 2019 NXP
#
# SPDX-License-Identifier:      GPL-2.0+
#

obj-y += imx8mp_lighto.o mmc.o

ifdef CONFIG_SPL_BUILD
obj-y += spl.o
obj-$(CONFIG_IMX8M_LPDDR4) += lpddr4_timing_imx8mp-lighto-2gb.o lpddr4_timing_imx8mp-lighto-4gb.o
endif

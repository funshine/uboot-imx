# SPDX-License-Identifier: GPL-2.0+
#
# Copyright (C) Lighto

# obj-$(CONFIG_USB_TCPC) += tcpc.o

MINIMAL=

ifdef CONFIG_SPL_BUILD
# ifdef CONFIG_SPL_INIT_MINIMAL
# MINIMAL=y
# endif
# necessary to create built-in.o
obj- := __dummy__.o
endif

ifdef MINIMAL
# necessary to create built-in.o
# obj- := __dummy__.o
endif

# SPDX-License-Identifier: GPL-2.0

# Overlays Instructions
# https://docs.armbian.com/User-Guide_Armbian_overlays/

dtbo-$(CONFIG_ARCH_SUNXI) += \
	sun50i-h616-disable_uart0.dtbo \
	sun50i-h616-i2c1.dtbo \
	sun50i-h616-i2c2.dtbo \
	sun50i-h616-i2c4.dtbo \
	sun50i-h616-spidev0_0.dtbo \
	sun50i-h616-spi1.dtbo \
	sun50i-h616-spidev1_0.dtbo \
	sun50i-h616-spidev1_1.dtbo \
	sun50i-h616-spidev1_2.dtbo \
	sun50i-h616-tft35.dtbo \
	sun50i-h616-uart2.dtbo \
	sun50i-h616-uart4.dtbo 

scr-$(CONFIG_ARCH_SUNXI) += \
	sun50i-h616-fixup.scr
	
targets += $(dtbo-y) $(scr-y) $(dtbotxt-y)

always		:= $(dtbo-y) $(scr-y) $(dtbotxt-y)
clean-files	:= *.dtbo *.scr

#
# Makefile for misc devices that really don't fit anywhere else.
#

obj-$(CONFIG_IBM_ASM)		+= ibmasm/
obj-$(CONFIG_AD525X_DPOT)	+= ad525x_dpot.o
obj-$(CONFIG_AD525X_DPOT_I2C)	+= ad525x_dpot-i2c.o
obj-$(CONFIG_AD525X_DPOT_SPI)	+= ad525x_dpot-spi.o
0bj-$(CONFIG_INTEL_MID_PTI)	+= pti.o
obj-$(CONFIG_ATMEL_PWM)		+= atmel_pwm.o
obj-$(CONFIG_ATMEL_SSC)		+= atmel-ssc.o
obj-$(CONFIG_ATMEL_TCLIB)	+= atmel_tclib.o
obj-$(CONFIG_BMP085)		+= bmp085.o
obj-$(CONFIG_ICS932S401)	+= ics932s401.o
obj-$(CONFIG_LKDTM)		+= lkdtm.o
obj-$(CONFIG_TIFM_CORE)       	+= tifm_core.o
obj-$(CONFIG_TIFM_7XX1)       	+= tifm_7xx1.o
obj-$(CONFIG_PHANTOM)		+= phantom.o
obj-$(CONFIG_SENSORS_BH1780)	+= bh1780gli.o
obj-$(CONFIG_SENSORS_BH1770)	+= bh1770glc.o
obj-$(CONFIG_SENSORS_APDS990X)	+= apds990x.o
obj-$(CONFIG_SGI_IOC4)		+= ioc4.o
obj-$(CONFIG_ENCLOSURE_SERVICES) += enclosure.o
obj-$(CONFIG_KGDB_TESTS)	+= kgdbts.o
obj-$(CONFIG_SGI_XP)		+= sgi-xp/
obj-$(CONFIG_SGI_GRU)		+= sgi-gru/
obj-$(CONFIG_CS5535_MFGPT)	+= cs5535-mfgpt.o
obj-$(CONFIG_HP_ILO)		+= hpilo.o
obj-$(CONFIG_APDS9802ALS)	+= apds9802als.o
obj-$(CONFIG_ISL29003)		+= isl29003.o
obj-$(CONFIG_ISL29020)		+= isl29020.o
obj-$(CONFIG_SENSORS_TSL2550)	+= tsl2550.o
obj-$(CONFIG_EP93XX_PWM)	+= ep93xx_pwm.o
obj-$(CONFIG_DS1682)		+= ds1682.o
obj-$(CONFIG_TI_DAC7512)	+= ti_dac7512.o
obj-$(CONFIG_UID_STAT)		+= uid_stat.o
obj-$(CONFIG_C2PORT)		+= c2port/
obj-$(CONFIG_IWMC3200TOP)      += iwmc3200top/
obj-$(CONFIG_HMC6352)		+= hmc6352.o
obj-y				+= eeprom/
obj-y				+= cb710/
obj-$(CONFIG_SPEAR13XX_PCIE_GADGET)	+= spear13xx_pcie_gadget.o
obj-$(CONFIG_VMWARE_BALLOON)	+= vmw_balloon.o
obj-$(CONFIG_ARM_CHARLCD)	+= arm-charlcd.o
obj-$(CONFIG_PCH_PHUB)		+= pch_phub.o
obj-y				+= ti-st/
obj-$(CONFIG_AB8500_PWM)	+= ab8500-pwm.o
obj-y				+= lis3lv02d/
obj-y				+= carma/
obj-$(CONFIG_WL127X_RFKILL)	+= wl127x-rfkill.o
obj-$(CONFIG_APANIC)		+= apanic.o
obj-$(CONFIG_SENSORS_AK8975)	+= akm8975.o
obj-$(CONFIG_OMAP_DIE_TEMP_SENSOR)	+= omap_temp_sensor.o
#LGE_SJIT 09/28/2011 [mohamed.khadri@lge.com] BT control path 
obj-$(CONFIG_LBEE9QMB_RFKILL)	+= lbee9qmb-rfkill.o
obj-$(CONFIG_BD_ADDRESS)       += bd_address.o
#LGE_SJIT 09/28/2011 [mohamed.khadri@lge.com] BT control path
obj-$(CONFIG_CDC_TCXO)		+= cdc_tcxo.o

# LGE_CHANGE [younglae.kim@lge.com] 2012-03-26 mpu3050 will be used for P2
# LGE_SJIT 2011-11-24 [dojip.kim@lge.com] will be use inv_mpu instead of this
# LGE_CHANGE [eugene.goh] 2011-07-01
obj-$(CONFIG_MPU_SENSORS_MPU3050)   += mpu3050/
#obj-y				+= inv_mpu/
# LGE_CHANGE [younglae.kim@lge.com] 2012-04-18 BMC050 will be used for U2
obj-$(CONFIG_SENSORS_BMC050)        += bmc050/
obj-$(CONFIG_TWL6040_VIB)	+= twl6040-vib.o
obj-$(CONFIG_CDC_TCXO)		+= cdc_tcxo.o
obj-$(CONFIG_GCCORE)		+= gcx/gccore/
obj-$(CONFIG_GCBV)		+= gcx/gcbv/
obj-$(CONFIG_GCIOCTL)		+= gcx/gcioctl/
# LGE_SJIT 2011-11-29 [dojip.kim@lge.com] add tspdrv from P940 GB
# LGE_CHANGE [seungmoon.lee@lge.com] 2011-08-18
obj-$(CONFIG_TSPDRV)		+= tspdrv/

# RIP-12331 : handling CP Crash of RIL Recovery
obj-$(CONFIG_LGE_MODEM_WATCHER)	+= modem_watcher.o
obj-$(CONFIG_TS0710_MUX)	+= ts0710mux/
obj-$(CONFIG_CACHE2DMANAGER)	+= cache-2dmanager/
obj-$(CONFIG_FSYNC_CONTROL)  += fsync_control.o

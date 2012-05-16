obj-y += io.o dma.o memory.o timer.o
obj-y += clock.o
obj-$(CONFIG_CPU_FREQ_MSM) += cpufreq.o
obj-y += socinfo.o

ifndef CONFIG_ARCH_MSM8X60
obj-y += dma.o
endif

obj-y += nand_partitions.o
obj-y += pmic.o
obj-y += drv_callback.o
obj-y += htc_board_tags.o
obj-y += socinfo.o

obj-$(CONFIG_ARCH_MSM_SCORPION) += idle-v7.o
obj-$(CONFIG_ARCH_MSM_SCORPION) += arch-init-scorpion.o

obj-$(CONFIG_ARCH_QSD8X50) += acpuclock-qsd8x50.o
obj-$(CONFIG_MSM_CPU_AVS) += avs.o avs_hw.o

ifndef CONFIG_ARCH_MSM8X60
obj-y += irq.o
endif

obj-$(CONFIG_ARCH_MSM8X60) += clock-dummy.o iommu.o iommu_dev.o devices-msm8x60-iommu.o
obj-$(CONFIG_MSM_PROC_COMM) += proc_comm.o clock-pcom.o vreg.o
obj-$(CONFIG_MSM_PROC_COMM) += clock.o
obj-$(CONFIG_MSM_PROC_COMM) += footswitch-pcom.o
obj-$(CONFIG_ARCH_QSD8X50) += sirc.o
obj-$(CONFIG_MSM_FIQ_SUPPORT) += fiq_glue.o
obj-$(CONFIG_MSM_SMD) += smd.o smd_debug.o smem_log.o
obj-$(CONFIG_MSM_SMD) += smd_tty.o smd_qmi.o
obj-$(CONFIG_MSM_SMD) += last_radio_log.o 
obj-$(CONFIG_MSM_DAL) += dal.o
obj-$(CONFIG_MSM_ONCRPCROUTER) += smd_rpcrouter.o
obj-$(CONFIG_MSM_ONCRPCROUTER) += smd_rpcrouter_device.o
obj-$(CONFIG_MSM_ONCRPCROUTER) += smd_rpcrouter_servers.o
obj-$(CONFIG_MSM_ONCRPCROUTER) += smd_rpcrouter_xdr.o
obj-$(CONFIG_MSM_RPCSERVERS) += rpc_server_dog_keepalive.o
obj-$(CONFIG_MSM_RPCSERVERS) += rpc_server_time_remote.o
obj-$(CONFIG_MSM_QDSP6) += qdsp6/
obj-$(CONFIG_PM) += pm.o
obj-$(CONFIG_CPU_FREQ) += cpufreq.o
obj-$(CONFIG_HTC_ACOUSTIC_QSD) += htc_acoustic_qsd.o
obj-$(CONFIG_HTC_BATTCHG) += smb329.o htc_battery.o

obj-$(CONFIG_MACH_TROUT) += board-trout.o board-trout-gpio.o board-trout-mmc.o devices-msm7x00.o
obj-$(CONFIG_MACH_HALIBUT) += board-halibut.o devices-msm7x00.o
obj-$(CONFIG_ARCH_MSM7X30) += board-msm7x30.o devices-msm7x30.o
obj-$(CONFIG_ARCH_QSD8X50) += board-qsd8x50.o devices-qsd8x50.o
obj-$(CONFIG_ARCH_MSM8X60) += board-msm8x60.o

obj-$(CONFIG_ARCH_MSM7X30) += gpiomux-7x30.o gpiomux-v1.o gpiomux.o
obj-$(CONFIG_ARCH_QSD8X50) += gpiomux-8x50.o gpiomux-v1.o gpiomux.o
obj-$(CONFIG_ARCH_MSM8X60) += gpiomux-8x60.o gpiomux-v2.o gpiomux.o
ifndef CONFIG_MSM_V2_TLMM
obj-y	+= gpio.o generic_gpio.o
endif

obj-$(CONFIG_MACH_INCREDIBLEC) += board-incrediblec.o board-incrediblec-panel.o board-incrediblec-tv.o
obj-$(CONFIG_MACH_INCREDIBLEC) += board-incrediblec-keypad.o board-incrediblec-mmc.o
obj-$(CONFIG_MACH_INCREDIBLEC) += board-incrediblec-rfkill.o htc_wifi_nvs.o  board-incrediblec-audio.o
obj-$(CONFIG_MACH_INCREDIBLEC) += board-incrediblec-wifi.o htc_awb_cal.o
obj-$(CONFIG_MACH_INCREDIBLEC) += board-incrediblec-microp.o htc_bluetooth.o
obj-$(CONFIG_MACH_INCREDIBLEC) += msm_vibrator.o
obj-$(CONFIG_MACH_INCREDIBLEC) += proc_engineerid.o board-incrediblec-tpa6130.o


obj-$(CONFIG_MICROP_COMMON) += atmega_microp_common.o
obj-$(CONFIG_HTC_HEADSET_MGR) += htc_headset_mgr.o
obj-$(CONFIG_HTC_HEADSET_GPIO) += htc_headset_gpio.o
obj-$(CONFIG_HTC_HEADSET_MICROP) += htc_headset_microp.o
obj-$(CONFIG_PERFLOCK) += perflock.o
obj-$(CONFIG_PERFLOCK) += htc_set_perflock.o

obj-$(CONFIG_ARCH_MSM_FLASHLIGHT) += msm_flashlight.o



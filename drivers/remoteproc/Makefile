# SPDX-License-Identifier: GPL-2.0
#
# Generic framework for controlling remote processors
#

obj-$(CONFIG_REMOTEPROC)		+= remoteproc.o
remoteproc-y				:= remoteproc_core.o
remoteproc-y				+= remoteproc_coredump.o
remoteproc-y				+= remoteproc_debugfs.o
remoteproc-y				+= remoteproc_sysfs.o
remoteproc-y				+= remoteproc_virtio.o
remoteproc-y				+= remoteproc_elf_loader.o
obj-$(CONFIG_REMOTEPROC_CDEV)		+= remoteproc_cdev.o
obj-$(CONFIG_IMX_REMOTEPROC)		+= imx_rproc.o
obj-$(CONFIG_INGENIC_VPU_RPROC)		+= ingenic_rproc.o
obj-$(CONFIG_MTK_SCP)			+= mtk_scp.o mtk_scp_ipi.o
obj-$(CONFIG_OMAP_REMOTEPROC)		+= omap_remoteproc.o
obj-$(CONFIG_WKUP_M3_RPROC)		+= wkup_m3_rproc.o
obj-$(CONFIG_DA8XX_REMOTEPROC)		+= da8xx_remoteproc.o
obj-$(CONFIG_KEYSTONE_REMOTEPROC)	+= keystone_remoteproc.o
obj-$(CONFIG_QCOM_PIL_INFO)		+= qcom_pil_info.o
obj-$(CONFIG_QCOM_RPROC_COMMON)		+= rproc_qcom_common.o
rproc_qcom_common-y			:= qcom_common.o qcom_tracepoints.o
obj-$(CONFIG_QCOM_Q6V5_COMMON)		+= qcom_q6v5.o
obj-$(CONFIG_QCOM_Q6V5_ADSP)		+= qcom_q6v5_adsp.o
obj-$(CONFIG_QCOM_Q6V5_MSS)		+= qcom_q6v5_mss.o
obj-$(CONFIG_QCOM_Q6V5_PAS)		+= qcom_q6v5_pas.o
obj-$(CONFIG_QCOM_SPSS)			+= qcom_spss.o
obj-$(CONFIG_QCOM_ESOC)			+= qcom_esoc.o
qcom_esoc-y				+= esoc_bus.o
qcom_esoc-$(CONFIG_QCOM_ESOC_DEV)	+= esoc_dev.o
qcom_esoc-$(CONFIG_QCOM_ESOC_CLIENT)	+= esoc_client.o
qcom_esoc-$(CONFIG_QCOM_ESOC_MDM_4X)	+= esoc-mdm-pon.o esoc-mdm-4x.o
qcom_esoc-$(CONFIG_QCOM_ESOC_MDM_DRV)	+= esoc-mdm-drv.o
qcom_esoc-$(CONFIG_QCOM_ESOC_DBG_ENG)	+= esoc-mdm-dbg-eng.o
ccflags-$(CONFIG_ESOC_DEBUG)		:= -DDEBUG
obj-$(CONFIG_QCOM_Q6V5_WCSS)		+= qcom_q6v5_wcss.o
obj-$(CONFIG_QCOM_SYSMON)		+= qcom_sysmon.o
obj-$(CONFIG_QCOM_WCNSS_PIL)		+= qcom_wcnss_pil.o
qcom_wcnss_pil-y			+= qcom_wcnss.o
qcom_wcnss_pil-y			+= qcom_wcnss_iris.o
obj-$(CONFIG_ST_REMOTEPROC)		+= st_remoteproc.o
obj-$(CONFIG_ST_SLIM_REMOTEPROC)	+= st_slim_rproc.o
obj-$(CONFIG_STM32_RPROC)		+= stm32_rproc.o
obj-$(CONFIG_TI_K3_DSP_REMOTEPROC)	+= ti_k3_dsp_remoteproc.o
obj-$(CONFIG_TI_K3_R5_REMOTEPROC)	+= ti_k3_r5_remoteproc.o
obj-$(CONFIG_QCOM_RPROC_HELIOS)   += qcom_rproc_helios.o
obj-$(CONFIG_XIAOMI_ZISP_REMOTEPROC)	+= zisp_mcu.o
zisp_mcu-y				+= zisp_mcu_rproc.o
zisp_mcu-y				+= zisp3_pci.o
zisp_mcu-y				+= zisp3_spi.o
zisp_mcu-y				+= zisp_rproc_utils.o

ccflags-$(CONFIG_CAIF_DEBUG) := -DDEBUG

# Serial interface
obj-$(CONFIG_CAIF_TTY) += caif_serial.o

# SPI slave physical interfaces module
cfspi_slave-objs := caif_spi.o caif_spi_slave.o
obj-$(CONFIG_CAIF_SPI_SLAVE) += cfspi_slave.o

# Shared memory
caif_shm-objs := caif_shmcore.o caif_shm_u5500.o
obj-$(CONFIG_CAIF_SHM) += caif_shm.o

# HSI interface
obj-$(CONFIG_CAIF_HSI) += caif_hsi.o

# Tegra specific SPI slave physical interfaces module
tegra_cfspi_slave-objs := tegra_caif_sspi.o
obj-$(CONFIG_TEGRA_SPI_CAIF) += tegra_cfspi_slave.o

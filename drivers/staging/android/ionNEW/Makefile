# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_ION) +=	ion.o ion_heap.o ion_page_pool.o ion_system_heap.o \
			ion_carveout_heap.o ion_chunk_heap.o ion_cma_heap.o
obj-$(CONFIG_ION_SYSTEM_HEAP) += ion_system_heap.o ion_page_pool.o
obj-$(CONFIG_ION_CMA_HEAP) += ion_cma_heap.o
obj-$(CONFIG_ION_TEST) += ion_test.o
ifdef CONFIG_COMPAT
obj-$(CONFIG_ION) += compat_ion.o
endif

obj-$(CONFIG_ION_DUMMY) += ion_dummy_driver.o
obj-$(CONFIG_ION_ROCKCHIP) += rockchip/
obj-$(CONFIG_ION_TEGRA) += tegra/


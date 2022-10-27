# GD32 BSP移植说明

GD32 系列 BSP 目前支持情况如下表所示：

| **BSP 文件夹名称**                               | **开发板名称**                       |
|:------------------------------------------- |:------------------------------- |
| **ARM 系列** |  |
| **F1 系列**                                   |                                 |
| [gd32103c-eval](bsp/gd32/arm/gd32103c-eval) | 兆易创新 官方 GD32103C-EVAL 开发板(未验证) |
| [gd32105c-eval](bsp/gd32/arm/gd32105c-eval) | 兆易创新 官方 GD32105C-EVAL 开发板(未验证) |
| [gd32105r-start](bsp/gd32/arm/gd32105r-start) | 兆易创新 官方 GD32105R-START 开发板      |
| [gd32107c-eval](bsp/gd32/arm/gd32107c-eval) | 兆易创新 官方 GD32107c-EVAL 开发板(未验证) |
| **F2 系列**                                   |                                 |
| [gd32205r-start](bsp/gd32/arm/gd32205r-start) | 兆易创新 官方 GD32205R-START 开发板      |
| [gd32207i-eval](bsp/gd32/arm/gd32207i-eval) | 兆易创新 官方 GD32207I-EVAL 开发板 |
| **F3 系列**                                   |                                 |
| [gd32303e-eval](bsp/gd32/arm/gd32303e-eval)   | 兆易创新 官方 GD32303E-EVAL 开发板(未验证) |
| [gd32305r-start](bsp/gd32/arm/gd32305r-start) | 兆易创新 官方 GD32305R-START 开发板      |
| [gd32307e-start](bsp/gd32/arm/gd32307e-start) | 兆易创新 官方 GD32307E-START 开发板 |
| **F4 系列**                                   |                                 |
| [gd32407v-start](bsp/gd32/arm/gd32407v-start) | 兆易创新 官方 GD32407V-START 开发板      |
| [gd32450z-eval](bsp/gd32/arm/gd32450z-eval)   | 兆易创新 官方 GD32450Z-EVAL 开发板(未验证) |
|  |  |
| **RISC-V 系列** |  |
| **VF1 系列** |  |
| [gd32vf103v-eval](bsp/gd32/risc-v/gd32vf103v-eval) | 兆易创新 官方 GGD32VF103V-EVAL 开发板 |
| [gd32vf103r-start](bsp/gd32/risc-v/gd32vf103r-start) | 兆易创新 官方 GD32VF103R-START 开发板 |



# 移植文档

**BruceOu的博客**：

[手把手教你使用RT-Thread制作GD32 ARM系列BSP](https://blog.bruceou.cn/2022/01/teach-you-how-to-use-rt-thread-to-make-gd32-arm-series-bsp/1058/)

[手把手教你使用RT-Thread制作GD32 RISC-V系列BSP](https://blog.bruceou.cn/2022/06/teach-you-how-to-use-rt-thread-to-make-gd32-riscv-series-bsp/1706/)


**BruceOu的CSDN**：

[手把手教你使用RT-Thread制作GD32 ARM系列BSP](https://bruceou.blog.csdn.net/article/details/120243537)

[手把手教你使用RT-Thread制作GD32 RISC-V系列BSP](https://bruceou.blog.csdn.net/article/details/125211614)



# 版本更新

## 2021-09-04_V0.0.1

1.完成GD32 BSP架构

2.移植GD32407V-START 开发板

3.实现GPIO和USART驱动

4.撰写移植文档

## 2021-12-31_V0.0.2

1.完善GD32 BSP架构，本 BSP 为开发者提供 MDK4、MDK5，并且支持 ENV开发 (GCC开发环境)，支持RT-Thread Studio开发

2.新增gd32103c-eval, gd32105c-eval, gd32105r-start, gd32107c-eval, gd32205r-start, gd32303e-eval, gd32305r-start, gd32450z-eval 8款BSP

3.新增I2C和SPI驱动

4.GD32 F1 ,GD32 F2, GD32 F3, GD32 F4增加相应GCC版本的启动文件



## 2022-05-21_V1.0.0

1.进一步优化GD32 BSP 架构

2.优化串口、ADC驱动

3.新增gd32207i-eval， gd32307e-start 两款BSP



## 2022-06-09_V2.0.0

1.优化GD32 BSP 架构，分为ARM 和RISC-V系列

2.新增RISC-V系列BSP

3.完善文档



## 2022-06-25_V2.1.0

1.新增IAR开发环境

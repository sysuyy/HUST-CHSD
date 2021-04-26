# HUST-CHSD
华中科技大学计算机硬件系统设计仿真实验的实验总结，该实验基于仿真软件Logisim与在线实践测评平台Educoder。  
The simulation experiment of CHSD(Computer Hardware System Design), based on Logisim and Educoder, via HUST(Huazhong University of Science and Technology).   

## 为什么创建这个仓库  
这学期有幸当上了之前组原老师的助教，这门课使用的就是华科的实验方案，以前学习这门课的时候，课程没有要求把全部实验做完，也不够时间，于是想趁着这个机会，把整个实验课程完完整整做一遍，同时对实验做一些总结，放在网上，没准对其他同学有用。  

## 资料  
[计算机硬件系统设计MOOC](https://www.icourse163.org/course/HUST-1205809816)  
[计算机硬件组成原理(微课版)谭志虎](https://book.douban.com/subject/35379794/)  
[Educoder自己动手画CPU《计算机组织与结构实验》](https://www.educoder.net/paths/1426)  
实验相关的软件包在Educoder平台上，请自行获取。  

## 实验列表  
### 计算机数据表示  
- 汉字国标码转区位码实验 [√]  
- 汉字机内码获取实验 [√]  
- 偶校验编码设计 [√]  
- 偶校验编码电路设计 [√]  
- 16位海明编码电路设计 [√]  
- 16位海明解码电路设计 [√]  
- 海明编码流水传输实验 [√]  
- 16位CRC并行编码电路设计  
- CRC编码流水传输设计

### 运算器设计  
- 8位可控加减法电路设计  [√]
- CLA182四位先行进位电路设计 [√]
- 4位快速加法器设计 [√]
- 16位快速加法器设计 [√]
- 32位快速加法器设计 [√]
- 5位无符号阵列乘法器设计
- 6位有符号补码阵列乘法器
- 乘法流水线设计
- 原码一位乘法器设计
- 补码一位乘法器设计
- MIPS运算器设计

### 存储系统设计  
- 汉字字库存储芯片扩展实验 [√]
- MIPS寄存器文件设计 [√]
- MIPS RAM设计
- 全相联cache设计
- 直接相联cache设计
- 4路组相连cache设计
- 2路组相联cache设计

### 控制器设计  
- 单周期MIPS CPU设计
- 微程序地址转移逻辑设计
- MIPS微程序CPU设计
- 硬布线控制器状态机设计
- 多周期MIPS硬布线控制器CPU设计（排序程序）

### 单总线CPU设计  
#### 单总线CPU设计(定长指令周期3级时序)(HUST)
- MIPS指令译码器设计
- 定长指令周期---时序发生器FSM设计
- 定长指令周期---时序发生器输出函数设计
- 硬布线控制器组合逻辑单元
- 定长指令周期---硬布线控制器设计
- 定长指令周期---单总线CPU设计
#### 单总线CPU设计(变长指令周期3级时序)(HUST)
- MIPS指令译码器设计
- 变长指令周期---时序发生器FSM设计
- 变长指令周期---时序发生器输出函数设计
- 硬布线控制器组合逻辑单元
- 变长指令周期---硬布线控制器设计
- 变长指令周期---单总线CPU设计
#### 单总线CPU设计(现代时序)(HUST)
- MIPS指令译码器设计
- 单总线CPU微程序入口查找逻辑
- 单总线CPU微程序条件判别测试逻辑
- 单总线CPU微程序控制器设计
- 采用微程序的单总线CPU设计
- 现代时序硬布线控制器状态机设计
- 现代时序硬布线控制器设计

### 中断机制实现  
#### MIPS单周期CPU设计(24条指令)(HUST)
- 单周期CPU(24条指令)
- 单周期MIPS+单级中断
- 多级嵌套中断(EPC硬件堆栈保存)
- 多级嵌套中断(EPC内存堆栈保存)
#### 现代时序中断机制实现(HUST)
- MIPS指令译码器设计
- 支持中断的微程序入口查找逻辑
- 支持中断的微程序条件判别测试逻辑
- 支持中断的微程序控制器设计
- 支持中断的微程序单总线CPU设计
- 支持中断的现代时序硬布线控制器状态机设计
- 支持中断的现代时序硬布线控制器设计
#### 三级时序中断机制实现(HUST)
- 支持中断的时序发生器FSM设计
- 支持中断的时序发生器输出函数设计
- 中断信号控制器设计
- 支持中断的硬布线控制器设计
- 变长指令周期---单总线CPU设计

### 流水CPU设计  
- 理想流水线设计
- 气泡流水线设计(EX段分支3624版本)
- 重定向流水线(EX段分支2298版本)
- 气泡流水线设计(ID段分支3309版本)
- 重定向流水线设计(ID段分支2103版本)

## 日志

| 日期      | 完成事项                    |
| --------- | --------------------------- |
| 2021/3/27 | 完成计算机数据表示实验的1~7 |


# 数控脉宽脉冲信号发生器
# Numerical control pulse width pulse signal generator

本设计采用EDA技术，通过FPGA芯片实现了数控脉宽脉冲信号发生器的设计。
通过模100加法计数器、模100加减计数器、8位比较器、译码器来实现本设计。
采用传统设计方法和现代设计方法相结合的方案。
先用Multisim仿真软件对电路进行仿真，以此来证明设计的可行性；
随后将该电路分模块用VHDL语言进行描述；
然后通过ISE仿真软件模拟FPGA芯片运行，调试相关功能；
最后刷机进行实际测试运行。

代码：

FPGA/src/   https://github.com/LIGHTYUAN/FPGA/tree/master/src


截图：

FPGA/pictures/  https://github.com/LIGHTYUAN/FPGA/tree/master/pictures

## RV32I 指令解析

### 1.  整数计算

* 加法
    + **add** <br/>     R-type. 寄存器加
    + **addi** <br/>    I-type. 寄存器加短立即数

* 减法
    + **sub** <br/>     R-type. 寄存器减

* 逻辑
    + **and** <br/>     R-type. 寄存器与
    + **andi** <br/>    I-type. 寄存器和短立即数与
    + **or** <br/>      R-type. 寄存器或
    + **ori** <br/>     I-type. 寄存器和短立即数或
    + **xor** <br/>     R-type. 寄存器异或
    + **xori** <br/>    I-type. 寄存器和短立即数异或

* 移位
    + **sll** <br/>     R-type. 寄存器逻辑左移
    + **slli** <br/>    I-type. 寄存器逻辑左移某个立即数
    + **sra** <br/>     R-type. 寄存器算术右移
    + **srai** <br/>    R-type. 寄存器算术右移某个立即数

# Key_Word
关键字及其定义

## C语言

### 数据类型关键字
 (1) char ：声明字符型变量或函数

 (2) double ：声明双精度变量或函数

 (3) enum ：声明枚举类型

 (4) float：声明浮点型变量或函数

 (5) int： 声明整型变量或函数

 (6) long ：声明长整型变量或函数 

 (7) short ：声明短整型变量或函数 

 (8) signed：声明有符号类型变量或函数 

 (9) struct：声明结构体变量或函数 

 (10) union：声明联合数据类型 

 (11) unsigned：声明无符号类型变量或函数 

 (12) void ：声明函数无返回值或无参数，声明无类型指针（基本上就这三个作用）

### 控制语句关键字

#### 循环语句
 (1) for：一种循环语句(可意会不可言传） 

 (2) do ：循环语句的循环体 

 (3) while ：循环语句的循环条件 

 (4) break：跳出当前循环 

 (5) continue：结束当前循环，开始下一轮循环 

#### 条件语句
 (1)if: 条件语句 

 (2)else ：条件语句否定分支（与 if 连用） 

 (3)goto：无条件跳转语句 

#### 开关语句
 (1)switch :用于开关语句 

 (2)case：开关语句分支 

 (3)default：开关语句中的“其他”分支 

#### 返回语句
 return ：子程序返回语句（可以带参数，也看不带参数）

### 类型修饰符
 (1)auto ：缺省，声明自动变量，一般不使用 

 (2)extern：声明变量是在其他文件声明（也可以看做是引用变量） 

 (3)register：声明寄存器变量，能实现对变量的快速访问
 > 编译器会尽量安排CPU中的寄存器存放该修饰的变量，但CUP寄存器满了的时候，变量会存在存储器中。另外，不能对该修饰符修饰的变量进行取址（&）操作

 (4)static ：声明静态变量
 > 该修饰符的特点是对该修饰符修饰的变量只能初始化一次

 (5)const ：声明只读常量，但是通过某些方法也能改变常量
 > 该修饰符相对于宏定义（#define）的优点在于可以节省空间，const定义常量从汇编的角度来看，只是给出了对应的内存地址，而不是象#define一样给出的是立即数，所以，const定义的常量在程序运行过程中只有一份拷贝（因为是全局的只读变量，存在静态区），而 #define定义的常量在内存中有若干个拷贝

 (6)volatile：说明变量在程序执行中可被隐含地改变，每一次对该类型变量的读取都会直接从地址处读取，不会被编译器优化

## 汇编语言基础

### 基本指令
![Loading......](https://github.com/BasenLi/Key_Word/blob/master/src/Photo/%E6%B1%87%E7%BC%96.png?raw=true)

### 寄存器组信息
![Loading......](https://github.com/BasenLi/Key_Word/blob/master/src/Photo/%E5%AF%84%E5%AD%98%E5%99%A8%E7%BB%84.png?raw=true)


## STM32

 (1)NMI:不可屏蔽中断
 
 (2)NVIC:嵌套向量中断控制器
 
 (3)[存储器映射](https://baike.baidu.com/item/存储器映射/9105968)：存储器映射是指把芯片中或芯片外的FLASH，RAM，外设，BOOTBLOCK等进行统一编址。即用地址来表示对象。
 
 (4)[bootblock](https://baike.baidu.com/item/bootblock/2318506?fr=aladdin):主板上的引导块Boot Block,BOOTBLOCK是BIOS中一段特定的区域，包含有用于引导的最小指令集，正常的BIOS升级操作不能消除这段信息。
 
 (5)互斥访问：假设有 A、B 两个线程都去调用对象 α 的方法 method1(),并且要求 A、B 两个线程是互斥调用 method1 的。具体来说，假设 method1 中有 4 个命令，一旦 A 调用了 method1，在执行 method1 中有 4 个命令的时候，B 不会调用 method1 方法，反之，依然。

## 金融

## 文件类

(1)[ini文件](https://baike.baidu.com/item/ini文件/9718973?fr=aladdin):.ini 文件是Initialization File的缩写，即初始化文件，是windows的系统配置文件所采用的存储格式，统管windows的各项配置，一般用户就用windows提供的各项图形化管理界面就可实现相同的配置了。

(2)[DLL文件](https://baike.baidu.com/item/DLL文件/4170556?fr=aladdin):DLL(Dynamic Link Library)文件为动态链接库文件，又称“应用程序拓展”，是软件文件类型。

## 哲学

 (1)[修斯底德陷阱](https://baike.baidu.com/item/修昔底德陷阱/7508870?fr=aladdin):“修昔底德陷阱”，是指一个新崛起的大国必然要挑战现存大国，而现存大国也必然会回应这种威胁，这样战争变得不可避免。

 (2)[唯物主义](https://baike.baidu.com/item/唯物主义/270875?fr=aladdin):唯物论，哲学理论，肯定世界的基本组成为物质，物质形式与过程是我们认识世界的主要途径，持着只有事实上的物质才是存在的实体的这一种观点，并且被认为是物理主义的一种形式。
 
 (3)[唯心主义](https://baike.baidu.com/item/唯心主义/188072?fr=aladdin):唯心主义的基本含义，是在思维和存在、精神和物质的关系这个哲学基本问题上，认为精神(意识)第一性，物质第二性，精神决定物质，物质是精神的产物。
 
 (4)[方法论](https://baike.baidu.com/item/方法论/82748?fr=aladdin):方法论是一种以解决问题为目标的理论体系或系统，通常涉及对问题阶段、任务、工具、方法技巧的论述。方法论会对一系列具体的方法进行分析研究、系统总结并最终提出较为一般性的原则。
 
 



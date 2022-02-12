# Useful-Tools
在学习中用到的实用things

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

一、C基础

1.# 预处理前解
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
    1. 符号 # 表示这是一个预处理指令，告诉编译器在编译源代码之前，要先执行一些操作。编译器在编译过程开始之前的预处理阶段会处理这些指令。
    
    2. stdio 是 “standard input & output” 的缩写，包含了编译器理解 printf() 以及其它输入 / 输出函数所需要的信息。
    ![001-C流程图](https://user-images.githubusercontent.com/47250430/153712016-a93c39e2-4465-47ff-9d7f-126759a4b803.png)
    
2.输入输出函数scanf/printf
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
    1.scanf() 函数中的表列是地址表列
    
3.指数表现形式
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
    1.e 或者 E 之前必须有数字，且 e 或者 E 后面必须为整数，如 32.23e3（表示 32.23*10^3），-323.34e-6（表示 -323.34*10^-6）
    
4.转义字符
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
![002-转义字符](https://user-images.githubusercontent.com/47250430/153711918-4f5c2119-e4a3-43dc-8953-a6c168a0f2bd.png)

5.小数在内存中形式
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
在存储时，系统将实型数据分成小数部分和指数部分两个部分、分别存储。如 3.14159 在内存中的存放形式如下图：
![003](https://user-images.githubusercontent.com/47250430/153712892-f23cbf06-c89b-41c9-905b-2bdc551fb29c.jpg)

6.浮点型数据所占的内存空间以及取值范围
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
![004](https://user-images.githubusercontent.com/47250430/153712915-d93ec30e-66d7-46c6-8718-a8bd9a23e30e.jpg)




# Java基础
## 1、 JDK和JRE的区别
 1、JDK(Java Development Kit)是Java开发工具包,JRE(Java Runtime Environment)Java运行环境
 
 2、JDK包含JRE,JRE包含JVM
## 2、 标识符定义
 由26个英文字母大小写、数字、0-9、符号_  $组成，并且只能以字母、下划线、美元符号开头。
## 3、 基本数据类型
   4种8类
   整数类型：byte/short/int/long
   浮点类型：float/double
   布尔类型：boolean
   字符类型：char
## 4、 为什么float范围比long大？
    因为他们的存储方式不一样
## 5、 下面a1和b1输出多少？
       int a = 126;
       byte a1 = (byte)a;   //126
       int b = 130;
       byte b1 = (byte)b;  //-126
       b1先截取b的八位，发现是负数，然后取反，再取补码（反码+1）





        
    

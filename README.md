# Java入门  

*println输出信息后会换行，print不会换行*  
*java.util.Scanner*
*main+Alt+/  -->main方法*  
*Syso+Alt+/  -->System.out.println();*  
*问题：public ststic HelloWorld{}，HelloWorld为什么要和源文件名一致？*   
*问题：为什么运行字节码文件不允许带后缀.class？*  

### 基本概念-1
基础核心Java SE，大型开发JavaEE，嵌入式开发Java ME。  
源文件(.java)通过编译器生成二进制的字节码文件(.class)(跨平台的基础)，通过解释器(针对平台)才能执行。  
Java虚拟机：JVM，Java开发工具包：JDK，Java运行环境：JRE  
### java安装-1
bin目录：常用javac.exe，java.exe  
lib目录：(.jar)库文件  
JAVA_HOME：配置JDK安装路径  
PATH：配置JDK命令文件的位置  
CLASSPATH：配置类库文件的位置  
### eclipse-1
创建project工程(资源管理,工程独立)-->创建package程序包(避免重名com.imooc)-->创建class源代码(类和文件名相同)
My eclipse工具
导出：project 右击属性，Location，拷贝project。
导入：空白处右击，import，找到project。

### 关键字-2
**数据类型**  
1. (基本 本身)整数类型：byte(1) short(2) int(4) long(8)
2. (基本 本身)浮点类型：float(4) double(8)    
3. (基本 本身)字符类型：char(2)
4. (基本 本身)布尔类型：boolean(1)（包含：true false）
5. (引用 地址)类：class
6. (引用 地址)接口：interface
7. (引用 地址)数组
8. (引用)字符串：String  
**逻辑运算**  
1. if else：条件语句
2. for do while：循环
3. continue：跳出继续下次循环
4. break：跳出循环
5. switch case default：多重条件(switch后面表达式必须是整型或字符型，case必须是常量数值或常量表达式)  
**修饰符**  
final：用于修饰常量，不允许改变
abstract：
private：
protected：
public：
static：
super ：
volatile：
**函数**  
return：返回
void：无类型
null：空
extends finally catch  package    import implements instanceof  new native try synchronized this throw throws transient

### javadoc命令从文档注释中提取内容-2
举例：'javadoc -d doc Demo03.java'

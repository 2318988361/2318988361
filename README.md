
//编写一个main方法
    public static void main(String[] args) {
        System.out.println("老付 is studing java!");
    }
}        

//运行结果
D:\0java\Java code>javac studying.java
studying.java:10: 错误: 类Hello是公共的, 应在名为 Hello.java 的文件中声明
public class Hello {
       ^
1 个错误

D:\0java\Java code>javac Hello.java

D:\0java\Java code>java Hello
老付 is studing java!             

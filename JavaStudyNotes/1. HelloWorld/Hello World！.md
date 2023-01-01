
```java
// HelloWorld.java
public class HelloWorld{  
    public static void main(String[] args){  
        System.out.println("Hello,World!");  
    }  
}
```

#### **详解**
- class -> 类
- HelloWorld ->类名
- public class -> 公开类，说明类名要与文件名一致
- 大括号内是类的内容，也叫类体
- public static void main(String[] args) -> 方法的定义，告诉Java这是程序入口，也就是程序开始执行的地方。
- 大括号内是方法的内容，也称方法体(method body)
- main 方法是Java程序的入口
- System.out.println是Java提供的内置功能，可以将内容输出
- 小括号里的内容是参数(parameter)
- 没有参数的情况下，System.out.println 会输出一行空行

注：
- 文件名与public类名相同；
- 编译方法：javac HelloWorld.java -> 生成HelloWorld.class文件 -> 运行 java HelloWorld 
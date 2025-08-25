---
hide:
  - footer
---
# 第一个程序 HelloWorld

## 安装 JDK

- 推荐 JDK 11 或更高版本。安装后确保 `java` 与 `javac` 在终端可用：

```bash
java -version
javac -version
```

## 创建文件并编译运行

创建文件 `HelloWorld.java`：

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

在命令行中执行：

```bash
javac HelloWorld.java
java HelloWorld
```

如果需要从命令行接收参数：

```java
public class ArgsDemo {
    public static void main(String[] args) {
        if (args.length > 0) {
            System.out.println(args[0]);
        }
    }
}
```

运行：

```bash
javac ArgsDemo.java
java ArgsDemo runoob
``` 
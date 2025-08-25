---
hide:
  - footer
---
# 基础语法要点

## 标识符与命名
- 类名首字母大写，方法与变量使用小驼峰。

## 基本数据类型
- 整型：`byte short int long`
- 浮点：`float double`
- 字符：`char`
- 布尔：`boolean`

## 运算符
- 算术、关系、逻辑、位运算、赋值、三元运算符。

## 控制流

```java
int n = 3;
if (n > 0) {
    System.out.println("positive");
} else if (n == 0) {
    System.out.println("zero");
} else {
    System.out.println("negative");
}

for (int i = 0; i < 3; i++) {
    System.out.println(i);
}

switch (n) {
    case 1 -> System.out.println("one");
    case 2 -> System.out.println("two");
    default -> System.out.println("other");
}
``` 
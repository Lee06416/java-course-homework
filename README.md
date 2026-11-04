# Java 程序设计课程作业

八次作业分别保存在 homework-01.zip 至 homework-08.zip 中。下载对应压缩包并解压即可查看 .java 源文件；各作业独立编译，第六次作业各子目录也独立编译，避免同名类冲突。

1. 环境搭建与 HelloWorld
2. 第一、二章基础练习
3. 第五章循环练习
4. 第七章数组练习
5. 正则表达式上机测试
6. 第九章课本例题
7. 第九章一星练习与 UML 类图
8. 第十一章课本例题（程序清单 11-1 至 11-10）

使用 JDK 11。第六次作业的 Point2D 示例附有 JavaFX 依赖。教材例题与练习来源：梁勇《Java语言程序设计与数据结构（基础篇）》，机械工业出版社，2018。

## 第八次作业运行方法

解压 homework-08.zip，进入 homework-08 文件夹后执行：

```sh
javac -encoding UTF-8 *.java
java TestCircleRectangle
java PolymorphismDemo
java DynamicBindingDemo
java CastingDemo
java TestArrayList
java DistinctNumbers
```

DistinctNumbers 从键盘读取整数，输入 0 后结束。GeometricObject、Circle、Rectangle 和 MyStack 是供其他程序使用的类，没有 main 方法，不能直接作为主程序运行。不要与第六、七次作业的同名类放到一起编译。

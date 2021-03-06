---
layout: post
title: c# .NET的面试知识点
date:   2016-12-09
categories: blog
---
c# .NET的面试知识点

- 什么是.NET？什么是CLI？什么是CLR？IL是什么？JIT是什么，它是如何工作的？GC是什么，简述一下GC的工作方式？
- 类（class）和结构（struct）的区别是什么？它们对性能有影响吗？.NET BCL里有哪些是类（结构），为什么它们不是结构（类）？在自定义类型时，您如何选择是类还是结构？
- 在.NET程序运行过程中，什么是堆，什么是栈？什么情况下会在堆（栈）上分配数据？它们有性能上的区别吗？“结构”对象可能分配在堆上吗？什么情况下会发生，有什么需要注意的吗？
- 泛型的作用是什么？它有什么优势？它对性能有影响吗？它在执行时的行为是什么？.NET BCL中有哪些泛型类型？举例说明平时编程中您定义的泛型类型。
- 异常的作用是什么？.NET BCL中有哪些常见的异常？在代码中您是如何捕获/处理异常的？在“catch (ex)”中，“throw”和“throw ex”有什么区别？您会如何设计异常的结构，什么情况下您会抛出异常？
- List<T>和T[]的区别是什么，平时你如何进行选择？Dictionary<TKey, TValue>是做什么的？.NET BCL中还有哪些常用的容器？它们分别是如何实现的（哪种数据结构）？分别是适用于哪些场景？
- 抽象类和接口有什么区别？使用时有什么需要注意的吗？如何选择是定义一个“完全抽象”的抽象类，还是接口？什么是接口的“显式实现”？为什么说它很重要？
- 字符串是引用类型类型还是结构类型？它和普通的引用类型相比有什么特别的地方吗？使用字符串时有什么需要注意的地方？为什么说StringBuilder比较高效？在连接多个字符串时，它无论何时都比直接相加更高效吗？
- 如何高效地进行数组复制？“二维数组”和“数组的数组”有什么区别？在使用双重循环遍历一个二维数组时，如何选择内外层的遍历顺序？
- 什么是元编程，.NET有哪些元编程的手段和场景？什么是反射？能否举一些反射的常用场景？有人说反射性能较差，您怎么看待这个问题？有什么办法可以提高反射的性能吗？
- 委托是什么？匿名方法是什么？在C# 3.0中，Lambda表达式是什么？扩展方法是什么？LINQ是什么？您觉得C# 3.0中还有哪些重要的特性，它们带来了什么优势？BCL中哪些类库和这些特性有关？您平时最常用哪些？
- 工作之外您看哪些技术相关的书、网站、社区、项目等等？您还接触哪些.NET以外的技术，能和.NET或.NET中有针对性的部分做个对比吗？；
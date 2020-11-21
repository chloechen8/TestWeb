---
layout: page
title: Java
---

This is Chinese version.[Reference Video] (https://www.bilibili.com/video/BV1Kb411W75N?p=48)
 
# Java 基础
<!-- GFM-TOC -->
* [Java 基础](#java-基础)
    * [一、语言概述](#语言概述)
        * [核心机制](#核心机制)
        * [JDK](JDK)
        * [注释](#注释)
        * [第一个Java程序分析](#第一个Java程序分析)
    * [二、基本语法](#基本语法)
        * [关键字和保留字](#关键字和保留字)
        * [标识符](#标识符)
        * [变量](#变量)
        * [运算符](#运算符)
        * [程序流程控制](#程序流程控制)

## 一、语言概述

### 核心机制

- Java虚拟机(JVM)： 能够保证Java程序在不同的平台运行；
- 垃圾回收；

垃圾回收：
在C++中，由程序员回收无用内存，所以需要进行内存是都泄露的检测；
在Java中，有系统进行垃圾回收；

### JDK
JDK = JRE + Java开发工具；
JRE = JVM + java类库；
JRE： Java Runtime environment;

### 注释
- 单行注释；
- 多行注释；
- 文档注释： 可以被javadoc解析，生成HTML文件；

### 第一个Java程序分析
1. Java程序编写-编译-运行的过程
编写：编写的Java代码保存在以"java"结尾的源文件中；
编译：使用javac.exe命令编译Java源代码；格式：javac 源文件.java;
运行：使用java.exe命令解释运行字节码文件。格式： java className;

2. class：
在一个Java源文件中可以什么多个class，但是最多只能有一个雷声明为public，而且要求声明为public的类名和源文件相同；

3. 程序入口：
程序的入口是main()方法。格式是固定的；

4. 输出语句：
System.out.println();先输出后换行；
System.out.print();只输出；

5. 编译的过程：
编译过后，会生成一个或多个字节码文件；
字节码文件的文件名和Java源文件中的类名相同；
有几个class就会有几个字节码文件。

## 二、基本语法
### 关键字和保留字
### 标识符
### 变量
### 运算符
### 程序流程控制
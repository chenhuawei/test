# 数据结构作业

开发工具 CLion

`sqlist/main.c`对应实验一

`linklist/main.c`对应实验二（暂未实现）



## 一、顺序表操作验证

### 1.实验目的
(1) 掌握线性表的顺序存储结构;

(2) 验证顺序表及其基本操作的实现;

(3) 掌握数据结构及算法的程序实现的基本方法。

### 2.实验内容
(1) 建立含有若干个元素的顺序表;

(2) 对已建立的顺序表实现插入、删除、查找等基本操作。

### 3.实现指导

(1) 实验类型: 验证实验。本实验主要是将学到的“线性表”这种数据结构上机实现，深化理解和掌握 理论知识，进一步认识线性表的顺序存储结构。本实验不需要自己设计，只需将给定的 方案实现即可。

(2) 预备知识: 线性表的基本定义、线性表的基本操作算法、线性表的顺序存储结构。

(3) 实现方法提示:
1) 定义顺序表的数据类型——顺序表类 SqList，包括题目要求的插入、删除、查找等基 本操作，为便于查看操作结果，请设计一个输出函数依次输出顺序表的元素;顺序表类 SqList 如下描述:
    ```
    Struct{
    ElemType *elem; //存储空间基址
    int length; //当前长度
    }SqList;
    ```
2) 建立含有 n 个数据元素的顺序表;
3) 对建立的顺序表设计插入、删除、查找等基本操作的算法。

### (4) 实验报告要求:
1) 实验上要写出多批测试数据的运行结果; 
2) 结合运行结果，对程序进行分析。

## 二、单链表操作验证


## 1.实验目的

(1) 掌握线性表的链式存储结构;

(2) 验证单链表及其基本操作的实现;

(3) 进一步掌握数据结构及算法的程序实现的基本方法。

## 2.实验内容

(1) 用头插法(或尾插法)建立带头结点的单链表;

(2) 对已建立的单链表实现插入、删除、查找等基本操作。

## 3.实验指导

(1) 实验类型: 验证实验。本实验主要是将学到的“线性表”这种数据结构上机实现，深化理解和掌握 理论知识，进一步认识线性表的链式存储结构。本实验不需要自己设计，只需将给定的 方案实现即可。

(2) 预备知识: 线性表的基本定义、线性表的基本操作算法、线性表的链式存储结构。

(3) 实现方法提示:

1) 将单链表中的结点定义为如下结构类型:
    ```
    Structure Node
    {
        ElemType data;
        Node *next;
    }
    ```
2) 定义单链表的数据类型——单链表类LinkList,包括所要求做的插入、删除、查找等 基本操作，为便于查看操作结果，设计一个输出函数依次输出单链表的元素;
3) 设计单链表类 LinkList 的构造函数和析构函数。构造函数用于建立单链表(用头
插法或尾插法)，析构函数用于释放单链表中的所有结点;
4) 对所建立的单链表设计插入、删除、查找等基本操作的算法;
5) 思考题:否为单链表的结点设计一个结点类，来实现单链表的基本操作?

### (4) 实验报告要求:
1) 要写出多批测试数据的运行结果; 
2) 结合运行结果，对程序进行分析。

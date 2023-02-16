[HashMap源码分析（jdk1.8，保证你能看懂） - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/79219960)

# 一、带着问题分析

1. HashMap的底层数据结构是什么？
2. HashMap中增删改查操作的底部实现原理是什么？
3. HashMap是如何实现扩容的？
4. HashMap是如何解决hash冲突的？
5. HashMap为什么是非线程安全的？

# 二、认识Hashmap

jdk 1.2 至 jdk 1.7 使用**数组+链表**结构
jdk 1.8 使用**数组+链表+[[红黑树]]**结构

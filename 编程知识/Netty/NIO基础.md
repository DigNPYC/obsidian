#网络 #通讯

>non-blocking io 非阻塞 io

# 三大组件

1. Channel & Buffer & Selector
	1. chanel：双向通道
	2. Buffer：缓存区
	3. Selector：（结合服务器演化过程理解）
		1. 传统多线程服务器：内存占用高、线程上下文切成本高 、只适用于连接数少的场景
		2. 线程池版服务器：阻塞模式下，线程仅能处理一个socket链接


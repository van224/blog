<br>

高效IO异步模型的设计

对支持"可扩展"的方向和方式

内存利用的设计

使用时要注意的几点
对资源的使用率也好，算法层面的逻辑优化也好，当流量高起来之后，
也许之前不太起眼的小优化此时起到的效果有是被乘N倍的放大。
ByteBuf的复用 release();
 
<br>

Netty的零拷贝机制是一种应用层的逻辑实现，和JVM以及操作系统并没有过多的关联。通过ByteBuf避免一些数组等数据的拷贝。


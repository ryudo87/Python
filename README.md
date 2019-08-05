# 全局解释器锁(Global Interceptor Lock)GIL

即在任意时刻，只有一个线程在解释器中运行。对Python 虚拟机的访问由全局解释器锁（GIL）来控制，正是这个锁能保证同一时刻只有一个线程在运行

如何避免受到GIL的影响

用多进程(multi-process)替代多线程(multi-thread):

该模块是什么：

1. 仿.NET Framework中的BackgroundWorker，帮助新手更容易的使用多线程
2. 简化多线程的创建和管理
3. **完成回调、进度回调都会在窗口线程中执行，可安全的操作窗口组件**
4. 同时支持延时任务、间隔执行任务，功能与时钟类似

该模块不是什么：

1. 不是线程池，可创建的任务数量有上限，最大允许60个任务
2. 不是IOCP等异步IO，不能用来创建网络连接池
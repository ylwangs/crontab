1、从etcd中把job同步到内存中
2、实现调度模块，基于cron表达式调度N个job
3、实现执行模块，并发执行多个job
4、对job的分布式锁，防止集群并发
5、把执行日志保存到MongoDB中
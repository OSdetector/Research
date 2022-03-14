# 内核相关资料
5.15 (LTS)



## 内核数据结构

eBPF bcc 读取内核数据结构 [ref](https://github.com/iovisor/bcc/blob/master/docs/reference_guide.md#data)

线程[task_struct](https://elixir.bootlin.com/linux/v5.15.28/source/include/linux/sched.h#L723)数据结构定义
其中的[nsproxy](https://elixir.bootlin.com/linux/v5.15.28/source/include/linux/sched.h#L1077)指明当前的namespace

[nsproxy](https://elixir.bootlin.com/linux/v5.15.28/source/include/linux/nsproxy.h#L31)数据结构定义
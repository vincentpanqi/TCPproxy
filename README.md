# 暂不可用
如果你不慎看到本项目(说的好像有人能看到一样，哈哈)，请知晓程序还有待完善，尚不能使用。

# 目的
关于socket编程，网上能找到大把大把的入门教程，基本上都是教你写一个echo server和client。但是很难找到相对中阶一点的教程，告诉你如何实现真正能用到现实中的程序。
求人不如求己，为了更进一步了解python的socket的编程，加之我有一个想从外网控制内网树莓派的需求，我写了一个tcp代理程序。目前基本功能已经完成，还需要再打磨一下。

# 大致实现思路
非阻塞socket + 系统I/O复用机制(利用selectors模块)

# 运行版本
因为用到selectors模块，所以至少需要Python3.4。我在3.5.2下开发和运行没问题

# 用法
待程序完善后补充
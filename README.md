rbtree
======

红黑树的C 实现，
删除部分参考了http://en.literateprograms.org 提供的红黑树的代码和文档，
插入部分参考了内核的实现。

将来需要改进的地方：
1 目前左旋右旋，很多情况的处理都是对称的，但是对称本质也是冗余的一种，希望将来有时间，用child[2] 把左旋右旋，各种镜像情况
统一到一个框架之内。因为删除部分我理解的不深刻，所以暂时没有动手。

2 在测试代码中加入了用生成dot文件，实现了可视化，方便调试。



# 一笔画寻路暴力搜索

试一下：[https://npcdw.github.io/Unicursal/](https://npcdw.github.io/Unicursal/)

算法实现比较简单，一个棋盘，从起始位置开始，理论上来说每一步都有四个方向可以走，排除掉墙壁、障碍物和已经走过的路线，如果还有方向可以走，那就向那个方向走。

如果走到了死胡同，并且还有格子没有走，退一步寻找没有走过的路线，如果所有的格子都走过了，说明寻路成功，如果所有方法都没办法一步走完，说明无路可寻。

![image](https://user-images.githubusercontent.com/32638459/147827269-d08af2ea-c85c-4acc-a1cf-b477a3094a48.png)

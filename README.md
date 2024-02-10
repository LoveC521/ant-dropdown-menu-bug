# Bug复现
当前vue版本号3.4.18

鼠标放在Hover me上菜单有概率闪烁。
![alt text](./image/image.png)
正常显示的类名如下
![alt text](./image/image2.png)
对比发现，bug发生时Menu组件的类名多了几个。

当切换vue版本为3.3.10时，bug消失.
```
pnpm update vue@3.3.10
```
当切换vue版本切换回3.4.15时，bug消失
```
pnpm update vue@3.4.18
```
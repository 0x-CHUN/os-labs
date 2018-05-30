Lab 1实验思路
===
1. 修改bootsect.s  
   改变字符串，如果长于改变前面的字符长度，要修改字符串不然显示不全
2. 修改setup.s
    * 地址给对（bootsect.s里面写的是BOOTSEG）
    * 通过中断取到数据，存储下来
    * 提示信息修改为XX loading 输出
    * 死循环

运行截图
===
![屏幕截图.png](屏幕截图.png)
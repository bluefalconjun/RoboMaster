# Lesson.1 Maze

----
Use cozmo program to get to the star. 
then get back.

原始迷宫:

![mazesmall.png](https://github.com/bluefalconjun/RoboMaster/blob/master/Pics/mazesmall.jpg)

lego示意图:

![cozmo.lesson.1.png](https://github.com/bluefalconjun/RoboMaster/blob/master/Pics/cozmo.lesson.1.png)


## 详细步骤:
1. 按照lego示意图, 从底板(48*48)上面, 自行搭建迷宫.
    ### 教学点: 需要Rex自己判断和计算, 中间的墙的位置的坐标, 包括考虑墙本身的宽度.
    ### 教学点: 迷宫墙体的稳定性, 需要自己处理. 包括可以加入门, 小人, 障碍物等.

2. 使用discover模式, 首先使用手控完成任务.
    ### 教学点: 手控分为直接看实物操作/cozmo视角操作, 区别对待.
 
4. 固定好cozmo出发/获取方块/返回的位置.
    ### 教学点: 在出发/方块/返回的位置使用方块做好标记, 程序的初始化条件/中间条件必须是固定的, 这样才能调整参数到每一次都是一样的结果.

4. 使用code lab模式, 逐步使用编程模式完成任务.
    ### 教学点: 编程模式, 可以一步步来, 分多次完成, 重点是理解顺序控制, 循环操作. 需要前面code.org的编程基础.

----
复杂迷宫

![maze.png](https://github.com/bluefalconjun/RoboMaster/blob/master/Pics/maze.jpg)
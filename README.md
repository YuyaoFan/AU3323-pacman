# AU3323-pacman
使用bfs, dfs, greedy search和A star search 寻找吃豆人的运动路径

# 作业说明
1、本次作业提供的文件中，你仅需要在 search.py 中编写 bfs、dfs、greedySearch、aStarSearch 四个算法的函数。在实现这些算法时，提供了一些可用的数据结构 Queue、Stack、 PriorityQueue，具体用法可参考 util.py 中关于这些数据结构的定义。(A*算法的 heuristic 默认为欧氏距离。)

2、为了检查 bfs、dfs、greedySearch、aStarSearch 这些算法的运行情况，请在pacman.py 中将 algorithm 字典（676 行）的 fn 的 value 改成对应的'bfs', 'dfs', 'greedy', 'astar'之一, 运行 pacman.py 即可看到效果。为了方便使用各种工具，建议详细阅读 searchAgents.py 文件中定义的 PositionSearchProblem 类，重点关注该类提供的函数。

3、提交内容:search.py 文件，一份文档(包含四个算法的运行结果截图即可)。

请仔细阅读注释部分对 problem 属性的说明。实现完成后，请删除函数中的 util.raiseNotDefined()语句，该语句的作用是在函数为空的时候抛出错误。

# 结果展示

## 1.BFS
![bfs pic](https://github.com/user-attachments/assets/2bcd595b-5d5f-4a0d-b316-c28b5e7e9fb5)

## 2.DFS
![dfs pic](https://github.com/user-attachments/assets/b4e68c51-bf00-4329-9b6c-adf058463f33)

## 3.greedy search
![greedy pic](https://github.com/user-attachments/assets/2242bc8e-c970-4714-b9c5-986f366131b7)

## 4.A star search
![astar pic](https://github.com/user-attachments/assets/f4c3783a-f5bc-4307-b5ef-d42af4c6b119)

note: 图中的得分是运动过程中的实时得分，并不是最终得分，最终得分请以实际运行结果为主。

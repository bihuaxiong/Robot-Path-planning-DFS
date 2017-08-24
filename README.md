# Robot-Path-planning-DFS
Robot path planning using depth-first-search algorithm

扫地机器人自动寻路实现（使用深优先搜索算法）

地图实例(Sample map of room)：<br/>
`@#*` <br/>
`*__` <br/>
`#*_` <br/>

It shows that in a room with 3 rows and 3 columns where * reprensents dirty cell, # represens obstacles, _ represents for empty cell and @ is the location of the cleaning robot.<br/>
该地图表示为在3×3的房间内，星号(*)代表脏东西的格子，井号（#）代表障碍物格子，下划线(_)代表空格子，@代表机器人所在位置。<br/>

程序输入实例(The example input for the sample map)<br/>
Please Enter Row Number:<br/>
3<br/>
Please Enter Colomn Number:<br/>
3<br/>
Please Enter the Elements in row 1:<br/>
`@#*`<br/>
Please Enter the Elements in row 2:<br/>
`*__`<br/>
Please Enter the Elements in row 3:<br/>
`#*_`<br/>
S<br/>
C<br/>
E<br/>
S<br/>
C<br/>
N<br/>
E<br/>
N<br/>
C<br/>
<br/>
14<br/>

字母表示机器人走的路径。N表示向上，S表示向下，W表示向左，E表示向右。数字表示算法遍历过的节点数量。<br/>
The letters (N, S, W and E) represents the direction of each step the robot walked. The number represens the number of nodes which have been traversed.

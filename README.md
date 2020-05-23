# Game 2048
### 游戏规则  
你需要控制所有方块向同一个方向运动，两个相同数字方块撞在一起之后合并成为他们的和，每次操作之后会在空白区域（按3:1的几率）随机生成一个2或者4，最终得到一个“2048”的方块就算胜利了。  
WSAD键控制上下左右滑动，R可重置本次游戏，Q退出游戏。  
  
### 可能的注意事项  
其中的游戏界面绘制用到了curses库，由于Python自带的官方curses库不支持windows，在windows环境下运行需使用非官方的curses库来代替。  
[curses下载]（http://www.lfd.uci.edu/~gohlke/pythonlibs/）

# sudoku
数独是源自18世纪瑞士的一种数学游戏。是一种运用纸、笔进行演算的逻辑游戏。玩家需要根据9×9盘面上的已知数字，推理出所有剩余空格的数字，并满足每一行、每一列、每一个粗线宫（3*3）内的数字均含1-9，不重复。

数独盘面是个九宫，每一宫又分为九个小格。在这八十一格中给出一定的已知数字和解题条件，利用逻辑和推理，在其他的空格上填入1-9的数字。使1-9每个数字在每一行、每一列和每一宫中都只出现一次，所以又称“九宫格”。

用户执行程序，输入数字，然后默认输出相应的数独txt文件。

##项目需求
•	利用程序随机构造出N个已解答的数独棋盘 。
•	输入
•	数独棋盘题目个数N（0<N<=1000000）
•	输出
•	随机生成N个不重复的已解答完毕的数独棋盘，并输出到sudoku.txt中，输出格式见下输出示例。

	输入示例
3
	输出示例（输出文件示例戳我）
2 6 8 4 7 3 9 5 1
3 4 1 9 6 5 2 7 8
7 9 5 8 1 2 3 6 4
5 7 4 6 2 1 8 3 9
1 3 9 5 4 8 6 2 7
8 2 6 3 9 7 4 1 5
9 1 7 2 8 6 5 4 3
6 8 3 1 5 4 7 9 2
4 5 2 7 3 9 1 8 6

4 5 1 7 8 2 3 6 9
7 8 6 4 9 3 5 2 1
3 9 2 1 5 6 4 8 7
5 2 7 6 4 9 8 1 3
9 6 8 5 3 1 2 7 4
1 3 4 2 7 8 6 9 5
8 1 5 3 6 7 9 4 2
6 7 3 9 2 4 1 5 8
2 4 9 8 1 5 7 3 6

9 5 8 3 6 7 1 2 4
2 3 7 4 5 1 9 6 8
1 4 6 9 2 8 3 5 7
6 1 2 8 7 4 5 9 3
5 7 3 6 1 9 4 8 2
4 8 9 2 3 5 6 7 1
7 2 4 5 9 3 8 1 6
8 9 1 7 4 6 2 3 5
3 6 5 1 8 2 7 4 9


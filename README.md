# pygame_4d_tic_tac_toe

## Game Play

游戏在3*3的9个井字棋的棋盘上进行。\
第一手默认在[1, 1]处的井字棋的棋盘上落子。\
落子的位置决定了下一次落子的棋盘。\
例如：当玩家在棋盘上的[2, 2]处落子后，则下一手必须在[2, 2]处的棋盘上落子，除非出现例外。\
当某个棋盘上达成3连时，该棋盘被封锁并由3连的玩家持有。\
当一个棋盘9个格子被摆满而没有3连出现时，棋盘也会被封锁，并由最后落子的玩家持有。\
例外：当下一回合落子的位置是被封锁的棋盘时，下一回合的落子不再有棋盘限制。\
被封锁的棋盘不允许再落子。\
胜利的条件是持有的棋盘达成3连的玩家获胜。

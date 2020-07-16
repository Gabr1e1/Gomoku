# 交互方式

## 需要你写的代码
1. 完成两个函数`init`和`action`

`init`: 初始化函数，会在程序开始的时候被调用

`action(loc)`: `loc`参数为对手采取的行动，需要返回你在这步落子的位置

如果是第3步，返回`(-1,-1)`表示交换颜色，返回坐标表示不选择换手，正常下棋

2. `ai_side`变量表示你的AI是哪一边，0黑1白，`ai_name`可以随便填写（

3. `AIController.h`不需要修改，提交也仅需要提交`yourcode.cpp`

可以参考`sample.cpp`的实现

## 本地评测

python3, 需要的包有`subprocess`, `timeout_decorator`, `numpy`, `sys`, `time`

运行方式：`python3 judge.py ai0path/human ai1path/human`

写在前面的表示先手，后面的表示后手

例如：`python3 judge.py ./sample human`

可以通过更改judge.py来输出更多信息

Note: 人机下的时候最好注释掉`judge.py`33, 42行

# 参考资料
## 算法
1. 基础教程：https://github.com/lihongxun945/myblog/issues/11
2. MCTS
   1. https://www.analyticsvidhya.com/blog/2019/01/monte-carlo-tree-search-introduction-algorithm-deepmind-alphago/
   2. https://www.geeksforgeeks.org/ml-monte-carlo-tree-search-mcts/

## 前端

1. Basic HTML: W3Schools https://www.w3schools.com/html
2. Use Framework if needed
   1. Javascript Framework: Angular, React, Vue
   2. Web app Framework: Flask, Tornado
   3. UI Framework


# HIT_AI_Lab
## 哈尔滨工业大学计算机学院人工智能实验
**人工智能实验共有两个：**
### √ 知识表示之猴子摘香蕉问题
```
**√ 实验内容：**
参照课程第二部分讲授的知识表示方法完成，包括产生式系统、框架系统、语义网络等（还可以选择其他方法）解决以下问题（不限于此），必要时上网查找有关参考文献。最好事先编好源代码，然后再调试运行。
**√ 实验问题 **
一个房间里，天花板上挂有一串香蕉，有一只猴子可在房间里任意活动（到处走动，推移箱子，攀登箱子等）。设房间里还有一只可被猴子移动的箱子，且猴子登上箱子时才能摘到香蕉，问猴子在某一状态下（设猴子位置为A，箱子位置为B，香蕉位置在C），如何行动可摘取到香蕉。
```
### √ 搜索策略之吃豆人游戏
```
**√ 实验内容：**
实验要求采用且不限于课程第四章内各种搜索算法此编写一系列吃豆人程序解决以下列出的问题1-8，包括到达指定位置以及有效的吃豆等。
**√ 实验简介 **
参考网址：http://ai.berkeley.edu/search.html内容，以下为实验简介。
基本代码和支持文件可以从search.zip中获取。其中，一些需要参考的文件如下：
√ 需要编辑的文件：search.py和searchAgents.py
√ 需要参考的文件：
  pacman.py	吃豆人游戏的程序。 文件包括一个描述”吃豆人”gamestate的类型。
  game.py	吃豆人游戏的运行逻辑. 文件包括以下类型AgentState, Agent, Direction, and Grid.
  util.py	搜索策略可以用到的数据结构.
√ 可以忽略的支持性文件：graphicsDisplay.py graphicsUtils.py textDisplay.py ghostAgents.py keyboardAgents.py                layout.pyautograder.py	testParser.py testClasses.py test_cases/ searchTestClasses.py
√ 解压缩search.zip，在此目录下，运行以下指令可打开吃豆人游戏。
   python pacman.py
√ 运行python autograder.py可以帮助你对自己的程序打分。
√ searchAgents.py中最简单的Agent叫做GoWestAgent，一路向西，偶尔能实现目标：
   python pacman.py --layout testMaze --pacman GoWestAgent
   但是其不能实现转弯：
   python pacman.py --layout tinyMaze --pacman GoWestAgent
如果程序卡死，可通过CTRL-c来终止。
√ 此项目中用到的指令也都储存在commands.txt文件中，可用于复制和粘贴。
```
### 注意(Attention)
```
以上资料仅供参考，切勿照搬！！！
```
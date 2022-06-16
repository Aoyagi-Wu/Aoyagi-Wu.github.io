# 一点点笔记
## hello, symbol table 

_看完了GeeksforGeeks关于symbol table的解释以后决定记录一下_
_夹杂各种蹩脚英语，因为不知道怎么翻_

symbol table是用来追踪semantics of variables的，由compiler创建并保持的一个data structure。
symbol table会储存关于名称的范围和绑定的信息，各种实体（例如变量，方程名，类和对象）的实例信息。
symbol table的特点：
1. 是内建的词汇&语法分析器（analysis phases）
2. 信息会被analysis phases收集，并被synthesis phases用来生成code
3. symbol table被compiler用来实现高效的compile time
4. symbol table被多个compiler的phases使用

累了

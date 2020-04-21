刷交易问题思考：

power计算公式由：power = TxCount 调整为power = TxCount + Height，是否可解决隐藏算力打击问题？

加入一个区块的交易数最多为k笔，则：

Pmin = height, Pmax = k * height +height = (k+1) * height，即：

Pmax / Pmin = k+1

或者数学上lim (kx+b)/(x+b)

交易刷了不用，将会随着高度增长减小其影响。
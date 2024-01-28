MACD是一个可以测试价格动能的一个指标。MACD总共有两条线，一条是快线，一条是慢线，以及一个0轴。

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240128110245178.png" alt="image-20240128110245178" style="zoom:50%;" />

当两条线在0轴上方就是上升趋势。

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240128110355453.png" alt="image-20240128110355453" style="zoom:50%;" />

当两条线在0轴下方就是下跌趋势。

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240128110441089.png" alt="image-20240128110441089" style="zoom:50%;" />

## MACD

MACD衡量的是价格运行的边际变化，MACD往往被看作是衡量价格运行的动能的重要指标。

+ 当一种上行或者下行的趋势已经确立并且不断强化的时候，EMA12和EMA26之间的距离就会在正向或者负向上逐渐拉大。

  <img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101150943623.png" alt="image-20240101150943623" style="zoom:50%;" />

+ 当一种上行或者下行的趋势已经确立并且不断弱化的时候，EMA12和EMA26之间的距离就会在正向或者负向上逐渐缩小。

  <img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101151041217.png" alt="image-20240101151041217" style="zoom:50%;" />

EMA12均线和EMA26均线的差值为差离值(差离值 = EMA12 - EMA26)。由差离值构成的曲线就是MACD线。

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20231228203449077.png" alt="image-20231228203449077" style="zoom:50%;" />

因为差离值在一个方向上增长的时候代表一种趋势的强化，

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101151758610.png" alt="image-20240101151758610" style="zoom:50%;" />

在一个方向上缩减的时候代表一种趋势的弱化或者可能的趋势反转，

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101151853965.png" alt="image-20240101151853965" style="zoom:50%;" />

所以又给差离值本身配置了一条9日指数移动均线DEA，DEA又叫信号线(信号线 = 差离值的EMA9)。注意：信号线是差离值的EMA9，不是价格的EMA9。

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101153232515.png" alt="image-20240101153232515" style="zoom:50%;" />

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101153408204.png" alt="image-20240101153408204" style="zoom:50%;" />

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101153615638.png" alt="image-20240101153615638" style="zoom:50%;" />

零轴上方 = 上涨阶段。零轴下方 = 下跌阶段。

差离值为正值，MACD线运行在0轴上方，此时EMA12运行在EMA26上方。差离值为负值，MACD线运行在0轴之下。红绿柱表示两者之间差值的实际值的2倍。差值在0轴附近表示在横盘震荡。

+ 当一种颜色的红绿柱的长度在不断增大的时候，说明差离值向上或者向下运行的速度要大于其9日EMA（信号线）运行的速度，价格当前运行的趋势在不断强化（上涨/下跌）。

+ 当一种颜色的红绿柱的长度在不断缩小的时候，说明差离值向上或者向下运行的速度要小于其9日EMA（信号线）运行的速度，价格当前运行的趋势在不断减弱（上涨/下跌），需要特别注意趋势可能发生反转。

  当MACD线和信号线交叉来确认一种趋势已经发生了根本性的反转。当MACD线和信号线交叉时，首先红绿柱的颜色会互换，MACD线向上穿过信号线通常被认为是一种较强的看涨信号，趋势由跌转涨。

  <img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101154655299.png" alt="image-20240101154655299" style="zoom:50%;" />

  MACD线向下穿过信号线则代表趋势由涨转跌，是一种较强的看跌信号。

  <img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101154842763.png" alt="image-20240101154842763" style="zoom:50%;" />

  死叉信号会失效的原因：

  + 基本面过于强劲，死叉只是短暂的调整。

  + MACD线依然在零轴的上方，技术面未进入下行通道。

    <img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101155204117.png" alt="image-20240101155204117" style="zoom:50%;" />

    <img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101155318879.png" alt="image-20240101155318879" style="zoom:50%;" />

    同样的，下跌过程中发生在零轴下方的金叉有时候也可能只代表着下跌趋势中的短暂反弹调整。

    <img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101155539279.png" alt="image-20240101155539279" style="zoom:50%;" />

    如果想要比较靠谱的确认一段趋势的反转，零轴下方的金叉可以等到MACD线运行到零轴上方再考虑买入。

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101155959618.png" alt="image-20240101155959618" style="zoom:50%;" />

零轴上方的死叉，可以等到MACD线运行到零轴下方再考虑卖出。

<img src="/Users/zhangxuan/Library/Application Support/typora-user-images/image-20240101160334824.png" alt="image-20240101160334824" style="zoom:50%;" />




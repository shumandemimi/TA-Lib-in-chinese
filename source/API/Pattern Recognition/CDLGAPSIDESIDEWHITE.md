
# CDLGAPSIDESIDEWHITE

# 指标概述

中文名称：向上/下跳空并列阳线。

用法：向上/下跳空并列阳线本身不直接看涨或看跌。如果出现在趋势中，则是非常显著的看涨或看跌信号。但本函数并不包含趋势判断。

调用方法：talib.CDLGAPSIDESIDEWHITE(open, high, low, close)

输出：向上跳空输出100，向下跳空输出-100，不符合形态输出0.

# 指标介绍

首先要向上/下跳空，实体间有缺口。

跳空后第一根k线：阳线。

跳空后第二根k线：阳线，长度和开盘价均与第一根k线相仿。且其不能填充跳空的缺口。


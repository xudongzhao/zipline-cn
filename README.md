# zipline-cn
zipline量化交易平台的一些中国本地化修改。

Some modifications to zipline for chinese market.



## 设计原则

1. 为最新版的zipline做修改 （目前是1.3.0）。
2. 尽量少的修改zipline的源代码。







## 项目目录与文件结构

- **zipline-cn**    主项目目录
  - *benchmarks.py*

- **dev**    开发目录

- **test**    测试目录

  



## 修改benchmarks.py，通过网易获取指数的数据。	

benchmarks.py 位于 zipline安装目录下的 data目录中。

原文件使用的是iextrading的SPY在线数据。现在改为通过网易获取数据。










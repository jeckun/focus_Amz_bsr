# Focus Amazone BSR Top 100

这个项目是为了方便亚马逊卖家追踪BSR Top 100名单的。目标是周期性采集指定子类目的Top 100 商品数据。并且保存到数据库，用于后续的数据分析。

## 前提：
由于部分数据采用了卖家精灵，这是一个中国公司做的针对亚马逊的插件，并且他是收费的。如果你没有安装这个插件，那么这个项目将只能采集到有限的数据。

## 用法：
直接在命令行执行下列代码即可
``` $ python main.py```

示例：
1. 编辑 config.ini

```
[Parameters]
ZIP = 90001
HOMEPAGE = https://www.amazon.com
BSR = Tumblers & Water Glasses
BSR_URL = kitchen/13218451/ref=pd_zg_hrsr_kitchen
```

2. 命令行执行

``` $ python main.py```

## 特点：
1. 指定 ZIP 可模拟不同地区消费者看到的 BSR 排名，因为亚马逊销售的商品排名跟地区紧密相关，所以可能出现不同地区看到的 BSR 排名是不同的。
2. 指定 BSR URL 路径，即可采集指定 BSR 排名的所有 Top 100 商品， 自动采集信息，自动翻页。
3. 采集的数据保存到Excel，可随时查看。也可保存到数据库，用于后续数据分析。

## 目标：
这是一个个人项目，如果您也对此感兴趣，欢迎加入我一起来完善他，实现更加丰富的自动化功能。最终目标是对接Ai，实现自动采集，智能分析，智能决策。实现自动化亚马逊运营。

## 许可证：

## 联系方式：

## 链接：无

## 更新日志：
*** 2024-4-20 *** 完成基础数据自动采集，并保存为Excel

*** 2024-4-23 *** 实现批量导入Excel到mysql

*** 2024-4-25 *** 实现对多个ASIN的子类BSR变化折线图

## 致谢：感谢贡献者和其他支持您项目的人。

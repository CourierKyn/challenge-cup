# 基于深度学习的基金投资组合智能投顾

### [`挑战杯项目规划.pdf`](https://github.com/CourierKyn/challenge-cup/raw/master/挑战杯项目规划.pdf)

### [`第一周计划简述.docx`](https://github.com/CourierKyn/challenge-cup/blob/master/other/第一周计划简述.docx)

## JQData 数据

#### [安装 JQData](https://github.com/CourierKyn/challenge-cup/blob/master/其他说明.md#安装-jqdata)

#### [JQData 证券代码标准格式](https://github.com/CourierKyn/challenge-cup/blob/master/其他说明.md#jqdata-证券代码标准格式)

#### 所有基金累计净值

```python
pd.read_hdf('fund_value_df.h5')
```

[`fund_value_df.h5`](https://github.com/CourierKyn/challenge-cup/raw/master/fund_value_df.h5)：所有基金自上市以来每个交易日的累计净值。

#### [获取单个基金信息](https://www.joinquant.com/help/api/help?name=JQData#get_security_info-获取单个标的信息)

#### 可视化

- [`所有基金列表.csv`](https://github.com/CourierKyn/challenge-cup/blob/master/所有基金列表.csv)

- [`基金累计净值示例.csv`](https://github.com/CourierKyn/challenge-cup/blob/master/基金累计净值示例.csv)

#### [关于所有基金列表](https://github.com/CourierKyn/challenge-cup/blob/master/其他说明.md#关于所有基金列表)

## Next

* 制定根据用户要求选出基金组合的方法
* 从用户角度进一步设计产品使用逻辑
* …

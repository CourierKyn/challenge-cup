# 基于深度学习的基金投资组合智能投顾

## JQData 数据

#### JQData 证券代码标准格式

由于同一代码可能代表不同的交易品种，JQData 给每个交易品种后面都添加了该市场特定的代码后缀，如 `security='600519.XSHG'`。可从基金列表中得到。

#### 所有基金累计净值

```python
pd.read_hdf('fund_value_df.h5')
```

[fund_value_df.h5](https://github.com/CourierKyn/challenge-cup/blob/master/fund_value_df.h5)：基金在一段时间的每个交易日的累计净值。

#### 获取单个基金信息

详见 [获取单个标的信息](https://www.joinquant.com/help/api/help?name=JQData#get_security_info-获取单个标的信息)

#### 可视化

- [所有基金列表.csv](https://github.com/CourierKyn/challenge-cup/blob/master/所有基金列表.csv)

- [基金累计净值示例.csv](https://github.com/CourierKyn/challenge-cup/blob/master/基金累计净值示例.csv)

## Next

* 制定根据用户要求选出基金组合的方法
* 从用户角度进一步设计产品使用逻辑
* …

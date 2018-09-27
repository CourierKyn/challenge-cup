# 基于深度学习的基金投资组合智能投顾

## 可用资源

JQData：2005 年至今的基金等基础金融数据，每日可访问 100 万条。

### JQData 证券代码标准格式

由于同一代码可能代表不同的交易品种，JQData 给每个交易品种后面都添加了该市场特定的代码后缀，如 `security='600519.XSHG'`。可从基金列表中得到。

### 获取所有基金列表

```python
get_all_securities(types=['fund'])
```

详见 [获取所有标的信息](https://www.joinquant.com/help/api/help?name=JQData#get_all_securities-获取所有标的信息)

### 获取基金累计净值

```python
get_extras('acc_net_value', security_list, start_date, end_date)
```

得到基金在一段时间的每个交易日的累计净值。详见 [获取基金净值期货结算价等](https://www.joinquant.com/help/api/help?name=JQData#get_extras-获取基金净值期货结算价等)

## Next

* 寻找累计净值数据与基金未来表现的相关性
* 制定根据用户要求选出基金组合的方法
* 从用户角度进一步设计产品使用逻辑
* …

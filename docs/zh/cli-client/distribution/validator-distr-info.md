# iriscli distribution validator-distr-info

## 介绍

查询验证人的收益分配信息

## 用法

```
iriscli distribution validator-distr-info [flags]
```

打印帮助信息:

```
iriscli distribution validator-distr-info --help
```

## 示例

```
iriscli distribution validator-distr-info <validator address>
```
执行结果示例
```json
[
  {
    "delegator_addr": "iaa1ezzh0humhy3329xg4avhcjtay985nll06lgq50",
    "val_operator_addr": "iva14a70gzu0v2w8dlfx462c9sldvja24qazzr2ds4",
    "del_pool_withdrawal_height": "10859"
  },
  {
    "delegator_addr": "iaa1ezzh0humhy3329xg4avhcjtay985nll06lgq50",
    "val_operator_addr": "iva1ezzh0humhy3329xg4avhcjtay985nll00wz0fg",
    "del_pool_withdrawal_height": "4044"
  }
]
```
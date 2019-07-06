# AlphaGooo-mysql


- [导入导出数据](files/导入导出数据.md) - 往Mysql导入数据、从Mysql导出数据，是怎么做的



## 时间戳转换日期

1.时间戳 -> 日期
```
FROM_UNIXTIME(1156219870);
```

2.日期 -> 时间戳
```
UNIX_TIMESTAMP('2017-05-29 12:00:00');
```


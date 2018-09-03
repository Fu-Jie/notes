# statistics_notes

## 截尾平均数

将一组数据中部分异常值去点之后计算平均数通常是根据百分比来去除。

```matla
trimmean(data,precent,flag)
```
### flag作用是当出现截取百分比的个数不是整数的时候，使用的方法。有`round`,`floor`,`weighted`.

# Readme

## 统计高峰段

#### 不看路段即总体时段分析

仅仅统计时段：打车的时间点所在的区间，注意最后的结果要除上区间的长度

| 时间段                                            | 对应index |
| ------------------------------------------------- | --------- |
| 7:00-10:00（3h）                                  | 1         |
| 10:00-17:00（7h）                                 | 2         |
| 17:00-23:00 (6h)/17:00-20:00 (3h)/17:00-21:00(4h) | 3         |
| 22:00-7:00 (9h)                                   | 4         |



- 通过不同的区间划分来看：17:00-20:00 (3h)



<img src="/Users/xunyijiang/Library/Application Support/typora-user-images/image-20221116102723937.png" alt="image-20221116102723937" style="zoom:50%;" />

693956/3 = 231318.66666666666

918176/7 = 131168.0

1851884/3 = 617294.6666666666

1518058/9 =168673.11111111112



- 17:00-21:00(4h)

  <img src="/Users/xunyijiang/Library/Application Support/typora-user-images/image-20221116104355470.png" alt="image-20221116104355470" style="zoom:50%;" />



- 17:00-23:00



#### 看路段以及每个is_weekend & time_interval

![image-20221116113216474](/Users/xunyijiang/Library/Application Support/typora-user-images/image-20221116113216474.png)



## 关于pyspark 的存储

[栈溢出](https://blog.csdn.net/qq_32023541/article/details/79282179)





## 参考

[数据分析及可视化](https://toddwschneider.com/posts/analyzing-1-1-billion-nyc-taxi-and-uber-trips-with-a-vengeance/#data-privacy-concerns)




# Top10Rating_HaDoop
选出每个用户 评分最高的10部电影
RateBean 封装的Json对象 movie,rate,timeSatmp,uid 并且重写 compareTo方法
Map() 读入每条数据,输出的<K,V>为<用户的ID,RateBean对象>
Reduce() 输出每组的10条数据
shuffle过程中,先分区,在分组

58同城北京地区爬取了3w6k多条数据，进行数据清洗和数据分析后进行可视化
==============


结果展示
-------
![Image text](https://github.com/naginoasukara/data-visualization/blob/master/58/images/demo1.png)

![Image text](https://github.com/naginoasukara/data-visualization/blob/master/58/images/demo2.png)

爬取数据展示
-------


图片为mongoDB的可视化工具robomongo  显示3w6千条爬取数据

![Image text](https://github.com/naginoasukara/data-visualization/blob/master/58/images/2.png)

图片为一个count.py的运行结果  每五秒监视一次爬取结果

![Image text](https://github.com/naginoasukara/data-visualization/blob/master/58/images/1.png)

爬虫需要解决高频率访问问题，和效率问题的平衡，使用线程池，和IP池防止封IP。
并且解决58同城不同页面的解析。商品展示的页面可能会有好多种，如何处理。


数据清洗过程
-------

使用jupyter notebook (python的web版的IDE) 
可以更直观的观看数据做一些处理

讲有问题的数据或者不是很清楚的数据，改成自己想要的格式

![Image text](https://github.com/naginoasukara/data-visualization/blob/master/58/images/3.png)

![Image text](https://github.com/naginoasukara/data-visualization/blob/master/58/images/4.png)

![Image text](https://github.com/naginoasukara/data-visualization/blob/master/58/images/5.png)

![Image text](https://github.com/naginoasukara/data-visualization/blob/master/58/images/6.png)

![Image text](https://github.com/naginoasukara/data-visualization/blob/master/58/images/7.png)

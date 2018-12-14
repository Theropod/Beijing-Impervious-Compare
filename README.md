# Beijing-Impervious-Compare
4 geotiff representing the impervious surface of Beijing (30m)

![image](https://github.com/Theropod/Beijing-Impervious-Compare/blob/master/Comparison.gif)

- ## 1是建成区，其他是0
- ## urban_beijing_classified
    
    Beijing City Lab自己做的2015年30m城市制图 用GEE
    https://www.beijingcitylab.com/data-released-1/
- ## 2013年from-glc
    
    Beijing City Lab下载拼接提取的2013年的from-glc建成区，本地再把北京区域裁剪出来
- ## 2015年from-glc
    
    from-glc官网上下载的2015v1，本地拼接后再把北京区域裁剪出来。这一年的不知道为什么建成区提的很范围很大，城市里的湖泊一类的都挤小了，impervious连成一片
- ## 2017年from-glc
    
    from-glc官网上下载的2017v1，在110E50N这一景的最下面（也就是40N纬线）上有一个条带的缺失，值为0，不知道为什么。这个缺失我是用from-glc 2013给补上

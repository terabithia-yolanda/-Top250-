# -豆瓣电影Top250-
基于Python3对豆瓣电影Top250爬取，获得电影链接，海报，名称，评分等其他信息，并将数据以excel和sqlite3数据库形式存储；
总体分为几个步骤：
1.获取url，爬取每页电影信息；
2.根据url变化规律获取所有页面信息，并使用正则表达式将需求信息提取；
3.保存数据。

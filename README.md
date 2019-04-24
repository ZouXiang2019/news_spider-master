# news_spider-master
	spider crawl in qq.news 163.news	
	start environment:windows10,python3.6,scrapy
	step:
1.Creat scrapy project:scrapy startproject XXX
2.Copy the files into new project
3.Turn to XXX file and cmd:scrapy crawl start.py
	
	Some instructions:
demo/: 该项目的python模块。之后您将在此加入代码。 
demo/items.py: 项目中的item文件. Item 是保存爬取到的数据的容器
demo/pipelines.py: 项目中的pipelines文件. 编写存储文件Pipelines将数据保存到txt文件中
demo/settings.py: 项目的设置文件. 
demo/spiders/: 放置spider代码的目录.编写爬写网站的Spider

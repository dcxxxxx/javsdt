# JAV-Scraper-and-Rename-local-files
收集jav元数据，并规范本地文件（夹）的格式，为emby、kodi、jellyfin收集女优头像。  
python3.7  使用pyinstaller打包成exe。

[点击下载exe](https://github-production-release-asset-2e65be.s3.amazonaws.com/199952692/2b7ae780-1cfd-11ea-9d4f-425a9fba71be?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20191212%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20191212T083649Z&X-Amz-Expires=300&X-Amz-Signature=aa420f9999881d4eb96e605d5a3dd3a81dc731dfb82b6857bdfecf901e5bd70a&X-Amz-SignedHeaders=host&actor_id=44168897&response-content-disposition=attachment%3B%20filename%3DV1.9.8%2B.JAVSDT.zip&response-content-type=application%2Foctet-stream)
  或者[从蓝奏云下载](https://www.lanzous.com/i7z0r1a)

[点击下载emby和kodi女优头像](https://github-production-release-asset-2e65be.s3.amazonaws.com/199952692/40b54680-12f9-11ea-94e9-4e37ce4bec6e?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20191211%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20191211T200343Z&X-Amz-Expires=300&X-Amz-Signature=37b11e998a4d042857a17ea30bcdaed589af8e90f1ab0c3f9030c01f9e3c1e2f&X-Amz-SignedHeaders=host&actor_id=44168897&response-content-disposition=attachment%3B%20filename%3Dactors.zip&response-content-type=application%2Foctet-stream)  
  [点击下载jellyfin女优头像](https://github-production-release-asset-2e65be.s3.amazonaws.com/199952692/abfe6180-15f4-11ea-9c0b-cf86d9dc383b?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20191211%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20191211T200358Z&X-Amz-Expires=300&X-Amz-Signature=661316cb24696cf175103ad6c20d6db89f1820aa1af3bec31c053ac8d25f836d&X-Amz-SignedHeaders=host&actor_id=44168897&response-content-disposition=attachment%3B%20filename%3DPeople.zip&response-content-type=application%2Foctet-stream)  
如果链接失效，请进入[“release”](https://github.com/junerain123/JAV-Scraper-and-Rename-local-files/releases)下载。  

[没人的电报群](https://t.me/javsdtool)  
<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=79a735ccf11ed7f15481ae02f6a58f16315b8b424149455b4dc65868362f4b30">没人的企鹅群</a>  



工作流程：  
1、用户选择文件夹，遍历路径下的所有文件。  
2、文件是jav，取车牌号，到javXXX网站搜索影片找到对应网页。  
3、获取网页源码找出“标题”“导演”“发行日期”等信息和DVD封面url。  
4、重命名影片文件。 
5、重命名文件夹或建立独立文件夹。
6、保存信息写入nfo。  
7、下载封面url作fanart.jpg，裁剪右半边作poster.jpg。  
8、移动文件夹，完成归类。  

目标效果：  
![image](https://github.com/junerain123/Collect-Info-and-Fanart-for-JAV-/blob/master/images/1.png)  
![image](https://github.com/junerain123/Collect-Info-and-Fanart-for-JAV-/blob/master/images/2.png)  
![image](https://github.com/junerain123/Collect-Info-and-Fanart-for-JAV-/blob/master/images/3.jpg)  

以下为ini中的用户设置：  
  
![image](https://github.com/junerain123/JAV-Scraper-and-Rename-local-files/blob/1.9.8%2B/images/6.PNG)  

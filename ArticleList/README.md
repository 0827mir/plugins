### 随机/热门文章列表插件ArticleList v1.1.1

可指定分类并设置列表文章数目，其中随机列表支持自定义缓存。

 > 修正php5.6+报错问题，加入热评收录时限代码(注释)。

#### 使用说明
1. 将ArticleList.php文件直接上传至`/usr/plugins/`目录(:warning:不需要文件夹)；
2. 登陆后台，在“插件管理”中启用并进行设置；
3. 在模版中写入`<?php ArticleList::random(); ?>`输出随机文章列表，`<?php ArticleList::hot(); ?>`输出热门文章列表。

###### 更多详见作者博客：http://defe.me/prg/395.html
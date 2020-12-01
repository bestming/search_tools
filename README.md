# search_tools
根据搜索引擎的搜索规则，写了个前端页面，避免老是输入搜索规则



##### 搜索技巧：
①排除关键词(减号+关键词) 比如说：搜锤子而不是锤子手机，即为-手机

②精确搜索(给关键词加引号) 比如说：想搜小苹果，而不想是苹果，就“小苹果”

③指定网站内搜索(site：域名 关键词) 比如说在知乎里搜关于小苹果的内容，即为：site：zhihu.com 小苹果 这个方法用于一些搜索引擎特别垃圾的资料网站 比如说中国裁判文书网

④指定文件格式(filetype：文件格式 关键词) 比如说filetype：pdf 张文显《法理学》 包括doc，ppt，avi等格式

⑤指定标题搜索(intitle：关键词) 搜索的内容必须出现在标题里 比如说：intitle：小苹果 那搜索出来的网页标题就都包括小苹果 不然就会出现一些内容才会出现小苹果的网页 信息检索就很费劲

⑥intext:是指如果输入intext：小苹果,那搜索出来的文章里面就必须有小苹果的内容

⑦allintext: 是指搜索出来的内容必须有包括 小苹果 大苹果 红苹果 所有的内容

⑧结果包含某个url

##### 注意事项：1.所有的冒号都是半角，也就是英文的冒号，而不是中文的冒号 2.空格很重要，关键词之间要有空格 3.提取关键词很重要(可以提高搜索效率）
工具在线使用：
- [bestming.gitee.io/search_tools](https://bestming.gitee.io/search_tools)
- [bestming.github.io/search_tools](https://bestming.github.io/search_tools)

项目源码：[search_tools](https://github.com/bestming/search_tools)

code by [GitHub@韦相铭](https://github.com/bestming),有问题，欢迎提交issues

灵感来源： [bilibili@蜡笔和小勋](https://www.bilibili.com/video/BV1YK4y1t7bg?t=437)


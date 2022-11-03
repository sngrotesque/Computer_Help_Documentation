# 针对搜索引擎的高级搜索方法

> Baidu，Google等主流搜索引擎均支持高级搜索。

### 寻找子域名
```text
site: 域名

如需寻找bilibili.com这个域名的所有子域名，可以使用此语句来实现
具体实现方法为
    site: bilibili.com

可以在结果中看到有如下的子域名
    www.bilibili.com
    space.bilibili.com
    search.bilibili.com
    等等...
```

### 精准搜索
```text
在搜索某关键词的基础上将想要精准搜索的内容放入双引号中""
支持多个内容

如想寻找bilibili的某个番剧可以使用此语句来实现
具体实现方法为
    哔哩哔哩 "莉可莉丝"
```

### 排除型搜索
```text
在搜索某关键词的基础上使用横杠来排除掉不要看到的结果

如想搜索bilibili，但是不想看到大部分无关内容可使用此语句来实现
具体实现方法为
    哔哩哔哩 -知乎 -百科 -豆瓣 -应用
```

### 标题型搜索
```text
通过匹配标题来精确查找某个内容

如想搜索哔哩哔哩UP主罗翔的视频或主页可以使用此语句来实现
具体实现方法为
    intitle:哔哩哔哩 intitle:罗翔
```

### 目录文件型搜索
```text
inurl:内容
```
如你想搜索哔哩哔哩的某个UP主的UID进入主页你可以使用以下语句
```text
inurl:space.bilibili.com/UP主UID
```

### 文件型搜索 (此方法推荐与site:混合使用)
>```java
filetype:文件格式
```
比如你想搜索哔哩哔哩内的pdf文件可以使用以下语句
```text
site:bilibili.com filetype:pdf
```

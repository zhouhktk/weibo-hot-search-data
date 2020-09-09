# weibo-hot-search-data

## 微博热搜数据

### 功能

存放新浪微博热搜每日不同时段的实时数据

### 数据存储

- 按`年/月/日`归档
- XX时.json

### 数据样例

```json
{
    "number": "1",
    "url": "https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%8F%B2%E4%B8%8A%E6%9C%80%E5%A4%A7%E5%BC%83%E5%A5%96%E8%AF%9E%E7%94%9F%23&Refer=top",
    "topic": "中国体彩史上最大弃奖诞生",
    "popularity": "865558"
}
```



### 数据来源

- 使用[weibo-hot-search-spider](https://github.com/zhouhktk/weibo-hot-search-spider)仓库
- 程序部署在服务器上，每天定时爬取数据，存入json文件
- 爬取时段：7时、9时、11时、13时、15时、17时、19时、21时、23时

### 爬虫代码

Github仓库：[weibo-hot-search-spider](https://github.com/zhouhktk/weibo-hot-search-spider)


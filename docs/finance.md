---
pageClass: routes
---

# 金融

## CFD

### 每周股指派息调整 (GBP)

<Route author="HenryQW" example="/cfd/div_gbp" path="/cfd/div_gbp" />

## finviz

### 美股股票新闻

<Route author="HenryQW" example="/finviz/news/AAPL" path="/finviz/news/:ticker" :paramsDesc="['股票代码']"/>

## WEEX 华尔街见闻旗下全球投资线上品牌

### 资讯

<Route author="SChen1024" example="/weexcn/news/1" path="/weexcn/news/:typeid" :paramsDesc="['栏目代码, 按照表列出']" />

| 最新文章 | 市场要闻 | 交易策略 | 机构观点 | 投资学堂 | 行业观察 | 基金理财 | 分析师投稿 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | ---------- |
| 1        | 2        | 3        | 4        | 5        | 6        | 7        | 8          |

## 财联社

### 电报

<Route author="nczitzk" example="/cls/telegraph" path="/cls/telegraph"/>

### 深度

<Route author="nczitzk" example="/cls/depth/1000" path="/cls/depth/:caty" :paramsDesc="['分类代码，可在首页导航栏的目标网址 URL 中找到']">

| 要闻 | 股市 | 环球 | 公司 | 地产 | 券商 | 金融 | 汽车 | 科创版 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ |
| 1000 | 1003 | 1007 | 1005 | 1006 | 1118 | 1032 | 1119 | 1111   |

</Route>

## 富途牛牛

### 要闻

<Route author="Wsine" example="/futunn/highlights" path="/futunn/highlights" />

## 淘股吧股票论坛

### 论坛总版

<Route author="emdoe" example="/taoguba/index" path="/taoguba/index"/>

### 用户博客

<Route author="emdoe" example="/taoguba/user/252069" path="/taoguba/user/:uid" :paramsDesc="['用户 id']" />

## 天天基金

### 用户动态

<Route author="zidekuls" example="/eastmoney/user/6551094298949188" path="/eastmoney/user/:uid" :paramsDesc="['用户 id, 可在用户主页 URL 中找到']"/>

## 新浪财经

### 新浪财经－国內

<Route author="yubinbai" example="/sina/finance" path="/sina/finance" />

## 雪球

### 用户动态

<Route author="imlonghao" example="/xueqiu/user/8152922548" path="/xueqiu/user/:id/:type?" :paramsDesc="['用户 id, 可在用户主页 URL 中找到', '动态的类型, 不填则默认全部']">

| 原发布 | 长文 | 问答 | 热门 | 交易 |
| ------ | ---- | ---- | ---- | ---- |
| 0      | 2    | 4    | 9    | 11   |

</Route>

### 用户收藏动态

<Route author="imlonghao" example="/xueqiu/favorite/8152922548" path="/xueqiu/favorite/:id" :paramsDesc="['用户 id, 可在用户主页 URL 中找到']"/>

### 用户自选动态

<Route author="hillerliao" example="/xueqiu/user_stock/1247347556" path="/xueqiu/user_stock/:id" :paramsDesc="['用户 id, 可在用户主页 URL 中找到']"/>

### 基金净值更新

<Route author="HenryQW" example="/xueqiu/fund/040008" path="/xueqiu/fund/:id" :paramsDesc="['基金代码, 可在基金主页 URL 中找到. 此路由的数据为场外基金 (`F`开头)']"/>

### 组合最新调仓信息

<Route author="ZhishanZhang" example="/xueqiu/p/ZH1288184" path="/xueqiu/snb/:id" :paramsDesc="['组合代码, 可在组合主页 URL 中找到.']"/>

### 股票信息

<Route author="YuYang" example="/xueqiu/stock_info/SZ000002" path="/xueqiu/stock_info/:id/:type?" :paramsDesc="['股票代码（需要带上交易所）', '动态的类型, 不填则为股票公告']">

| 公告         | 新闻 | 研报     |
| ------------ | ---- | -------- |
| announcement | news | research |

</Route>

## 中国人民银行

### 沟通交流

<Route author="nczitzk" example="/pbc/goutongjiaoliu" path="/pbc/goutongjiaoliu"/>

### 货币政策司公开市场交易公告

<Route author="nczitzk" example="/pbc/tradeAnnouncement" path="/pbc/tradeAnnouncement"/>

## 中证网

### 资讯

<Route author="nczitzk" example="/cs/news/zzkx" path="/cs/news/:caty" :paramsDesc="['资讯类型']">

| 中证快讯 | 行业资讯 |
| -------- | -------- |
| zzkx     | hyzx     |

</Route>

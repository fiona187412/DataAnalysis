# DataAnalysis

## CDNOW用户消费行为分析
本项目是数据的EDA探索+业务分析。
本数据集共有 7 万条左右数据，数据为 CDNow 网站 1997年1月至1998年6月的用户行为数据，共计 4 列字段，分别是：

特征名称  | 说明|
| :------------: |:---------------:|
user_id | 用户唯一ID |
order_dt  | 用户购买日期 |
order_products  | 用户订购产品的数量 |
order_amount  | 用户订购金额 |

分别观察了数据集的数据分布、对数据进行预处理(数据类型转换、缺失值、异常值处理)等。
- 用户消费趋势进行分析（按月）
- 用户个体消费分析
- 用户消费行为分析
- 指标生成及分析
- 总结与意见


## IMDB电影数据分析（Kaggle）
本项目是数据的EDA，针对Kaggle的IMDD电影数据进行分析，探索变量之间的相关性、电影的发展趋势等。这个数据集的特征如下表所示：

特征名称  | 说明|
| :------------: |:---------------:|
imdb_id | IMDB 标识号 |
popularity | 在 Movie Database 上的相对页面查看次数 |
budget | 预算（美元）|
revenue |收入（美元） |
original_title | 电影名称 |
cast | 演员列表，按 | 分隔，最多 5 名演员 |
homepage | 电影首页的 URL |
director | 导演列表，按 | 分隔，最多 5 名导演 |
tagline | 电影的标语 |
keywords | 与电影相关的关键字，按 | 分隔，最多 5 个关键字 |
overview | 剧情摘要 |
runtime | 电影时长 |
genres | 风格列表，按 | 分隔，最多 5 种风格 |
production_companies | 制作公司列表，按 | 分隔，最多 5 家公司 |
release_date | 首次上映日期 |
vote_count | 评分次数 |
vote_average | 平均评分 |
release_year | 发行年份 |
budget_adj | 根据通货膨胀调整的预算（2010 年，美元）|
revenue_adj |根据通货膨胀调整的收入（2010 年，美元）|


## 2019-nCOv 
本项目是针对2019新型冠状肺炎的各地疫情（全球）的数据获取及可视化，针对数据集为爬虫抓取新冠肺炎疫情数据集。这个数据集的特征如下表所示：

特征名称  | 说明|
| :------------: |:---------------:|
areaTree | 这个节点下面包全世界数据，中国数据到市级的数据，是最详细的 |
lastUpdateTime | 最后更新时间 |
chinaTotal |国内累计值 |
chinaAdd | 国内每日新增 |
confirm | 确诊 |
heal | 治愈 |
dead | 死亡 |
nowConfirm | 现有确诊 |
suspect | 疑似 |
nowSevere | 重症 |
chinaDayList | 每日人数汇总历史数据 |
chinaDayAddList | 每日新增人数历史数据 |
dailyNewAddHistory | 每日新增人数历史数据，分湖北、非湖北、全国三个维度 |
articleList | 每日新发布新闻 |


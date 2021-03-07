# homework6
## 要求
为你的homework5增加博文功能

1. 要登录才能发（废话）
2. 记录发文章的人
3. 那一篇博文的内容肯定包含：标题、内容、作者、时间，当然别的你也可以自己加
4. 要有文章列表，而且点开能看博文的详情，当然最重要的是要有一个后台能让用户发博文。
5. 做好样式优化，可以去网上抄样式，怎么抄：f12开控制台看。
6. 已经写好的内容可以修改，所以需要有一个编辑页，但其实长相跟新增应该是基本一致的。


## 技术细节
你需要自己设计一个博文的表来存储数据

然后就是简单的增删改查了

## 高级要求
1. 给博文添加富文本编辑器，让你的博文能有色彩、文字大小等样式的可编辑可能。
2. 博文点进去之后可以有上一篇、下一篇的链接

## 时间分配
| 任务 | 时间 | 备注 | 熟练工建议时长 |
|--|--|--|
| 后台前端 | 30min | 后台，简洁明了为主。编辑、新增可以用同一个视图 | 10min |
| 博客前端 | 2h |  | 30min |
| 后端 | 40min | 前台有两个查询，一个是列表一个是文章内容，都是select。后台两个查询，insert和update。 | 10min |

## 提示
比如修改功能，你怎么确定我修改的是什么哪一篇？在设计数据表的时候你应该要意识到这个问题，需要有一个字段作为唯一索引，update的时候 `where id = ?` 就行了


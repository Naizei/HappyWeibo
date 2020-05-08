# HappyWeibo
 批量生成微博屏蔽词，净化微博环境

## 使用方法
### 直接使用
仓库里`ShieldWords.bak`和`ShieldWords.share_backup`文件已给出大部分常用屏蔽词，包括但不限于：

* 辱骂和引战

* 流量明星

* 营销号

* 宗教

* 小广告

使用方式如下：

* **See用户：** 下载`ShieldWords.bak`文件，依次点击设置->屏蔽设置->过滤词->导入，导入ShieldWords.bak；

* **Share用户：** 下载`ShieldWords.share_backup`文件，依次点击设置->隐私设置->关键词屏蔽->备份->导入屏蔽词，导入ShieldWords.bak；

### 自定义屏蔽词
1. 对`list_KW.txt`和`list_ID.txt`进行增删改查。

  其中`list_KW.txt`表示屏蔽关键词，`list_ID.txt`表示屏蔽账户名，格式均为

  ```
  屏蔽词1
  屏蔽词2
  ……
  屏蔽词n
  
  ```
  注意最后的换行符必不可少

2. 运行`transfer.sh`

3. 和上面一样的方法导入生成的文件

## 说明
1. 仅安卓用户可用本方法，需下载See或Share
2. See的屏蔽词不分用户名和关键词，且仅对首页、热门、评论有效，对搜索无效；Share的屏蔽词分用户名和关键词，对首页、热门、评论、搜索均有效
3. 为方便删去重复词，`list_KW.txt`和`list_ID.txt`内的屏蔽词按拼音顺序重新排列过，事实上顺序并无影响
4. 请谨慎使用，若使用此方法产生重要消息遗漏等损失，本人概不负责

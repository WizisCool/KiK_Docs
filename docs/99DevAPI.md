---
title: 开发者API
description: dev
sidebar_label: 开发者API


# hide_table_of_contents: false
---

## 逐步开放一些KiK或者Hanbot x64的API  
  

### 1.KiK-Hanbot脚本胜率数据库(hanbot.cc)
- 正如你所见,你可以通过 [KiK-Hanbot脚本胜率数据库(db.hanbot.cc)](https://db.hanbot.cc) 
- 来查看各个英雄的Hanbot脚本的胜率情况  
- 不光开发者,这个网站同样开放给用户!且不会有任何引流广告!  
  
### 2.Hanbot脚本数据JSON
- 为了开发者可以更方便的调用获取各个脚本的胜率与选取率情况,我们还提供了Json格式的数据  
- 这些数据会在每天更新,它的实时的  
- 所以开发者们可以放心的在自己的程式中调用  
  
- JSON数据更新地址:[https://shards.hanbot.cc](https://shards.hanbot.cc)  
- 此Json格式同样适用于Shards.js文件

  
示例格式如下:

```jsx title="Json格式"
    "Aatrox": {                         //英雄名
        "shards": [
            {
                "name": "xxxx",         //脚本名称
                "id": "cno1_aio",       //脚本标识ID
                "pick_rate": 0.4423,    //该脚本选取率
                "win_rate": 0.6435      //该脚本胜率
            },
        ],
        "pick_rate": 0.0659,            //英雄选取率
        "win_rate": 0.6271              //英雄胜率
    },
    ....
```
  
### 3.HanbotNeverDead API SDK文档
- 如果你以前为Hanbot或者想成为Hanbot的开发者,那么SDK文档是必不可少的  
- KiK可以为您提供一个安全的测试环境和完整的SDK文档
- [KiK x Hanbot SDK Documentation (docs.hanbot.cc)](https://docs.hanbot.cc)
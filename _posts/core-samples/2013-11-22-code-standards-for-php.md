---
layout: post
category : php
tagline: "php常用编码规范"
tags : [php]
---
{% include JB/setup %}

##编码规范
文件编码统一为：__UTF-8__，请开发人员调整开发编辑器的编码为UTF-8，并关闭UTF-8 BOM功能，请不要使用windows自带的记事本编辑项目文件。

## 命名规范
#### 类命名
使用__大驼峰法__命名，即每个单词的首字母均大写；

  class SimpleDB {

  }

#### 函数命名
使用__小驼峰法__命名，即第一个单词首字母小写，其余单词首字母均大写；
  
  public function __construct($downloadPath = '') {

  }


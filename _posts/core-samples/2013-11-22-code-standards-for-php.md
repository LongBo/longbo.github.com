---
layout: post
category : php
tagline: "php常用编码规范"
tags : [php]
---
{% include JB/setup %}

##编码规范
文件编码统一为：__UTF-8__，请开发人员调整开发编辑器的编码为UTF-8，并关闭UTF-8 BOM功能，请不要使用windows自带的记事本编辑项目文件。

##命名规范
####类命名
使用__大驼峰__命名法。即每个单词的首字母都要大写：

	class OneClassName{

	}

####函数命名
使用__小驼峰__命名法。即第一个单词首字母小写，其他的首字母大写：
@特殊函数，魔术函数前加下划线__,

	public function __construct(){

	}

@普通函数,
	
	public function doFuncation(){

	}

####变量命名
使用__小驼峰__命名法，

	public $constantVar;

私有变量前加下划线_，

	private $_privateVar;

####常量命名
全部大写

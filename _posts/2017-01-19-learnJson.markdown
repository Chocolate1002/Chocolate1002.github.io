---
layout: post
title:  "Learn Json"
categories: jekyll update
tags:
---
## Json是js语法的子集

## ES5对解析JSON的行为进行了规范，定义了全局对象JSON。
   JSON对象有两个方法：** stringify() ** 和 ** parse() ** ，** stringify() **把js对象序列化为JSON字符串，** parse() ** 把JSON字符串解析为原生js值。

   在序列化js对象时，所有函数及原型都会被有意忽略，不体现在结果中。此外，值为undefined的任何属性也都会被跳过。结果中最终都是值为有效JSON数据类型的实例属性。

### Json中的对象
   Json中的对象要求给属性加双引号。

    {
        "name": "Nicholas",
        "age": 9
    }

###
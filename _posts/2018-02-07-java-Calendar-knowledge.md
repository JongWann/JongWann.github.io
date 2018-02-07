---
layout: post
title:  Calendar knowledge
subtitle: 每天一个小知识
card-image: 
date:     2018-02-07 19:00:00
tags:     java
post-card-type: article
---
# Calendar
### 使用Calendar将当前时间加一天或减一天
> 记得在做整车称重需求的时候,当时冒烟测试没有通过,其原因就是由于在取数据时,时间设置错了,本该使用add,但是用成了set,导致没有取到这些数据.不过这不是我写的,手动滑稽~
使用add方法,不是set方法
add是对当前的日期做加减操作
set是直接设置当前的日期
实例:
```
 ate t= new Date();
 alendar cal = Calendar.getInstance();
 al.setTime(t); //设置日期
 al.add(Calendar.DAY_OF_MONTH , 1);//当前时间增加一天
 al.add(Calendar.DAY_OF_MONTH , -1);//当前时间减一天
```

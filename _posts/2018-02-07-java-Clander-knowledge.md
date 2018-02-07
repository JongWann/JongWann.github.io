---
layout:         post
title:          Clander knowledge
subtitle:        
card-image:     
date:           2018-02-07 19:00:00
tags:           code
post-card-type: article
---

# 使用Calendar将当前时间加一天或减一天
使用add方法,不是set方法
add是对当前的日期做加减操作
set是直接设置当前的日期
实例:
Date t= new Date();
Calendar cal = Calendar.getInstance();
cal.setTime(t); //设置日期
cal.add(Calendar.DAY_OF_MONTH , 1);//当前时间增加一天
cal.add(Calendar.DAY_OF_MONTH , -1);//当前时间减一天

[TOC]
#我对信息素养实践课程的认识  
##我的认识  
我认为**信息素养实践课** 很有用，感觉重在培养学生的实践能力，以实践为主，理论知识很少，都是一些基本的实践，课上讲的内容需要在课下不断地复习练习，虽说任何一门课程都离不开课下的复习练习，但是信息素养实践课死记硬背的东西实在不多，主要通过练习来达到熟悉的程度即*熟能生巧*，自主探究、合作学习。现在的我们大部分大学生缺乏信息敏感性，缺乏主动创造性，自觉评估意识不强，还有重藏轻用的陈旧观念等，所以我们很有必要培养信息意识，可以从信息获取与传播意识、信息保密意识、信息安全意识、信息道德意识四个方面来培养信息意识，要有信息获取、分析、评价的能力。
##什么是信息素养  
[什么是信息素养](http://www.zhixing123.cn/lilun/32201.html)
##代码  
~~~
import random
def caishu():
    i=0
    key =random.randint(1,10)
    while i<5:
        guss=int(input())
        if key==guss:
            print("good guss!")
            break
        elif guss>key:
            print("大了")
        else:
            print("小了")
        i=i+1
    else:
        print("game over")
        print("key is :",key)
caishu()  
~~~
import random
def caishu():
    i=0
    key =random.randint(1,10)
    while i<5:
        guss=int(input())
        if key==guss:
            print("good guss!")
            break
        elif guss>key:
            print("大了")
        else:
            print("小了")
        i=i+1
    else:
        print("game over")
        print("key is :",key)
caishu()  
##表格  
|章节|标题|课时|
|第一章|计算机概述|4|
|:-:|-:|:-|
##列表  
1.a
2.b
* 1
* 2
# 备注  
***班级 7班 姓名 王英德 学号 2020012404***

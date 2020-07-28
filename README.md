## 项目介绍

该项目属于学习 Demo

## 开发环境

python 3.x

## 需求描述

* 数据：
生成12组数据，每组数据中有11条医疗保健途径的名称以及花费a，在这11条医疗保健途径中随机选一条作为目标，剩下的10条路径的花费的值在范围X-Y中随机生成，那个目标的花费的值Z有两种情况：一种是只比范围X-Y大一点点，这个是困难题；另一种是比范围X-Y大很多，这个是简单题。12组数据分为6组简单题6组困难题。每组数据的目标都是随机挑选出来的。
* 题目：
根据那12组数据生成12张图，12张图就是12个选择题，每道题的问题都是是哪一条医疗保健途径花费最多。因为系统是知道正确答案的（就是上面从每组数据中随机选择出来的目标），所以在用户做每道题的时候记录下来做的是简单题还是困难题，做的正确还是错误，还有做每一道题的时间。在做题时这12道题出现的顺序也应该是随机的。
图的样式：
大概是两个竖直的条形图，两个水平的条形图，两个饼图，这是总共6种图，每种图有一个简单题一个困难题，总共就是12张图。

## 医疗保健途径名字

1. Admitted
2. Call Closed
3. Discharged
4. Emergency dentist
5. MIU
6. Not picked up in an ambulance
7. OOH
8. Out-patient clinic
9. Seen by A&E doctor
10. Spoke to a primary care service
11. WIC
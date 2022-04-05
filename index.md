---
layout: cv
title: 左佳
email:
  url: mailto:hit.zzj.zuojia@gmail.com
  text: hit.zzj.zuojia@gmail.com
homepage:
  url: http://zuozuojia.github.io
  text: zuozuojia.github.io
phone: (+86)158 0635 2317
---

# **左 佳**

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## **教育背景**

### **哈尔滨工业大学（威海）** `2019/9 - 至今`

```
威海, 中国
```

- 测控技术与仪器
- GPA: 81/100     3.15/4.0
- 语言：CET-6     IELTS: 6.0

## **领导经历**

### **718 智能车实验室** <!-- (https://zuozuojia.github.io/posts/Introduction/)-->
- **负责人** `2020/9 – 2021/9`
<br> 

作为成员 60 余人的实验室负责人，负责团队纳新、宣传、运营: 组织大小赛事 4 场；面向全校开展科普与科创知识培训，前后覆盖面共计 1800 余人；首次将实验室由只有电控成员转型成为兼容视觉与机械的人才培养基地。 <br>
 <!-- 
[[PDF]({{ page.homepage.url }}/assets/uist-21-recode.pdf)]
[[BibTeX]({{ page.homepage.url }}/assets/uist-21-recode.txt)]
[[video preview](https://youtu.be/fMdHK9UrgQ4)]
[[talk](https://youtu.be/_GQ8E7EMMws)]-->

### **HERO 竞技机器人** <!-- (https://zuozuojia.github.io/posts/Introduction/)`2020/9 – 至今`-->
- **副队长， 项目管理** `2021/1 – 2021/8`
<br> 

管理团队开发进度及人员任务分工。负责自身嵌入式、算法工作的同时，参与机械设计、审图。 <br>
 <!-- 
[[PDF]({{ page.homepage.url }}/assets/uist-21-recode.pdf)]
[[BibTeX]({{ page.homepage.url }}/assets/uist-21-recode.txt)]
[[video preview](https://youtu.be/fMdHK9UrgQ4)]
[[talk](https://youtu.be/_GQ8E7EMMws)]-->

- **队长** `2021/9 – 至今`
<br> 

管理 40 余人的团队，组织团队参加 RoboMaster 赛事。负责全队机械、电控、视觉、运营的研发方向与进度。 <br>
 <!-- 
[[PDF]({{ page.homepage.url }}/assets/uist-21-recode.pdf)]
[[BibTeX]({{ page.homepage.url }}/assets/uist-21-recode.txt)]
[[video preview](https://youtu.be/fMdHK9UrgQ4)]
[[talk](https://youtu.be/_GQ8E7EMMws)]-->


## **项目研发经历**
**718 智能车实验室**`2019 – 2021`

2019/11 – 2020/9 **嵌入式软件开发**
<br> 
- 自平衡两轮智能车 全国大学生智能车竞赛

基于串级 PID 控制器的两轮直立车的平衡和运动算法。基于 PID 控制器的电磁循迹算法。适应复杂路段（例如环岛、急转弯、坡道等）的循迹算法。使用六轴姿态传感器基于卡尔曼滤波的姿态解算算法。
- 智能手表 全国大学生电子设计大赛

使用 OLED 和按键进行人机交互，实现菜单算法。测量体温，并自动刷新、绘制温度随时间变化的折线图。抬腕自动亮屏、放下自动熄屏、自动检测睡眠姿态防亮屏算法。检测运动状态，记录步数。
<br>
 <!-- 
[[PDF](http://penrose.ink/media/Penrose_SIGGRAPH2020.pdf)]
[[BibTeX]({{ page.homepage.url }}/assets/siggraph20-penrose.txt)]
[[www](http://penrose.ink/siggraph20.html)]
[[repo](https://github.com/penrose/penrose)]-->

**HERO 竞技机器人队** RoboMaster 机甲大师高校系列赛 `2020/9 – 至今`

2020/9 – 至今 **嵌入式软件开发**
<br> 
- 独立设计主力开发基于 RT-Thread 的电控软件架构

基于串级 PID 的两轴云台控制，数据源可由 IMU 与磁编码器顺滑切换。修复 RT-Thread 中的关于 CAN、PWM 等外设驱动代码错误。基于特殊 PID 的陀螺仪的温度控制器算法。遥控控制机器人发弹、运动等算法。基于视觉的自动瞄准打击目标算法。
- 自主开发基于 RT-Thread 的电机智能控制板软件

设计基于 CAN 通信的主从机通信协议，包括设置指令、控制指令、读取指令、错误处理以及其反馈报文。实现主机一条指令实现的电机自动初位置校准、自动角度/转速闭环等。主从机掉线自动处理机制，电机堵转、掉线报警。
<br>

2021/1 – 2021/4	**视觉/算法开发**
<br> 
- 抗干扰的自适应曝光算法

自动识别并抠除窗户等大光斑，利用 PI 控制器实现自动曝光，以便后期目标检测。
<br>
 <!-- 
[[PDF](http://penrose.ink/media/Penrose_SIGGRAPH2020.pdf)]
[[BibTeX]({{ page.homepage.url }}/assets/siggraph20-penrose.txt)]
[[www](http://penrose.ink/siggraph20.html)]
[[repo](https://github.com/penrose/penrose)]-->

**数学建模竞赛 4 场**`2020/9 – 2022/2`

2020/9 – 至今	**队长**
<br> 
- 使用 Python、MatheMatica，完成模型建立、随机地图生成、最短路径算法以及可视化处理。
- 使用 Python，完成 TOPSIS 综合分析、灰色关联分析，使用 Networkx 实现节点影响力可视化。
- 使用 Python 和 SPSS 建模，使用多因素方差分析、Spearman 相关系数分析、MLP 探究乙醇催化偶合制备 C4 烯烃工艺条件的优化问题。
- 建模探究世界公平的影响因素，并进行论文的撰写。
<br>
 <!-- 
[[PDF](http://penrose.ink/media/Penrose_SIGGRAPH2020.pdf)]
[[BibTeX]({{ page.homepage.url }}/assets/siggraph20-penrose.txt)]
[[www](http://penrose.ink/siggraph20.html)]
[[repo](https://github.com/penrose/penrose)]-->



## **IT 技能**
- 编程语言：C > Python > C++ > 汇编 > Verilog
- 平台：STM32，MSP430，STC，LPC，Linux
- 软件工具：熟练使用 Keil、IAR、LabView、SPSS，熟悉 MATLAB、Webots、Solidworks
- 嵌入式实时系统 (RTOS)：RT-Thread


## **获奖情况**
**国家级奖项**
- 二等奖, 第二十届全国大学生机器人大赛 ROBOMASTER 2021 机甲大师超级对抗赛全国赛 `2021/8`
- 二等奖, 2021 年高教杯全国大学生数学建模竞赛本科生组 `2021/11`

**区级奖项**
- 一等奖, 第二十届全国大学生机器人大赛 ROBOMASTER 2021 机甲大师超级对抗赛区域赛北部赛区 `2021/8`

**省级奖项**
- 一等奖, 第十一届山东省大学生科技节-科技馆展品创意与制作设计大赛 `2019/11`
- 二等奖, 全国大学生数学建模竞赛山东赛区 `2020/10`
- 二等奖, 全国大学生电子设计大赛山东赛区 `2020/10`
- 二等奖, 全国大学生智能车大赛山东赛区 `2020/10`

**荣誉称号及奖学金**
- 优秀科创个人, 哈尔滨工业大学（威海）2020 年度信息科学与工程学院 `2020/12`
- 科技创新奖学金, 哈尔滨工业大学（威海）2019-2020 春季学期 `2020/6`
- 科技创新奖学金, 哈尔滨工业大学（威海）2019-2020 秋季学期 `2020/10`
- 二等奖学金, 哈尔滨工业大学（威海）2020-2021 春季学期 `2021/5`
- 优秀学生干部, 哈尔滨工业大学（威海）2019-2020 年度 `2020/12`

## **学生工作经历**
- 1902805 班学习委员
- 1902202 班心理委员
- 哈尔滨工业大学（威海）校合唱团成员
- 哈尔滨工业大学（威海）信息科学与技术学院学生会科创中心部员
- 2019-2020 年秋高级电子技术课程助教

<!-- ### Footer

Last updated: May 2013 -->

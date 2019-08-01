用Watson Studio来分析和预测羊毛党
===
概述
---
>本文利用 [IBM Cloud - Watson Studio](cloud.ibm.com)/[Watson Studio Desktop](https://www.ibm.com/cloud/watson-studio) 建立羊毛党历史行为习惯数据模型，预测和识别羊毛党行为
-----

近年来，互联网平台的用户补贴大战风生水起，O2O 和共享经济模式发展迅速，企业通过各种线上的优惠券、抵值券或者积分等营销活动吸引消费者。企业为营销活动千金散尽，让用户获得了不少真金白银。


>用技术来分析羊毛党
-----
随着 AI 技术、生物识别技术、大数据技术、智能身份验证技术都在日趋完善，基于新技术、平台有更多办法可以强化对用户行为的识别，与此同时不影响用户体验。比如今天在手机App上越来越多支持人脸识别技术。未来平台开展优惠补贴营销活动，也可以与这样的技术多多结合，将“羊毛党”拦截在门外，或者提高他们的参与门槛。

工作流
---
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/flow_20190614092004.jpg)

1. 登陆到IBM Watson Studio<br>
2. 在Watson Studio中导入并SPSS Model Flow<br>
3. 使用Model Flow训练并部署模型<br>

包含组件
---
1. Watson Studio: IBM's integrated hybrid environment that provides flexible data science tools to build and train AI models and prepare and analyze data.<br>

Deploy on IBM CLoud
---
### 1. 注册 Watson Studio
---
注册并登陆IBM Cloud平台，通过创建Watson Studio服务后登陆平台创建一个新的项目
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC01.png)

### 2. 创建项目 : 选择项目模板：Modeler并创建模板
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC02.png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC03.png)


### 3. 导入模型
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/001.jpg)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/002.jpg)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/003.jpg)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC04.png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/004.jpg)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC06.png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC08.png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/005.jpg)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC10.png)

### 4. 运行Spss Moduler模型

Deploy on Local
---
1. [下载Watson Studio](###download) <br>
2. [创建项目](###create-project) <br>
3. [导入模型](###import-project)<br>
4. [运行Spss Moduler模型](###run-moduler)<br>

### 1. 下载[Watson Studio Desktop](https://www.ibm.com/cloud/watson-studio?loc=cn-zh)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/屏幕截图(78).png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/屏幕截图(79).png)

### 2. 创建项目（同Watson Studio on Cloud)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/屏幕截图(82).png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/屏幕截图(81).png)

### 3. 导入模型（同Watson Studio on Cloud)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/屏幕截图(83).png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/屏幕截图(84).png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/屏幕截图(85).png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/屏幕截图(86).png)

### 4. 运行Spss Moduler模型（同Watson Studio on Cloud)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/屏幕截图(119).png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/屏幕截图(117).png)

Use Watson Studio and SPSS Moduler Data Flow to predict the econnoisseur
===
Overview
---
>本文利用 [IBM Cloud - Watson Studio](cloud.ibm.com)/[Watson Studio Desktop](https://www.ibm.com/cloud/watson-studio) 建立羊毛党历史行为习惯数据模型，预测和识别羊毛党行为
-----

近年来，互联网平台的用户补贴大战风生水起，O2O 和共享经济模式发展迅速，企业通过各种线上的优惠券、抵值券或者积分等营销活动吸引消费者。企业为营销活动千金散尽，让用户获得了不少真金白银。


>用技术来分析羊毛党
-----
随着 AI 技术、生物识别技术、大数据技术、智能身份验证技术都在日趋完善，基于新技术、平台有更多办法可以强化对用户行为的识别，与此同时不影响用户体验。比如今天在手机App上越来越多支持人脸识别技术。未来平台开展优惠补贴营销活动，也可以与这样的技术多多结合，将“羊毛党”拦截在门外，或者提高他们的参与门槛。

Flow
---
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/flow_20190614092004.jpg)

1. 登陆到IBM Watson Studio<br>
2. 在Watson Studio中导入并SPSS Model Flow<br>
3. 使用Model Flow训练并部署模型<br>

Include Components
---
1. Watson Studio: IBM's integrated hybrid environment that provides flexible data science tools to build and train AI models and prepare and analyze data.<br>

Deploy on IBM CLoud
---
### register
1. Sign up for Watson Studio
---
注册并登陆IBM Cloud平台，通过创建Watson Studio服务后登陆平台创建一个新的项目
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC01.jpg)

### create
2. 创建项目 : 选择项目模板：Modeler并创建模板
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC02.png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC03.png)


### import
3. 导入模型
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC04.png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC05.png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC06.png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC08.png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC09.png)
![flow](https://github.com/JiaYinLei0809/econnoisseur/blob/master/source/IC10.png)

### run
4. 运行Spss Moduler模型

Deploy on Local
---
1. [下载Watson Studio](###download) <br>
2. [创建项目](###create-project) <br>
3. [导入模型](###import-project)<br>
4. [运行Spss Moduler模型](###run-moduler)<br>

### download
1. 下载Watson Studio

### create project
2. 创建项目

### import project
3. 导入模型

### run moduler
4. 运行Spss Moduler模型

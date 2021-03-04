---
title: 如何设置循环和连续的电子邮件活动
description: 了解如何设置循环和连续投放并了解两种方法之间的差异。
feature: 工作流
topics: channel activities
kt: 1560
doc-type: feature video
activity: use
team: TM
role: 业务从业者
level: 初学者
translation-type: tm+mt
source-git-commit: a16eb6d92ca40a1188e1ba6730bc28c2fb8358ce
workflow-type: tm+mt
source-wordcount: '270'
ht-degree: 6%

---


# 如何设置循环和连续的电子邮件活动

本教程介绍如何设置循环和连续投放，以及两种方法之间的差异。

## 循环和连续投放跟踪{#recurring-and-continuous-delivery-tracking}

循环投放和连续数据在管理联系数据的方式上有所不同：

* **连续投放**&#x200B;允许您向现有投放添加新收件人，并避免您每次添加新收件人时都必须创建新投放。 您可以直接在活动工作流中更新创意，它将更新投放模板资源文件夹中的模板。

   连续投放将创建SINGLE投放和投放日志(broadLog)以及引用每次执行一个投放时添加一个的跟踪日志。

![连续投放](/help/assets/delivery_continuous.jpg)

* 每次执行&#x200B;**循环投放**&#x200B;时，都将创建一个新投放实例。 例如，如果该工作流计划每周运行一次，则一年后将产生52个投放。 这也意味着，广义日志和跟踪日志将由每个投放实例分隔。

![循环投放](/help/assets/delivery_recurring.jpg)

## 如何设置循环投放 {#how-to-set-up-a-recurring-delivery}

此视频介绍如何配置循环投放和调度程序活动。

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## 如何设置连续投放 {#how-to-set-up-a-continuous-delivery}

此视频演示如何使用增量投放配置连续查询。

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## 其他资源

[在定位工作流中创建重复投放](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/use-cases/sending-a-birthday-email.html#creating-a-recurring-delivery-in-a-targeting-workflow)
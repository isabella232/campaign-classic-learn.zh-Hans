---
title: Android 推送通知入门 - 简介
description: 本教程将指导您完成从 Adobe Campaign 发送推送通知以及在 Android 应用程序中接收这些通知所涉及的步骤。
feature: Push
jira: KT-6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noDisplay
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
source-git-commit: f4e86b933660ced199c30d318445363b74c51c4b
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 100%

---

# Android 推送通知入门 - 简介

通过 Adobe Campaign，您可以向 [!DNL iOS] 和 [!DNL Android] 移动设备发送个性化的分段 [!DNL push] 通知。本教程将指导您完成将 [!DNL push] 通知从 Adobe Campaign 发送到 [!DNL Android] 应用程序时涉及的步骤。

## 先决条件

在开始之前，您将需要具备以下各项：

1) **Android 移动应用程序**

   本教程不涵盖设置移动应用程序所需的详细步骤。您将需要具有 [!DNL Campaign SDK] 集成&#x200B;**的**[!DNL Android] 移动应用程序。

   您可以在产品文档中找到所需步骤的详细说明：

   [将 Campaign SDK 集成到移动应用程序](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=zh-Hans)

   您还可以使用 Experience Platform Mobile SDK。有关详细信息，请观看教程视频：

   [使用 Experience Platform Mobile SDK 配置推送通道](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=zh-Hans)

2) **[!DNL Mobile App channel]软件包已安装**

   需要在 [!DNL Campaign] 实例上安装 [!DNL Mobile App channel] 软件包。以下视频介绍如何检查是否在实例上安装了 [!DNL Mobile App channel]，如果未安装，则介绍如何安装。

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12&learn=on)

## 教程概述

我们希望向 [!DNL Neotrip] [!DNL Android] 移动应用程序的订户发送个性化促销 [!DNL push] 通知。[!DNL Neotrip] 应用程序配置有 [!DNL Campaign SDK]，我们已确保在 [!DNL Campaign] 实例上激活 [!DNL Mobile App channel]。

需要以下配置步骤：

### 步骤 1：扩展应用程序订阅模式以个性化 [!DNL push] 通知

由于我们希望个性化 [!DNL push] 通知，因此将首先[扩展应用程序订阅模式](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)，以便能够存储用户订阅服务时从应用程序收到的个性化值。

### 步骤 2：在 Campaign 中配置 Android 服务并创建移动应用程序

接下来，我们将需要[在 Campaign 中配置 Android 服务并创建移动应用程序](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md)。在此步骤中，我们会将 [!DNL Neotrip] 应用程序定义为推送通知的目标。

### 步骤 3：配置并发送推送通知

然后，我们准备好[配置并发送推送通知](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)。

## 启动教程

步骤 1：[扩展应用程序订阅模式](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)

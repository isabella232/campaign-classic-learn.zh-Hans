---
title: Android推送通知入门——简介
description: 本教程将指导您完成从 Adobe Campaign 发送推送通知以及在 Android 应用程序中接收这些通知所涉及的步骤。
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 016f47e131df9c3a25b9131da372efaedf6cd5ad
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 8%

---


# Android推送通知入门——简介

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. 本教程将指导您完成将通知从Adobe Campaign发 [!DNL push] 送到应用程序时涉及的 [!DNL Android] 步骤。

## 先决条件

在开始之前，您需要具备以下各项：

1) **Android Mobile应用程序**

   本教程不涵盖设置移动应用程序所需的详细步骤。 您需要集成一个 **[!DNL Android]移动应用程 [!DNL Campaign SDK] 序**。

   您可以在产品文档中找到所需步骤的详细说明：

   [将 Campaign SDK 集成到移动应用程序](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   您还可以使用Experience PlatformMobile SDK。 有关详细信息，请观看教程视频：

   [使用Experience PlatformMobile SDK配置推送渠道](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]已安装**

   需 [!DNL Mobile App channel] 要在实例中安装 [!DNL Campaign] 包。 以下视频介绍如何检查实例 [!DNL Mobile App channel] 中是否已安装，如果未安装，如何安装。

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## 教程概述

我们希望向移动应用的订 [!DNL push] 户发送个性化促 [!DNL Neotrip] 销通 [!DNL Android] 知。 应 [!DNL Neotrip] 用程序已配置 [!DNL Campaign SDK] ，我们已确保在实例 [!DNL Mobile App channel] 上激活该 [!DNL Campaign] 应用。

需要以下配置步骤：

### 第1步：扩展应用程序订阅模式以个性化通 [!DNL push] 知

由于我们希望个性化通 [!DNL push] 知，因此我们将首 [先扩展应用订阅模式](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) ，以便能够存储用户订阅服务时从应用程序收到的个性化值。

### 第2步：配置Android服务并在活动中创建移动应用程序

接下来，我们需 [要配置Android服务并创建活动的移动应用程序](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md)。 在此步骤中，我们将将应 [!DNL Neotrip] 用程序定义为推送通知的目标。

### 第3步：配置和发送推送通知

然后，我们便可 [以配置和发送推送通知](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)。

## 开始教程

第1步： [扩展应用程序订阅模式](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)

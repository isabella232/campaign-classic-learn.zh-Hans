---
title: Android推送通知入门教程——简介
description: 本教程将指导您完成从 Adobe Campaign 发送推送通知以及在 Android 应用程序中接收这些通知所涉及的步骤。
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 412fe93f45be1e98343b4e63cbd7dd9285444e46
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 6%

---


# Android推送通知入门教程——简介

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

本教程将指导您完成将通知从Adobe Campaign发 [!DNL push] 送到应用程序时涉及的 [!DNL Android] 步骤。

## 先决条件

在开始之前，您需要满足以下先决条件

1) 移动应用程序本教程不涵盖设置移动应用程序所需的详细步骤。 您需要集成一个 **[!DNL Android]移动应用程[!DNL Campaign SDK]** 序。

   * 您可以在将活动SDK集成到移动应用程 [序中找到所需步骤的详细说明](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)。

   * 您还可以使用Experience PlatformMobile SDK。 有关详细信息，请观 [看使用Experience PlatformMobile SDK配](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) 置推送渠道教程视频。

2) 已安装移动应用程序渠道包

   您需要在实例上安装移动应用程序渠道包。 以下视频介绍如何检查实例中是否安装了移动应用程序渠道，如果未安装，如何安装。

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## 教程

我们希望向Neotrip移动应用的订户发送个性化的促销推 [!DNL Android] 送通知。 Neotrip应用程序已使用活动SDK进行配置，我们已确保在我们的活动实例上激活移动应用程序渠道。

需要以下配置步骤：

### 第1步：扩展应用程序订阅模式以个性化推送通知

由于我们希望个性化推送通知，因此我们将首 [先扩展应用订阅模式](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) ，以便能够存储用户订阅服务时从应用程序收到的个性化值。

### 第2步：配置Android服务并在活动中创建移动应用程序应用程序

接下来，我们需 [要配置Android服务并创建活动的移动应用程序应用程序](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md)。 在此步骤中，我们将Neotrip应用程序定义为推送通知的目标。

### 第3步：配置和发送推送通知

然后，我们便可 [以配置和发送推送通知](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)。

## 开始教程

**[第1步：扩展应用程序订阅模式](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**

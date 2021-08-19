---
title: 故障排除控制面板
description: 了解如何对控制面板进行故障诊断。
feature: 控制面板
kt: 2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/trouble-shooting.html
exl-id: 016e8b77-20df-4ca5-b5e7-fe2f3e7ba7a3
source-git-commit: 2f8ae3d47e4debf71311f341d3c02ff3a7f5297a
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 故障排除 [!UICONTROL Control Panel]

## 登录和主页

### 症状：无法登录Experience Cloud

**要做什么：**
用户必须找到其IMS组织ID(xxx)。管理员必须将用户添加到要管理的每个实例的产品用户档案“Campaign-xxx-Admins”中。 如果用户是所有实例的管理员，则必须将自己添加为用户。

### 症状：Experience Cloud 主页中访问 [!UICONTROL Control Panel]的链接不显示给用户

**原因：**
用户只有在将他们添加为产品用户档案Campaign-xxx-Administrators/Admin _的用户后，才会看到这些链接_。

**要做什么：**
管理员必须将用户添加到要管理的每个 _实例的产品用户档案Campaign-xxx-_  Admin中。如果用户是所有实例的管理员，则必须将自己添加为用户。

### 症状：实例未列在 [!UICONTROL Control Panel]中

**原因：**
对于缺少的实例，最可能的 ** 用户必 _须添加为用户产品用户档案Campaign-xxx-_ Administrators/Admin

**要做什么：**
管理员必须将用户添加到要管理的每个 _实例的产品用户档案Campaign-xxx-_  Admin中。如果用户是所有实例的管理员，则必须将自己添加为“用户”。

### 实用视频

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*查找 IMS Org ID（00:26 分钟）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*如何将管理员在产品用户档案中添加为管理员，以便能够使用[!UICONTROL Control panel]（01:03 分钟）*

### 帮助文档

* [了解控制面板](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)
* [管理 [!UICONTROL Control Panel]的权限](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## 建立与 SFTP 服务器（客户端或 API）的连接

连接到 SFTP 服务器需要：

* [!UICONTROL Allow listing] 您连接到 SFTP 服务器的 IP 地址
* 必须在Adobe Campaign中注册的私钥/公钥对
* 要直接连接到SFTP服务器，您还需要SFTP客户端软件

### 帮助文档 {#helpful-docs}

* [登录 SFTP 服务器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

---
title: 故障排除控制面板
description: 利用控制面板，可按实例监控和管理SFTP存储并允许列表IP地址。
feature: 控制面板
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 42%

---


# 故障排除 [!UICONTROL Control Panel]

## 登录和主页

### 症状：无法登录Experience Cloud

**要做什么：**
用户必须找到其IMS组织ID(xxx)。管理员必须将用户添加到要管理的每个实例的产品用户档案“Campaign-xxx-Admins”中。 如果用户是所有实例的管理员，则必须将自己添加为用户。

### 症状：Experience Cloud 主页中访问 [!UICONTROL Control Panel]的链接不显示给用户

**原因：**
用户只有在产品用户档案 _Campaign-xxx-Administrators/Admin_ 中将其添加为用户后，才会看到这些链接。

**要做什么：**
管理员必须将用户添加到要管理的每个 _实例的产品用户档案Campaign-xxx-_  Admin中。如果用户是所有实例的管理员，则必须将自己添加为“用户”。

### 症状：实例未列在 [!UICONTROL Control Panel]中

**原因：**
对于缺少的实例，最可能的用户必须添加为“ _用户”产品用户档案Campaign-xxx-Administrators/_ Admin

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
* 如果直接连接到SFTP服务器，则需要SFTP客户端软件

### 帮助文档 {#helpful-docs}

* [登录 SFTP 服务器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)


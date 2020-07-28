---
title: 故障排除控制面板
description: 该控制面板允许您按实例和允许列表IP地址监视和管理SFTP存储。
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 1%

---


# 疑难解答 [!UICONTROL Control Panel]

## 登录和主页

### 症状： 无法登录Experience Cloud

**要做什么：**
用户需要找到其IMS组织ID(xxx)。 管理员需要将用户添加到产品用户档案“活动-xxx-管理员”中，管理员需要管理的每个实例。 如果用户是所有实例的管理员，则他们仍可能需要将自己添加为用户。

### 症状： Experience Cloud主页中的链接 [!UICONTROL Control Panel] 不显示给用户

**原因：**
用户只有在将其添加为产品用户档案“活动-xxx-管理员／管理员”时，才会看到这些链接

**要做什么：**
管理员需要将用户添加到产品用户档案“活动-xxx-管理员”中，管理员需要管理的每个实例。 如果用户是所有实例的管理员，他们可能仍需要将自己添加为“用户”。

### 症状： 实例未列在 [!UICONTROL Control Panel]

**原因：**
最可能的用户需要被添加为缺少实例的“用户”产品用户档案“活动-xxx-管理员／管理员”

**要做什么：**
管理员需要将用户添加到产品用户档案“活动-xxx-管理员”中，管理员需要管理的每个实例。 如果用户是所有实例的管理员，则他们仍可能需要将自己添加为“用户”。

### 实用视频

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*检查IMS组织ID（00:26分钟）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*如何向产品用户档案管理员添加管理员以便能够[!UICONTROL Control panel]使用（01:03分钟）*

### 帮助文档

* [发现控制面板](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [管理 [!UICONTROL Control Panel]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## 建立与SFTP服务器（客户端或API）的连接

连接到SFTP服务器需要：

* [!UICONTROL Allow listing] 您连接到SFTP服务器的IP地址
* 需要向Adobe Campaign注册的私钥／公钥对
* 如果直接连接到SFTP服务器，您还需要SFTP客户端软件

### 实用文档

* [登录 SFTP 服务器](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)


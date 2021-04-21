---
title: 故障排除控制面板
description: 该控制面板允许您按实例监测和管理 SFTP 存储以及将 IP 地址添加到允许列表。
feature: 控制面板
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 137d1e0c36d038f3fb8a4742bafef6fbac96f41d
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 100%

---


# 故障排除 [!UICONTROL Control Panel]

## 登录和主页

### 症状：无法登录 Experience Cloud

**要做什么：**
用户需要找到其 IMS Org ID (xxx)。管理员需要将用户添加到要管理的每个实例的产品用户档案“Campaign-xxx-Admins”中。如果用户是所有实例的管理员，则他们仍可能需要将自己添加为用户。

### 症状：Experience Cloud 主页中访问 [!UICONTROL Control Panel]的链接不显示给用户

**原因：**
用户只有在产品用户档案 _Campaign-xxx-Administrators/Admin_ 中将其添加为用户后，才会看到这些链接。

**要做什么：**
管理员需要将用户添加到要管理的每个实例的产品用户档案 _Campaign-xxx-Admins_ 中。如果用户是所有实例的管理员，他们可能仍需要将自己添加为“用户”。

### 症状：实例未列在 [!UICONTROL Control Panel]中

**原因：**
最可能的原因是对于缺少的实例，需要将用户在产品用户档案 _Campaign-xxx-Administrators/Admin_ 中添加为“用户”。

**要做什么：**
管理员需要将用户添加到要管理的每个实例的产品用户档案 _Campaign-xxx-Admins_ 中。如果用户是所有实例的管理员，则他们仍可能需要将自己添加为“用户”。

### 实用视频

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*查找 IMS Org ID（00:26 分钟）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*如何将管理员在产品用户档案中添加为管理员，以便能够使用[!UICONTROL Control panel]（01:03 分钟）*

### 帮助文档

* [了解控制面板](https://helpx.adobe.com/cn/campaign/kb/control-panel-overview.html)
* [管理 [!UICONTROL Control Panel]的权限](https://helpx.adobe.com/cn/campaign/kb/control-panel-access.html)

## 建立与 SFTP 服务器（客户端或 API）的连接

连接到 SFTP 服务器需要：

* [!UICONTROL Allow listing] 您连接到 SFTP 服务器的 IP 地址
* 需要向 Adobe Campaign 注册的私钥/公钥对
* 如果直接连接到 SFTP 服务器，您还需要 SFTP 客户端软件

### 帮助文档  {#helpful-docs}

* [登录 SFTP 服务器](https://helpx.adobe.com/cn/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)


---
title: 故障排除控制面板
description: 「控制面板」可以讓您依執行個體和允許清單IP位址監控及管理SFTP儲存。
feature: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 13f7ab2dd41216a603a22f181dc4d06302c5918a
workflow-type: tm+mt
source-wordcount: '330'
ht-degree: 80%

---


# 故障排除 [!UICONTROL Control Panel]

## 登录和主页

### 症状：无法登录 Experience Cloud

**要做什么：**
用户须找到其 IMS Org ID (xxx)。管理员须将用户添加到要管理的每个实例的产品用户档案“Campaign-xxx-Admins”中。如果用户是所有实例的管理员，他们仍须将自己添加为用户。

### 症状：Experience Cloud 主页中访问 [!UICONTROL Control Panel] 的链接不显示给用户

**原因：**
用户只有在产品用户档案 _Campaign-xxx-Administrators/Admin_ 中将其添加为用户后，才会看到这些链接。

**要做什么：**
管理员须将用户添加到要管理的每个实例的产品用户档案 _Campaign-xxx-Admins_ 中。如果使用者是所有執行個體的管理員，則他們仍需將自己新增為使用者。

### 症状：实例未列在 [!UICONTROL Control Panel] 中

**原因：**
最有可能的使用者必須新增為「使用者」產品設定檔 _Campaign-xxx-Administrators/Admin_ 針對遺失的執行個體

**要做什么：**
管理员须将用户添加到要管理的每个实例的产品用户档案 _Campaign-xxx-Admins_ 中。如果用户是所有实例的管理员，他们须将自己添加为“用户”。

### 实用视频

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12&learn=on)

*查找 IMS Org ID（00:26 分）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12&learn=on)

*如何将管理员在产品用户档案中添加为管理员，以便能够使用[!UICONTROL Control panel]（1 分 3 秒）*

### 帮助文档

* [了解控制面板](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)
* [管理 [!UICONTROL Control Panel]的权限](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)

## 建立与 SFTP 服务器（客户端或 API）的连接

连接到 SFTP 服务器需要：

* [!UICONTROL Allow listing] 您连接到 SFTP 服务器的 IP 地址
* 必须向 Adobe Campaign 注册的私钥/公钥对
* 如果直接連線到SFTP伺服器，您需要SFTP使用者端軟體

### 帮助文档 {#helpful-docs}

* [登录 SFTP 服务器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)


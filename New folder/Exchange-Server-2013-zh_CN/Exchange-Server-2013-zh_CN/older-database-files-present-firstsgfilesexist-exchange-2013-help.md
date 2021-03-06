﻿---
title: '较旧的数据库文件 present_FirstSGFilesExist: Exchange 2013 Help'
TOCTitle: 较旧的数据库文件 present_FirstSGFilesExist
ms:assetid: 907faeb8-1c6d-49fc-95a1-417f415a9d79
ms:mtpsurl: https://technet.microsoft.com/zh-cn/library/ms.exch.setupreadiness.firstsgfilesexist(v=EXCHG.150)
ms:contentKeyID: 50491025
ms.date: 05/21/2018
mtps_version: v=EXCHG.150
ms.translationtype: MT
---

# 较旧的数据库文件 present\_FirstSGFilesExist

 

_**适用于：** Exchange Server_

_**上一次修改主题：** 2012-06-05_

此主题中的内容尚未针对 Microsoft Exchange Server 2013 进行更新。虽然尚未更新，但仍可能适用于 Exchange 2013。如果您仍需要帮助，请查看下面的社区资源。

遇到问题了吗？请在 Exchange 论坛中寻求帮助。 请访问以下论坛：[Exchange Server](https://go.microsoft.com/fwlink/p/?linkid=60612)、 [Exchange Online](https://go.microsoft.com/fwlink/p/?linkid=267542) 或 [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?linkid=285351)。

因为在目标安装路径中检测到了现有 Microsoft Exchange 数据库文件，所以 Microsoft® Exchange Server 2007 安装程序无法继续进行。

Exchange 2007 安装程序要求目标安装路径中不能存在 Microsoft Exchange 数据库文件。

要解决此问题，请从目标安装路径中删除所有现有文件，然后重新运行安装程序。

从目标安装路径中删除现有 Exchange Server 数据库文件

1.  在\&quot;我的电脑\&quot;或 Windows 资源管理器中，找到目标安装路径。
    
    > [!NOTE]
    > 默认情况下，数据库文件位于：<br />
    > &lt;systemDrive&gt;:\Program Files\Microsoft\Exchange Server\Mailbox\First Storage Group。


2.  用鼠标右键单击要删除的文件，然后选择\&quot;删除\&quot;。

3.  在\&quot;确认文件删除\&quot;对话框中，单击\&quot;是\&quot;。

4.  对目标安装路径中的所有文件重复步骤 2 和步骤 3。


---
description: 关于设备图中的链接共享。
seo-description: 关于设备图中的链接共享。
seo-title: 设备图中的链接共享
title: 设备图中的链接共享
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '557'
ht-degree: 0%

---


# 设备图中的链接共享{#link-sharing-in-the-device-graph}

关于设备图中的链接共享。

这些 [!DNL Device Graph] 公司与Adobe Experience Cloud设备合作社的不同成员共享确定性和概率性联系。 链接共享让Adobe变得 [!DNL Device Co-op] 如此强大。 它扩展了每个成员对与匿名人员相关的设备的了解，但前提是您以前至少见过该匿名人员的某个设备。

## 设备图形摘要审阅 {#section-7858e9f61b5644c981ffb53626fcc19d}

在入门之前，让我们花点时间来回顾一下工作方 [!DNL Device Graph] 式。 向发送数 [!DNL Device Co-op] 据的成员 [!DNL Device Graph]。 该 [!DNL Device Graph] 数据用于根据设备之间的确定性和概 [率性链接构建个人身份](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) 。 作为参 [!DNL Device Co-op] 加者，这些链接可让您深入了解已验证的用户、其他用户及其设备之间的关系。 下面部分，让我们看一下它的工作方式。

## 链接共享示例 {#section-cb410d827cf14f76bc9b0bd4d31ed767}

以下示例演示了设备合作社中链接共享的强大功能。 在此示例中，我们有2个虚构的公司，即新闻公司和财务公司。 两个公司都是成员 [!DNL Device Co-op]。 Person A是一个消费者，可登录或从多个设备浏览每个公司的网站。

![](assets/share1.png)

由于Person A已通过手机和平板电脑向新闻网站进行身份验证，因此新闻公司会使用消费者ID来识别他们。 它将该ID作为加 [!DNL Device Graph] 密哈希发送给。 财务公司以前见过这些设备，但人员A没有登录到该网站。 因此，财务公司不知道这些设备是否彼此相关或如何相关，也不知道它们与人员A的关联。

![](assets/share2.png)

给定消费者ID的加密哈希， [!DNL Device Graph] 识别这些设备彼此和特定人相关。 对于不参与这些网站访问 [!DNL Device Co-op] 的公司来说，这些网站访问似乎来自单独的随机设备。 无论如何，一旦获得 [!DNL Device Graph] 散列ID，它：

* 知道手机和笔记本电脑是链接的。
* 认识到财务公司希望了解移动电话和笔记本电脑是否关联。

鉴于这些条件，现 [!DNL Device Graph] 在与财务公司共享连接这些设备的链接。 在此过程中，重复 [!DNL Device Graph] 和共享一个合作社成员与另一个合作社成员之间的链接。

![](assets/share3.png)

此时，成功 [!DNL Device Graph] 执行了其角色。 新闻公司和金融公司都清晰地了解了自己的身份。 他们可以跨所有设备准确地联系Person A。

## 隐私和链接共享 {#section-7b566018b3304420a4b3e4c079826110}

在整个链接共享过程中，维护会 [!DNL Device Co-op] 员的消费者隐私和数据完整性至关重要。 在此客户识别和链接共享过程中， [!DNL Device Graph] 没有：

* 告诉财务公司，链接来自新闻公司。
* 将一个成员使用的客户ID [!DNL Device Co-op] 与另一个共享。
* 提供除移动设备和笔记本电脑共享一个公共链接之外的任何信息。

## 后续步骤 {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

阅读有关身份、链接和链接共享的文档，您应该能够很好地了解数据在内 [!DNL Device Graph] 部的汇集方式。 下一步，我们建议查看我们的文档，其中描述了设备协作成员 *`known device`* 的跨设备链接的概念。 请参 [阅已知设备](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 和 [未知设备](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)。

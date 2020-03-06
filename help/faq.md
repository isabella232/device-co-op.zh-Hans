---
description: 有关身份服务协作和身份图表的常见问题描述和解答
seo-description: 有关身份服务协作和身份图表的常见问题描述和解答
seo-title: 常见问题解答
title: 常见问题解答
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# 常见问题解答{#faq}

有关身份服务协作和身份图表的常见问题描述和解答

**什么事[!DNL Device Co-op]?**

Device Co-op是一个数字合作社，可让参与其中的Adobe Experience Cloud客户通力协作，以更好地识别不同设备上的消费者。

**设备协作采用了哪些技术？**

设备协作包含两种技术：

* **Experience Cloud ID服务：** Adobe Experience Cloud的这项核心服务提供了一个通用ID，可跨解决方案、渠道、体验和设备一致地识别消费者。
* **Adobe Experience Cloud Device Co-op:** 该技术将消费者或家庭使用的不同设备连接在一起。

**如何工[!DNL Device Co-op]作？**

由于用户跨设备进行匿名登录和网站访问令品牌感到困惑，因此 Adobe 对此数据进行处理，以形成能够代表未知人员所用设备群组的设备群集。这些设备群集将会提供给设备协作成员，并用于为他们的消费者提供更为优质、更加一致的跨设备体验。

**如何链接[!DNL Device Co-op]设备？**

See [Deterministic and Probabilistic Links](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**参加者提供哪些数据[!DNL Adobe]?**

请参阅[消费者退出工具、隐私和设备图表](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be)。

**成员之间共享哪些[!DNL Device Co-op]数据？**

See [Link Sharing in the Device Graph](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**会员[!DNL Device Co-op]能否看到以前从未见过的设备的链接？**

否。设备协作成员只能获得访问过他们某个品牌网站资产的设备数据。请参阅 已知 [设备](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 和 [未知设备](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)。

**我需要共享本公司的任何营销信息吗？**

否。品牌只会向 Adobe 提供匿名设备数据。

**是否[!DNL Adobe]在中使用个人识别信息(PII)[!DNL Device Co-op]?**

否。所有个人身份信息在导入任何 Adobe 系统之前都会经过哈希加密，因此您客户的信息绝不会传递到 Adobe 系统。

**与较大的品牌相比，向设备协作贡献较少设备数据的小品牌是否会获得更多的价值？**

否。所有协作成员收到的价值与付出成正比。例如，如果某个品牌贡献了 10,000 个设备，他们将收到与这 10,000 个设备关联的其他链接设备信息。从宏观层面看，这种贡献可能微不足道，但随着各种规模的品牌不断加入，总体贡献越来越多，并将提供许多其他较大品牌想要了解的许多设备的缺失链接。请参 [阅公平性和已知设备](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8)。

**如果某些国家/地区将 IP 地址视为个人信息，那么[!DNL Adobe]将如何管理 IP 地址？**

设备协作首先在美国和加拿大发行，这些地区并不会将 IP 地址视为个人信息。当设备协作在 IP 地址被视为个人信息的国家/地区发行时，将不使用 IP 地址。

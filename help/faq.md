---
description: 关于Identity Services Cooperative和Identity Graph的常见问题的说明和解答。
seo-description: 关于Identity Services Cooperative和Identity Graph的常见问题的说明和解答。
seo-title: 常见问题解答
title: 常见问题解答
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '491'
ht-degree: 1%

---


# 常见问题解答{#faq}

关于Identity Services Cooperative和Identity Graph的常见问题的说明和解答。

**什么 [!DNL Device Co-op]?**

设备合作社是一个数字合作社，供参与Adobe Experience Cloud客户通力合作，在不同设备上更好地识别其消费者。

**Device Co-op中使用了哪些技术？**

设备合作社包括两种技术：

* **Experience CloudID服务：** Adobe Experience Cloud的这一核心服务提供了一个通用ID，可以跨解决方案、渠道、体验和设备一致地识别消费者。
* **Adobe Experience Cloud设备合作社：** 该技术将消费者或家庭使用的不同设备连接起来。

**如何工 [!DNL Device Co-op] 作？**

当各品牌通过匿名登录和网站访问在跨设备的谜题中占据一席之地时，Adobe会处理这些数据，以形成设备群集，这些设备群集代表由未知人使用的一组设备。 这些设备群集将提供给设备合作社成员，并用于为其消费者提供更好、更一致的跨设备体验。

**链接设备 [!DNL Device Co-op] 如何？**

请参 [阅确定性和概率链接](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)。

**参加者提供哪些数据 [!DNL Adobe]?**

请参 [阅消费者选择退出工具、隐私和设备图表](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be)。

**成员之间共享哪些 [!DNL Device Co-op] 数据？**

请参 [阅设备图形中的链接共享](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf)。

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**会员能 [!DNL Device Co-op] 否查看到以前从未见过的设备的链接？**

否。设备合作社成员只能根据访问过其品牌Web资产之一的设备获取数据。 请参 [阅已知设备](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 和 [未知设备](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)。

**我是否需要共享我的公司的营销信息？**

否。品牌只向Adobe提供匿名设备数据。

**是否 [!DNL Adobe] 在中使用个人可识别信息(PII) [!DNL Device Co-op]?**

否。所有个人可识别信息在被引入任何Adobe系统之前都经过散列处理，因此您的客户信息永远不会被传输到Adobe系统。

**与较大的品牌相比，为Device Co-op贡献较少设备数据的小品牌是否比其投入的价值更高？**

否。合作社的所有成员都可以收回他们所投入的价值。 例如，如果一个品牌贡献了10,000台设备，他们将能够接收与这些10,000台设备相关的其他链接设备信息。 从大局看，这种贡献可能看起来微不足道；但随着越来越多不同规模的品牌加入其中，聚合的贡献是巨大的，并且将为许多其他品牌寻找的许多设备提供缺失的链接。 请参 [阅公平性和已知设备](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8)。

**如果某 [!DNL Adobe] 些国家／地区将IP地址视为个人信息，如何管理IP地址？**

设备合作计划首次在美国和加拿大发布，在加拿大，IP地址不被视为个人信息。 当在IP地址被视为个人信息的国家／地区发布合作社时，不会使用该IP地址。

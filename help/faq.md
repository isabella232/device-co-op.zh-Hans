---
description: 有关设备协作的常见问题解答（Identity Services Cooperative和Identity Graph）。
title: 设备协作常见问题解答
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: 399a4fe2d34957eafe8c4eebed465df8770a9239
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# 常见问题解答{#faq}

关于Identity Services Cooperative和Identity Graph的常见问题描述和回答。

**什么是 [!DNL Device Co-op]？**

Device Co-op是一个数字合作社，旨在帮助参与的Adobe Experience Cloud客户共同协作，以更好地识别跨设备的消费者。

**设备协作中使用了哪些技术？**

Device Co-op包含两种技术：

* **Experience CloudID服务：** Adobe Experience Cloud的这一核心服务提供了一个通用ID，用于跨解决方案、渠道、体验和设备以一致的方式识别消费者。
* **Adobe Experience Cloud设备协作：** 此技术可链接消费者或家庭使用的不同设备。

**如何 [!DNL Device Co-op] 工作？**

随着各大品牌通过匿名登录和网站访问来拼凑自己那部分跨设备拼图，Adobe会处理这些数据，以形成设备集群，设备集群代表了一组由未知人员使用的设备。 这些设备群集提供给设备协作成员，用于为其消费者提供更好、更一致的跨设备体验。

**如何 [!DNL Device Co-op] 链接设备？**

参见 [确定性和概率性链接](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**参与者提供哪些数据 [!DNL Adobe]？**

参见 [消费者选择退出工具、隐私和设备图](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**在之间共享哪些数据 [!DNL Device Co-op] 成员？**

参见 [设备图中的链接共享](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**可以 [!DNL Device Co-op] 成员是否看到以前从未见过设备的链接？**

不会。设备协作成员只能基于访问过其品牌的Web资产之一的设备获取数据。 参见 [已知设备](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 和 [未知设备](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**我是否需要共享我公司的任何营销信息？**

不会。Brands仅向Adobe提供匿名设备数据。

**Do [!DNL Adobe] 在中使用个人身份信息(PII) [!DNL Device Co-op]？**

不会。所有个人身份信息在进入任何Adobe系统之前都会经过哈希处理，因此客户的信息永远不会传输到Adobe系统。

**与较大的同类产品相比，那些向Device Co-op贡献的设备数据较少的较小品牌是否获得了更大的价值？**

不会。合作社的所有成员都获得了相对于他们投入的资源的价值。 例如，如果一个品牌贡献了10,000台设备，他们将能够接收与这10,000台设备相关的其他链接设备信息。 纵观全局，这一贡献可能看似微不足道；但随着越来越多不同规模的品牌加入其中，这一总体贡献将相当可观，并将为许多其他品牌（也许规模更大）正在寻找的设备提供缺失的链接。 参见 [公平性和已知设备](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**如何 [!DNL Adobe] 如果某些国家/地区将IP地址视为个人信息，是否管理IP地址？**

Device Co-op首先在美国和加拿大发行，这两个国家的IP地址不被视为个人信息。 在将IP地址视为个人信息的国家/地区发布合作时，将不使用IP地址。

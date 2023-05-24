---
description: 了解如何在Adobe Target活动中使用设备协作数据。
seo-description: Learn how to use Device Co-op data in Adobe Target activities.
seo-title: Target - A/B tests, multivariate tests, and experience targeting
title: Target - A/B测试、多变量测试和体验定位
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
exl-id: 6e630adf-faff-4fe4-b560-febd59964a5f
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---

# Target - A/B测试、多变量测试和体验定位{#target-a-b-tests-multivariate-tests-and-experience-targeting}

了解如何在Adobe Target活动中使用设备协作数据。

您可以在A/B测试、多变量(MVT)测试和体验定位活动中使用设备协作数据。 设备协作选项在活动创建期间对以下页面可用： [!DNL Goals & Settings] 中的页面 [!DNL Target] 三步引导式工作流。

您不能在以下位置在Automated Personalization活动、推荐活动或使用设备协作数据： [!DNL Adobe Analytics] 作为报表源(即 [!DNL Target] 和 [!DNL Analytics] 集成（称为A4T）。

>[!NOTE]
>
>确保您拥有所需版本的 `mbox.js`. 您可以使用任意版本的 `at.js`. 有关更多信息，请参阅 [会员资格要求](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## 无论使用什么设备，都交付相关内容 {#section-bba8d41e96914c82a6d267a54f776354}

营销人员希望向每位访客提供最相关的体验，而不管访客当前使用什么设备与其公司或品牌进行交互。

用户可通过多种不同的设备与同一公司或品牌进行交互：工作笔记本电脑、家庭计算机、iPad、iPhone、各种浏览器等。 如果您无法识别每个特定设备或浏览器被之前在其他设备或浏览器上与您的品牌进行交互的同一个人使用，则无法为该人提供一致且有针对性的体验。

使用Device Co-op ，可以将用户的各种设备标识为由同一用户使用。 当该用户看到包含 [!DNL Target] 活动（活动或目标内容） [!DNL Target] 可以确保用户看到与其他设备相同的体验。

## 按人员而不是访客分析Target活动 {#section-c25cf4f8483942d7836d60756235e62c}

营销人员想要分析 [!DNL Target] 活动由“人员”而不是“访客”进行。

每个人都可能通过设备和浏览器与同一公司或品牌进行交互，但如果没有设备协作，则每个单独的设备或浏览器都被视为单独的“访客”。 [!DNL Target] 报告。

按个别设备和浏览器查看报表，会将“访客”计数夸大为高于与公司或品牌进行交互的不同人员数量。 这些人通常在这些不同的设备和浏览器中仅转化一次，因此转化率将低于实际情况，因为一次转化将计入更多“访客”。

借助Device Co-op，内容交付和报告是在“人员”级别完成的，因此报告准确地显示了有多少不同的人员查看了活动以及有多少人员转化。

如果没有设备协作数据，您可能会确定某个特定活动是入选者；但是，由于使用设备协作进行报告更加准确，因此另一个活动可能会具有更高的转化率，从而成为入选者。

有关此概念的更多信息，请参阅 [Analytics：人员量度](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## 按活动使用设备协作数据 {#section-fb46fae482654023abb1a1e26564db9a}

营销人员可以选择为每个活动使用设备协作数据。 特定 [!DNL Target] 活动可能不适用于Device Co-op数据，例如：

* 适用于iPad上的用户的特定内容。

   首次查看iPad体验的用户将继续在其家庭计算机上查看该体验。

* 利率优惠仅适用于严格的访客区段。
* 产品仅允许在特定状态下广告（例如，具有许可证限制的保险单）。

当营销人员在中创建受众时 [!DNL Target]，如果受众不适用于启用了设备协作数据的活动，则会向他们发出警报。 相应的受众包括所有访客、新访客和回访访客。

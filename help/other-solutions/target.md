---
description: 了解如何在Adobe Target活动使用设备合作数据。
seo-description: 了解如何在Adobe Target活动使用设备合作数据。
seo-title: 目标- A/B测试、多变量测试和体验定位
title: 目标- A/B测试、多变量测试和体验定位
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '586'
ht-degree: 0%

---


# 目标- A/B测试、多变量测试和体验定位{#target-a-b-tests-multivariate-tests-and-experience-targeting}

了解如何在Adobe Target活动使用设备合作数据。

您可以在A/B测试、多变量(MVT)测试和体验定位活动中使用设备合作数据。 The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

您不能在Automated Personalization活动、推荐活动或活动中使用设 [!DNL Adobe Analytics] 备合作数据作为报告源 [!DNL Target] ( [!DNL Analytics] 和集成，称为A4T)。

>[!NOTE]
>
>确保您拥有所需的版本 `mbox.js`。 您可以使用的任何版本 `at.js`。 有关详细信息，请参阅 [会员资格要求](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43)。

## 提供相关内容，无论使用何种设备 {#section-bba8d41e96914c82a6d267a54f776354}

营销人员希望为每位访客提供最相关的体验，而不管访客当前使用何种设备与其公司或品牌进行互动。

用户与来自许多不同设备的相同公司或品牌进行交互：工作用笔记本电脑、家用计算机、iPad、iPhone、各种浏览器等。 如果您无法识别之前在其他设备或浏览器上与您的品牌互动的同一个人正在使用每个特定设备或浏览器，则无法向该人提供一致且有针对性的体验。

通过设备合作社，用户的各种设备可标识为由同一用户使用。 当用户看到包含活动的页 [!DNL Target] 面(活动或目标内容)时， [!DNL Target] 可以确保用户看到在其他设备上看到的相同体验。

## 按人员而非目标分析活动 {#section-c25cf4f8483942d7836d60756235e62c}

营销人员希望按 [!DNL Target] “人”而非“访客”分析活动。

每个人可能会跨设备和浏览器与同一公司或品牌进行交互，但如果没有设备合作计划，每个设备或浏览器在报告中都会被视为单独的“访客” [!DNL Target] 。

按个别设备和浏览器查看报告会将“访客”计数放大到比与公司或品牌交互的不同人数更多的数字。 这些人通常只在这些不同设备和浏览器之间进行一次转化率，因此访客将低于实际，因为单次转换需要计算更多的“”。

借助设备合作社，内容投放和报告在“人员”级别进行，因此报告可以准确地显示有多少不同的人看到了活动以及有多少人转化了。

如果没有设备合作活动，您可以确定特定客户是赢家；但是，由于报告在设备合作社方面更加准确，因此其他活动实际上可能拥有更高的转化率，因此成为赢家。

有关此概念的更多信息，请参阅 [分析：人员指标](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63)。

## 按活动使用设备合作数据 {#section-fb46fae482654023abb1a1e26564db9a}

营销人员可以选择按活动使用设备合作社数据。 某 [!DNL Target] 些活动可能不适合设备合作社数据，例如：

* 适用于iPad上用户的特定内容。

   首先在iPad上视图体验的用户将继续在家用计算机上查看该体验。

* 利率优惠仅适用于严格访客。
* 仅允许在特定状态下发布产品（例如，具有许可限制的保险单）。

当营销人员在中创建受众 [!DNL Target]时，如果受众不适用于支持设备合作社数据的活动，则会提醒他们。 适当的受众包括所有访客、新访客和返回访客。

---
description: 了解如何在Adobe Target活动中使用设备协作数据。
seo-description: 了解如何在Adobe Target活动中使用设备协作数据。
seo-title: 目标- A/B测试、多变量测试和体验定位
title: 目标- A/B测试、多变量测试和体验定位
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Target - A/B tests, multivariate tests, and experience targeting{#target-a-b-tests-multivariate-tests-and-experience-targeting}

了解如何在Adobe Target活动中使用设备协作数据。

您可以在A/B测试、多变量(MVT)测试和体验定位活动中使用设备协作数据。 The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

您不能在以下活动中使用设备协作数据：自动个性化活动、推荐活动，或者将 [!DNL Adobe Analytics] 用作报表源的活动（例如 [!DNL Target] 和 [!DNL Analytics] 集成，即 A4T）。

>[!NOTE]
>
>Ensure that you have the required version of `mbox.js`. 您可以使用任意版本的 `at.js`。有关详细信息，请参阅会 [员资格要求](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43)。

## Deliver relevant content regardless of the device {#section-bba8d41e96914c82a6d267a54f776354}

营销人员希望向每位访客提交相关度最高的体验，而不考虑访客当前用来与营销人员公司或品牌进行交互的设备。

用户从许多不同设备（例如工作笔记本电脑、家用计算机、iPad、iPhone、各种浏览器等）与同一个公司或品牌进行交互。如果您无法识别之前在其他设备或浏览器上与您的品牌进行交互的同一个人员使用的每个特定设备或浏览器，您将无法向该人员提供一致的定位体验。

使用设备协作后，可以将用户的不同设备识别为同一个用户使用。When that user sees a page with [!DNL Target] activities—either activities or targeted content— [!DNL Target] can ensure that the user sees the same experience seen on another device.

## Analyze Target activities by people instead of by visitors {#section-c25cf4f8483942d7836d60756235e62c}

Marketers want to analyze [!DNL Target] activities by “people” instead of “visitors.”

Each person is likely interacting with the same company or brand across devices and browsers, but without the Device Co-op, each individual device or browser is considered a separate “visitor” in [!DNL Target] reports.

按单个设备和浏览器查看报表可能会夸大“访客”计数，所得人数大于与公司或品牌进行交互的不同人数。这些人员通常通过不同设备和浏览器仅转换一次，因此转换率将会低于实际情况，因为很多“访客”被计为一次转换。

使用设备协作后，内容提交和报告是在“人员”级别完成的，因此报表可以准确显示查看活动的人数和转换人数。

虽然在没有设备协作数据的情况下，您也可以确定哪个活动是入选方；但在使用设备协作后，报表更加准确，另一个活动的转换率实际上可能更高，因此这个活动才是入选方。

有关这个概念的更多信息，请参阅 分 [析：人员指标](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63)。

## Use Device Co-op data per activity {#section-fb46fae482654023abb1a1e26564db9a}

营销人员可以选择使用每个活动的设备写作数据。Certain [!DNL Target] activities might not be appropriate for Device Co-op data, such as:

* 适合 iPad 用户访问的特定内容。

   对于首先在 iPad 上查看体验的用户，在家用计算机上仍可以感受到相同的查看体验。

* 仅适用于严格访客区段的利率选件。
* 仅允许在特定情况下宣传广告的产品（例如，具有许可限制的保险单）。

当营销人员在 [!DNL Target] 中创建受众时，如果受众不适用于开启设备协作数据的活动，则营销人员会收到警报。适用受众包括所有访客、新访客和回访访客。

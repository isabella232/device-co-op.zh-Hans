---
keywords: Adobe Experience Cloud;Adobe Experience Cloud；设备协作；设备协作；生命周期终止
title: 设备协作生命周期终止常见问题解答
description: 了解设备协作的生命周期终止计划。
exl-id: 015ba95c-0c8d-415e-969c-b8670494de98
source-git-commit: c19e8425d5d6c2498186c19929907d2ee5327b31
workflow-type: tm+mt
source-wordcount: '1017'
ht-degree: 2%

---

# 设备协作生命周期终止常见问题解答

本文档对有关Adobe Experience Cloud设备协作生命周期终止(EOL)计划的常见问题解答进行了解答。 此计划生效后，Adobe将在[Experience Cloud发行说明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=zh-Hans)和[优先产品更新](https://www.adobe.com/cn/subscription/priority-product-update.html)中提供高级通知。

## 常见问题解答

以下是有关[!DNL Device Co-op] EOL计划的常见问题解答列表。

## 为什么[!DNL Device Co-op]被弃用？

AdTech环境即将发生的变化预计会导致[!DNL Device Co-op]在未来几年中成为过时的解决方案。 [!DNL Device Co-op] 由第三方Cookie组成， [!DNL Google's] 并宣布他们将在2022年之前阻止第三 [!DNL Google Chrome] 方Cookie，这将降低 [!DNL Device Co-op]其有效性。[!DNL Chrome] 拥有约65%的浏览器市场份额，其他主要浏览器已经实施了阻止第三方Cookie的功能。在[!DNL Chrome]阻止第三方Cookie后，大多数第三方Cookie都将被阻止，并且[!DNL Device Co-op]将被弃用。

## 为什么Adobe现在要结束[!DNL Device Co-op]注册？

注册即将结束，以防由于即将发生的关于第三方Cookie的行业变化而无法满足客户期望的风险。 [!DNL Device Co-op] 需要几个月时间才能准备好，还需要几个月时间才能从服务中获取价值。此时任何进一步注册都可能会导致品牌无法体验[!DNL Device Co-op]的完整值。

## 新客户能注册吗？

自2021年6月11日起，Adobe将不再接受新的[!DNL Device Co-op]注册。

## 现有合同是否正在续订？

自2021年6月11日起，Adobe将不再续订[!DNL Device Co-op]合同。 如果您希望继续使用[!DNL Device Co-op]服务，则可以继续按照当前许可条款使用，直到程序结束。

## [!DNL Device Co-op]程序的确切结束日期是多少？

[!DNL Device Co-op]程序将于2022年结束。 具体时间和日期取决于[!DNL Google]开始阻止第三方Cookie的时间。

## 设备协作终止后，哪些应用程序将受到影响？

[!DNL Device Co-op]生命周期终止过程将影响以下应用程序：

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=en)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## 作为[!DNL Device Co-op]的替代选项，我有哪些选项？

### [!DNL Analytics]

您可以使用[!DNL Analytics] [跨设备分析(CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html)功能，因为它同时支持Adobe Experience Platform Identity服务[专用图](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en)和[基于字段的拼合](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en)。

### [!DNL Audience Manager]

[!DNL Audience Manager] 与第三方设备图形合作伙伴(包括 [!DNL LiveRamp] 和 [!DNL Tapad])保持集成，但您必须直接与图形合作伙伴建立商业关系，才能利用 [!DNL Audience Manager]。

### [!DNL Real-time Customer Data Platform]

没有修改当前[!DNL Audience Manager Data Management Platform](DMP)的计划。 但是，弃用第三方Cookie可能会为大多数DMP用户带来规模挑战。 为帮助客户改进其数据管理做法，Adobe鼓励减少对标识符的依赖，这些标识符在来年将面临限制。 营销团队必须构建第一方数据策略，重点针对包含个人身份信息(PII)的持久标识符，可通过[!DNL Real-time Customer Data Platform]（实时CDP）解决该问题。

[!DNL Real-time CDP] 通过将可用于受众创建的标识符集扩展到包含PII，可减少对第三方Cookie和设备ID的依赖关系。[!DNL Real-time CDP]的基础是实时客户资料，它将人员属性数据与行为数据实时整合在一起，并允许营销人员使用获得专利的数据管理控制创建丰富的受众区段。 与[!DNL Audience Manager]类似，[!DNL Real-time CDP]支持分析和个性化用例，但也会生成更精细的人员级别分析，并可以将受众激活到范围更广的目标，这些目标包括广告技术和营销技术，包括付费媒体、社交媒体、电子邮件和客户系统。

[!DNL Real-time CDP] 还将包括访问 [Adobe Experience Platform区段匹配(Alpha)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en)，该功能允许品牌通过合作伙伴关系扩展自己的第一方数据集，并实现改进的分析和个性化。

### [!DNL Target]

目前没有可用于[!DNL Target]的替代方案，因为[!DNL Target]提供了确定性的跨设备身份拼合功能，称为`mbox3rdPartyId`，其功能与Adobe的客户ID类似。 此功能允许[!DNL Target]客户合并在集客渠道中进行的[!DNL Target]测试和个性化中的用户档案和活动参与情况。

### Adobe Advertising Cloud

[!DNL Advertising Cloud] 客户将无法再使用进 [!DNL Device Co-op] 行跨设备受众定位和测量。在[!DNL Advertising Cloud]中，您仍然能够利用Adobe与[!DNL LiveRamp]的[!DNL Device Graph]合作关系，在[!DNL LiveRamp’s]的能力和规模范围内继续执行这些功能。 您必须允许使用[!DNL Device Co-op]的营销活动结束，然后切换到[!DNL LiveRamp]设备图提供商，或不再利用基于人员的定位。

## 哪些现有功能和实施可以帮助我为无Cookie的未来做好准备？

您现有的访客ID服务实施支持Analytics [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html)。 如果您现有的声明ID是经过哈希处理的电子邮件，则可以使用它来增强以下功能：

- [!DNL Audience Manager] [基于人员的目标](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Experience Platform区段匹配(Alpha)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en)。

## 能否保留[!DNL Device Co-op]中的数据？

对于[!DNL Audience Manager]和[!DNL Advertising Cloud]用户，来自[!DNL Device Co-op]的数据将无法传输到第三方图表。 [!DNL Device Co-op] 只有使用CDA并切换到基 [!DNL Analytics Ultimate] 于字段的拼合的用 [!DNL Device Co-op] 户，才会迁移数据。所有其他解决方案都不会迁移其数据。

## 是否必须采用其他功能？

虽然不强制采用其他Adobe功能，但您应该尽快开始实施其他功能，以便在[!DNL Device Co-op]弃用之前留出时间和适当的协调。

## 如果我选择采用替代解决方案，我何时必须采用替代解决方案？

采用其他功能并非强制性的。 仅当您希望继续解决[!DNL Device Co-op]已解决的用例时，才建议您这样做。 如果您选择采用其他功能，则必须在2022年之前（确切时间要宣布）采用，[!DNL Device Co-op]程序才能结束。

## 收养需要多长时间？

这取决于功能。 例如，如果使用[!DNL Device Co-op]跨设备分析的Analytics Ultimate客户需要迁移到实时专用设备图或基于字段的拼合，则采用需要一些时间。

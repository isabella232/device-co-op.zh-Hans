---
keywords: Adobe Experience Cloud;Adobe Experience Cloud；设备协作；设备协作；生命周期终止
title: 设备协作生命周期终止常见问题解答
description: 了解设备协作的生命周期终止计划。
exl-id: 015ba95c-0c8d-415e-969c-b8670494de98
source-git-commit: ab45f8f54046a31e60223a36c374dc99dc968d7c
workflow-type: tm+mt
source-wordcount: '1079'
ht-degree: 4%

---

# 设备协作生命周期终止常见问题解答

本文档对有关Adobe Experience Cloud设备协作生命周期终止(EOL)计划的常见问题解答进行了解答。 此计划生效后，Adobe将在 [Experience Cloud发行说明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=zh-Hans) 和 [产品更新早知道](https://www.adobe.com/cn/subscription/priority-product-update.html).

## 常见问题解答

以下是关于 [!DNL Device Co-op] 终止计划。

## 为什么 [!DNL Device Co-op] 被弃用？

AdTech环境即将发生的更改预计会导致 [!DNL Device Co-op] 成为未来几年过时的解决方案。 [!DNL Device Co-op] 主要由第三方Cookie和 [!DNL Google's] 宣布他们将在 [!DNL Google Chrome] 到2022年， [!DNL Device Co-op]. [!DNL Chrome] 拥有约65%的浏览器市场份额，其他主要浏览器已经实施了阻止第三方Cookie的功能。 一次 [!DNL Chrome] 阻止第三方Cookie，则大多数第三方Cookie都将被阻止，并且 [!DNL Device Co-op] 会过时。

## 为什么Adobe结束 [!DNL Device Co-op] 现在注册？

注册即将结束，以防由于即将发生的关于第三方Cookie的行业变化而无法满足客户期望的风险。 [!DNL Device Co-op] 需要几个月时间才能准备好，还需要几个月时间才能从服务中获取价值。 此时，任何进一步注册都可能会导致品牌无法充分体验 [!DNL Device Co-op].

## 2022年7月，Google宣布将在Chrome上弃用第三方Cookie的时间推迟到2024年。 这会影响 [!DNL Device Co-op] EOL计划？

不，Adobe [!DNL Device Co-op] EOL计划将继续保持不变，不会延期。

## 新客户能注册吗？

自2021年6月11日起，Adobe将不再接受 [!DNL Device Co-op].

## 现有合同是否正在续订？

自2021年6月11日起，Adobe将不再续订 [!DNL Device Co-op] 合同。 如果您希望继续使用 [!DNL Device Co-op] “服务”，您可以继续根据当前许可条款执行此操作，直到程序结束。

## 确切的结束日期是什么 [!DNL Device Co-op] 程序？

的 [!DNL Device Co-op] 计划将于2022年结束。 具体时间和日期取决于 [!DNL Google] 开始阻止第三方Cookie。 退役工作预计于2022年9月开始。

## 设备协作终止后，哪些应用程序将受到影响？

以下应用程序将受 [!DNL Device Co-op] 生命周期终止程序：

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=en)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## 我有哪些选项作为 [!DNL Device Co-op]?

### [!DNL Analytics]

您可以使用 [!DNL Analytics] [跨设备分析(CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) 功能，因为它同时支持Adobe Experience Platform Identity服务 [专用图](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en) 和 [基于字段的拼合](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en).

### [!DNL Audience Manager]

[!DNL Audience Manager] 维护与第三方设备图合作伙伴的集成，包括 [!DNL LiveRamp] 和 [!DNL Tapad]，但是您必须直接与图形合作伙伴建立商业关系，以便利用 [!DNL Audience Manager]. 所有客户都应更新任何协作配置文件合并规则，以使用 [!DNL Device Co-op.]

### [!DNL Real-time Customer Data Platform]

没有修改当前 [!DNL Audience Manager Data Management Platform] (DMP)。 但是，弃用第三方Cookie可能会为大多数DMP用户带来规模挑战。 为帮助客户改进其数据管理做法，Adobe鼓励减少对标识符的依赖，这些标识符在来年将面临限制。 营销团队必须构建第一方数据策略，重点针对包含个人身份信息(PII)的持久标识符，这些数据策略可通过 [!DNL Real-time Customer Data Platform] （实时CDP）。

[!DNL Real-time CDP] 通过将可用于受众创建的标识符集扩展到包含PII，可减少对第三方Cookie和设备ID的依赖关系。 基础 [!DNL Real-time CDP] 是“实时客户资料”，可实时将人员属性数据与行为数据整合在一起，并允许营销人员使用获得专利的数据管理控制创建丰富的受众区段。 赞 [!DNL Audience Manager], [!DNL Real-time CDP] 支持分析和个性化用例，但也会生成更精细的人员级别分析，并可以将受众激活到涵盖广告技术和营销技术（包括付费媒体、社交媒体、电子邮件和客户系统）的更广泛目标。

[!DNL Real-time CDP] 还将包括访问 [Adobe Experience Platform区段匹配（测试版）](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=en)，允许品牌通过合作伙伴关系扩展自己的第一方数据集，并实现改进的洞察和个性化。

### [!DNL Target]

目前没有可供使用的替代方案 [!DNL Target] 因为 [!DNL Target] 提供确定性的跨设备身份拼合功能，称为 `mbox3rdPartyId`，其功能与Adobe的客户ID类似。 此功能允许 [!DNL Target] 将用户档案和活动参与合并到 [!DNL Target] 测试和个性化。

### Adobe Advertising Cloud

[!DNL Advertising Cloud] 客户将无法再使用 [!DNL Device Co-op] 用于跨设备受众定位和测量。 使用 [!DNL Advertising Cloud]，您仍然能够利用Adobe [!DNL Device Graph] 与 [!DNL LiveRamp] 继续履行这些职能， [!DNL LiveRamp’s] 能力和规模。 您必须允许您的营销活动使用 [!DNL Device Co-op] 结束，然后切换到 [!DNL LiveRamp] 设备图提供商，或不再利用基于人员的定位。

## 哪些现有功能和实施可以帮助我为无Cookie的未来做好准备？

您现有的访客ID服务实施支持Analytics [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html). 如果您现有的声明ID是经过哈希处理的电子邮件，则可以使用它来增强以下功能：

- [!DNL Audience Manager] [基于人员的目标](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Experience Platform区段匹配（测试版）](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match/overview.html?lang=en).

## 我是否可以将数据从 [!DNL Device Co-op]?

对于 [!DNL Audience Manager] 和 [!DNL Advertising Cloud] 用户，数据来自 [!DNL Device Co-op] 将无法传输到第三方图表。 [!DNL Device Co-op] 数据将仅迁移到 [!DNL Analytics Ultimate] 将CDA与 [!DNL Device Co-op] 切换到基于字段的拼合。 所有其他解决方案都不会迁移其数据。

## 是否必须采用其他功能？

虽然不强制采用其他Adobe功能，但您应尽快开始实施其他功能，以便在 [!DNL Device Co-op] 弃用。

## 如果我选择采用替代解决方案，我何时必须采用替代解决方案？

采用其他功能并非强制性的。 仅当您希望继续解决由 [!DNL Device Co-op]. 如果您选择采用其他功能，则必须在2022年之前（确切时间要公布）实施，然后才能在 [!DNL Device Co-op] 程序结束。

## 收养需要多长时间？

这取决于功能。 例如，如果Analytics Ultimate客户在 [!DNL Device Co-op] 需要迁移到实时专用设备图或基于字段的拼合，采用将需要一些时间。

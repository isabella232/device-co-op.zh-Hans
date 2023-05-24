---
description: 在开始使用Experience Cloud设备协作之前，您的公司必须满足这些最低标准。
seo-description: Your company must meet these minimum standards before you can start using the Experience Cloud Device Co-op.
seo-title: Membership requirements
title: 会员资格要求
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
exl-id: 923ce9c5-7716-4c5a-95f2-05a81a05c9cf
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '415'
ht-degree: 17%

---

# 会员资格要求{#membership-requirements}

在开始使用Experience Cloud设备协作之前，您的公司必须满足这些最低标准。

## 要求 {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

与您的 [!DNL Adobe representative to get started]. 如果Adobe确定潜在客户参与设备协作可能(1)违反了任何适用的法律；或(2)对Experience Cloud或其任何客户的安全或运营造成重大风险，则Adobe保留拒绝任何潜在客户加入Adobe设备协作的权利。

## Experience Cloud要求 {#section-76218a50385d43e6b9323e49f598394a}

您必须启用 [!DNL Adobe Experience Cloud] 并使用以下解决方案和服务来参与协作。

**解决方案**

申请人必须至少使用以下项之一 [!DNL Adobe]解决方案：

* [Analytics](http://www.adobe.com/cn/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/cn/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/cn/marketing-cloud/testing-targeting.html)

**核心服务**

申请人必须执行 [Experience CloudID服务](https://docs.adobe.com/content/help/zh-Hans/id-service/using/home.html).

## Adobe代码库要求 {#section-931a3fca1ce54afd90b88ba032e75f05}

下表列出了各种组件使用的代码库或SDK的最低版本 [!DNL Experience Cloud] 解决方案和服务。 如果您使用任何此代码并希望参与设备协作，请确保您满足以下最低要求。

>[!TIP]
>
>作为最佳实践，我们建议您使用最新的代码版本，而不是使用要求的最低版本。

**AppMeasurement(Flash)**

需要版本4.1。参见 [AppMeasurement for Flash、Flex和AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement (JavaScript)**

需要版本1.5.4。参见 [AppMeasurement for Flash、Flex和AIR](https://docs.adobe.com/content/help/zh-Hans/analytics/implementation/js/migrate-from-hcode.html).

**Mobile SDK**

移动SDK最低要求：

* Android 版本 4.8.3.
* iOS 版本 4.8.5.

必须为启用SDK代码 [!DNL Experience Cloud] ID服务。 为您中的每个应用程序启用并下载最新的SDK代码 [Adobe移动服务](https://mobilemarketing.adobe.com/) 帐户。 参见 [配置SDK访客ID服务选项](https://docs.adobe.com/content/help/zh-Hans/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

对于每个SDK，使用相应的 `visitorSyncIdentifier` 方法满足您的需求。 请参阅：

* [AndroidExperience CloudID服务方法](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOSExperience CloudID服务方法](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

需要版本1.5.4。

[!DNL Analytics] 客户可以从以下位置下载VisitorAPI.js库： [!DNL Code Manager]. 它位于JavaScript（新）或JavaScript（旧）文件中。 联系人 [客户关怀](https://helpx.adobe.com/cn/marketing-cloud/contact-support.html) 如果您无权访问 [!DNL Code Manager].

**Target库**

需要以下任一项 [!DNL Target] JavaScript库：

* at.js（任何版本）
* mbox.js版本58或更高版本

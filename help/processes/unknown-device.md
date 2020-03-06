---
description: 当个人设备未与您的品牌进行交互时，这些设备被称为“未知设备”。
seo-description: 当个人设备未与您的品牌进行交互时，这些设备被称为“未知设备”。
seo-title: 未知设备
title: 未知设备
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371

---


# Unknown devices{#unknown-devices}

当个人设备未与您的品牌进行交互时，这些设备被称为“未知设备”。

## Unknown device categories {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

设备被视为“未知”的方法或类别有以下几种，包括：

* **对其他设备合作成员的第一方访问：** 访问其他会 [!DNL Device Co-op] 员站点或向设备投放广告本身并不会使设备成为您品牌的已知设备。

* **未跟踪的广告存货：**&#x200B;对于已可用但尚未提供服务或录入数据的广告存货，不会将设备转变为您的品牌已知的设备。
* **消费者退出：**&#x200B;为了尊重消费者的愿望，不会将已经退出的设备视为已知设备。

与已知设备不同，未知设备不会与其他设备链接或与个人关联。

## Rules for setting known/unknown status {#section-fa5c85e59e2d4f88bb79f27f17f02344}

The [!DNL Device Graph] tries to be inclusive as possible when classifying devices as known compared to unknown. 这些规则有助于按优先级顺序（1 为最高级）确定已知/未知状态，如下所示：

* **规则 1：**&#x200B;设备是否已退出？如果是，则该设备属于未知设备。
* **规则 2：**&#x200B;是否已通过任何方法认识设备？**&#x200B;如果是，则该设备是已知设备。

* **规则3:**如果前一个不适用，则设备未知。

>[!MORELIKETHIS]
>
>* [已知设备](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)


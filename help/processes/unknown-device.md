---
description: 当个人使用的设备不用于与您的品牌交互时，这些设备称为未知设备。
seo-description: When a person has devices that are not used to interact with your brand, those devices are called unknown devices.
seo-title: Unknown devices
title: 未知设备
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
exl-id: 7841bf32-7327-4981-86a2-600e2bfe5901
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---

# 未知设备{#unknown-devices}

当个人使用的设备不用于与您的品牌交互时，这些设备称为未知设备。

## 未知的设备类别 {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

您可以通过多种方式或类别将设备视为“未知”。 其中包括：

* **对其他设备协作成员的第一方访问：** 访问其他 [!DNL Device Co-op] 成员网站或设备广告本身不会使您的品牌了解设备。

* **未跟踪的广告库存：** 可用但尚未提供或摄取的广告库存不会使您的品牌知道某个设备。
* **消费者选择退出：** 为了尊重消费者的需求，已选择禁用的设备不被视为已知设备。

与已知设备不同，未知设备未链接到其他设备或与个人相关联。

## 设置已知/未知状态的规则 {#section-fa5c85e59e2d4f88bb79f27f17f02344}

此 [!DNL Device Graph] 在将设备分类为“已知”与“未知”时，尽量使其具有包容性。 帮助确定已知/未知状态的规则按优先级顺序（1最高）工作，如下所示：

* **规则1：** 设备是否已选择禁用？ 如果是，则表示设备未知。
* **规则2：** 设备是否由所知 *任意* 方法？ 如果是，则表示设备已知。

* **规则3：**如果上一规则不适用，则表示设备未知。

>[!MORELIKETHIS]
>
>* [已知设备](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)


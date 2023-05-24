---
description: 关于设备图中的已知设备。
seo-description: About known devices in the Device Graph.
seo-title: Known devices
title: 已知设备
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
exl-id: 4eaf104f-022b-447b-8ce2-f0d0d1177cdf
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '562'
ht-degree: 1%

---

# 已知设备{#known-devices}

关于设备图中的已知设备。

在设备图中，我们有 *`known device`*. 已知设备是客户用来与您的品牌进行交互的设备。

>[!NOTE]
>
>在 [!DNL Adobe Experience Cloud Device Co-op]，术语，例如 *`device`*， *`person`*， *`identity`* 等等。 都有特定的含义。 例如，“设备”可以指物理硬件（如手机或平板电脑）以及在该硬件上运行的应用程序。 请参阅 [术语表](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) 以了解定义。

## 使用已知设备支持目标 {#section-80deae33660e4280ac65c659ceff5601}

已知的设备概念支持一些对创建和维护有效的 [!DNL Device Co-op] 程序。 已知设备是指 [!DNL Device Co-op] 成员可通过与消费者的某些交互（例如，网站访问或使用移动应用程序）知晓相关信息。 根据这些操作， [!DNL Device Graph] 链接a的已知设备 [!DNL Device Co-op] 成员到由其他团队贡献的设备 [!DNL Device Co-op] 成员。 这些链接可以是 [确定性或概率](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931). 此优势 [!DNL Device Co-op] 成员，因为他们接收：

* 有关其已知设备的更多数据。
* 有关其他链接设备的新信息。

![](assets/known-device.png)

此 [!DNL Device Graph] 将不提供设备协作成员尚未看到的设备群集的信息。

## Device Co-op目标 {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

三个主要目标使 [!DNL Device Co-op]. 其中包括：

* **缩放：** 在各种用例之间共享最大数量的可能链接。
* **公平：** 确保 [!DNL Device Co-op] 其贡献相称的方式获得利益。

* **消费者信任：** 通过确保消费者跨设备体验涉及他们熟悉和信任的品牌，来保持和构建消费者信心。

## 扩展和已知设备 {#section-67f734109762457ca62ec306284ea082}

以下方法是设备被认定为已知设备的更常见方式。 基于这些方法， [!DNL Device Co-op] 成员几乎总是拥有至少1台已知设备。 这支持为的所有成员提供最大规模的目标 [!DNL Device Co-op].

**有机**

* 通过客户访问您的网站或使用您的应用程序。 这是对第一方数据的鉴别。
* 通过CRM系统中的载入客户。

**Marketplace**

* 从Audience Marketplace购买区段数据。
* 从第三方数据提供商购买数据。

**Advertising**

通过在拍卖中获取库存并将广告提供给设备来实现。 如果该广告包含 [!DNL Audience Manager] 像素。

## 已知设备和公平用例 {#section-0543188729d845d6b95db70b8b25e9f8}

董事会成员 [!DNL Device Co-op] 获得与其对 [!DNL Device Graph]. 为提供大量设备的公司 [!DNL Device Graph] 收到的链接多于只投稿几条的成员。 我们相信这能帮助我们 [!DNL Device Co-op] 对所有会员都是公平的。 让我们看一下它如何与下面描述的大型和小型用例一起使用。

**品牌A：大型用例**

在此示例中，品牌A每月有100个网站访客，并启动一个新的跨设备品牌营销活动。 为简单起见，假设 [!DNL Device Graph] 知道品牌A的所有访客都关联到了其他一台设备。 这意味着品牌A可以再连接100台设备。 此外， [!DNL Device Graph] 包含大约200个设备链接在一起。

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 已知设备/月 </th> 
   <th colname="col2" class="entry"> 从Device Co-op接收的链接设备 </th> 
   <th colname="col3" class="entry"> Campaign设备总数 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>100 </p> </td> 
   <td colname="col3"> <p>200 </p> </td> 
  </tr> 
 </tbody> 
</table>

**品牌B：小型用例**

在此示例中，品牌B每月有100个网站访客，并启动一个新的跨设备品牌营销活动。 为简单起见，假设 [!DNL Device Graph] 知道品牌B的所有访客已关联到其他50台设备。 这意味着品牌B可以访问150台设备。 此外， [!DNL Device Graph] 包含大约1,000个链接在一起的设备。

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 已知设备/月 </th> 
   <th colname="col2" class="entry"> 从Device Co-op接收的链接设备 </th> 
   <th colname="col3" class="entry"> Campaign设备总数 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>50 </p> </td> 
   <td colname="col3"> <p>150 </p> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>* [未知设备](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)


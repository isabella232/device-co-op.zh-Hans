---
description: “人员”量度是基于Adobe设备图的人员（或设备组）计数。 您可以应用“人员”量度以在Analysis Workspace中跨其设备识别访客。
seo-description: The People metric is the count of people (or groups of devices) based on Adobe's Device Graph. You can apply the People metric to identify visitors across their devices in Analysis Workspace.
seo-title: People metric
title: 人员指标
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
exl-id: e2e70461-19ab-49db-bd65-a3eb26c2d4a8
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '1374'
ht-degree: 4%

---

# 人员指标{#people-metric}

“人员”量度是基于Adobe设备图的人员（或设备组）计数。 您可以应用“人员”量度以在Analysis Workspace中跨其设备识别访客。

## 人员量度先决条件和注意事项 {#section-34551d0435fb4b3cb3fad736b7961541}

<table id="table_120F7EF50042485391E58B22DD00A2A8"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 先决条件或注意事项 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>设备协作 </p> </td> 
   <td colname="col2"> <p> 要使用“人员”指标，请成为 <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. 协作可标识人员的多个设备(或Experience CloudID)。 Analytics利用此信息来统计推断与品牌互动的人数。 此量度的准确性在5%以内。 </p> <p><b>地区</b>：Device Co-op目前仅在美国和加拿大提供。 因此，在评估“人员”量度时，您应将区段应用于仅过滤美国和加拿大数据的分析。 </p> <p>每周，设备图会计算一个新版本的co-op，并将其发布以供使用。 周二，系统会收集最新数据并发布图形的更新版本。 然后，Experience Cloud解决方案会使用最新版本的图表。 具体到对于Analytics，更改在星期三读入，处理更改通常需要1到2个工作日。 </p> <p> <p>重要信息：当图表每周更新时，它可能会影响人员量度历史记录。 换句话说，历史人员计数可能会随着图形的学习和更新而随着时间的推移而变化。 例如，如果您今天运行一个报表，该报表统计上个月的人员，然后在图表更新后的一周内运行同一报表，则历史人员计数可能会稍有变化。 </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 量度权限 </td> 
   <td colname="col2"> <p>只有在您已被授予访问权限的情况下，您才能使用“人员”量度。 管理员可以<a href="https://docs.adobe.com/content/help/en/analytics/admin/user-product-management/customize-report-access/groups-metrics.html" format="html" scope="external"> 自定义量度权限</a> （在管理工具中）。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 映射到IMS组织 </td> 
   <td colname="col2"> <p>将会为所有符合以下条件的报表包启用人员指标 <a href="https://docs.adobe.com/content/help/zh-Hans/core-services/interface/about-core-services/report-suite-mapping.html" format="html" scope="external"> 映射到IMSORG</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>分析项目/工具 </p> </td> 
   <td colname="col2"> <p>在中使用“人员”指标 <span class="wintitle"> Analysis Workspace</span>， <span class="wintitle"> Ad Hoc Analysis</span>， <span class="wintitle"> Report Builder</span>、和通过API。 您可以在要使用独特访客量度（包括计算量度）的任何位置使用该量度。 </p> <p>例如，创建一个按人员划分的收入量度来替换按独特访客划分的收入量度。 </p> <p>A <a href="https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html" format="html" scope="external"> 人员项目模板</a> 可用于开始使用Analysis Workspace中的“人员”指标。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>打开机器人规则 </p> </td> 
   <td colname="col2"> <p>Adobe建议您启用 <a href="https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/bot-removal/bot-rules.html" format="html" scope="external"> 机器人规则</a>，尤其是使用“人员”量度时。 </p> <p>当机器人爬取您的网站时，它会人为增加您的独特访客计数。 从报表包中删除机器人流量可更准确地衡量数字资产上的活动，包括独特访客和人员活动。 </p> <p>为此，请导航到 <span class="uicontrol"> 分析</span> &gt; <span class="uicontrol"> 管理员</span> &gt; <span class="uicontrol"> 报表包</span>. 选择正确的报表包，然后转到 <span class="uicontrol"> 编辑设置</span> &gt; <span class="uicontrol"> 常规</span> &gt; <span class="uicontrol"> 机器人规则</span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>分段注意事项 </p> </td> 
   <td colname="col2"> <p> 将区段与人员量度一起使用时，量度报表可能会显着低于预期。 </p> <p>参见 <a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local"> 将人员指标与区段结合使用</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## “人员”量度是什么？ {#section-89e2b8f5e80f480391449fc8d1117a6a}

“人员”指标是一个Analytics报表指标，可帮助您将设备归因于人员。 它提供了基于人员的营销视图，让您能够测量访客在其所有设备中的活动。 将其视为删除了重复数据的独特访客版本，您可以将“人员”量度用于分析，其中您之前使用了“独特访客”。

**设备是人**

在“人员”量度可用之前，人员（例如）可能会访问您的网站，在三个不同的设备上与促销活动或品牌互动并购买，即便是在几分钟内完成购买。 根据您的实施，Analytics可能会将每个设备报告为独特访客，并在30美元的购买中将10美元归因于3台设备。

通过“人员”量度，您可以准确地将那30美元的购买归因于一个人：

![](assets/people-centric-results.png)

**提高报表的准确性**

通过“人员”量度，您可以将多个设备视为单个实体。 以下Analysis Workspace项目显示“独特访客”报表和“人员”报表之间的比较提高了准确性：

![](assets/people_report.png)

并排比较人员和独特访客：

![](assets/people-report.png)

**定义**

<table id="table_F8171AF15DA64607B427E3739EF004D6"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 项目 </th> 
   <th colname="col2" class="entry"> 描述 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>人员 </p> </td> 
   <td colname="col2"> <p>“人员”量度基于这样一种理念，即消费者使用多种设备与您的品牌进行交互。 您对数据进行切片或分段得越多，同一人员在该数据切片中使用多个设备的机会就越小。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>独特访客 </p> </td> 
   <td colname="col2"> <p>例如，按日期或时间对数据切片得越多，“人员”与“独特访客”之间的差异就越小。 如果您想深入了解设备协作的整体影响，Adobe建议使用过去90天的日期范围 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>压缩 </p> </td> 
   <td colname="col2"> <p>通过简单的计算量度，您可以了解“人员”量度相对于“独特访客”的较小百分比。 单击上表中“压缩”旁边的信息图标，以查看如何创建此量度。 </p> <p>可以在其他计算指标中使用人员来替代“独特访客”。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 如何计算人员指标？ {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

下图显示了“人员”量度的计算方式，以及对于过去的同一报表日期范围，该量度如何随时间的推移而减少。

![](assets/people-calculations.png)

在本例中，假设有一组固定的访客。 如果您在过去的固定时间范围内运行报表，则会显示固定访客集。 如果设备图在第1周输出左侧图中显示的数据，则人数为90人。 一周后，在下次运行设备图后，会将新信息考虑在内。 如果你运行一个星期前做的报告，人数已经降到84人。 历史记录已更改，因为设备图提供了有关应将哪些设备分组到一起的新信息。

## 将人员指标与区段结合使用 {#section-d03525420dbe48379fd95b230ef05885}

如果将区段与“人员”量度一起使用，则量度结果可能会显着低于预期。 出现此问题的原因是，在分段中， *`person`* 容器。 分段使用访客容器，这是定义中最高级别的容器，基于设备，而不是基于人员。

此问题主要发生在使用“人员”量度栈叠区段时。

![](assets/people-stacked-segments.png)

栈叠区段会创建一个表示区段组合的新区段。 每当您执行以下操作时，都会出现栈叠区段：

* 将区段放在Analysis Workspace中的另一个区段上方。 (使用 *`And`* 运算符。)
* 应用包含 *`And`* 运算符。
* 在项目级别和表级别应用区段。
* 将虚拟报表包与其他区段结合使用。

例如，假设您将以下区段栈叠在“人员”量度上：

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

仅两个区段中符合条件的人数 *`using a single device`* 计数。 （人员量度不显示跨设备的合格人员数量。）

此外，使用 *`Or`* 在这种情况下，不建议使用运算符。 这样做会生成看到其中一方的人数，无法计算有多少人符合这两个区段的条件。

参见 [生成区段](https://docs.adobe.com/content/help/zh-Hans/analytics/components/segmentation/segmentation-workflow/seg-build.html) 有关更多信息，请参阅分段帮助。

## 设备类型 {#section-8ab378c84ff34574b9c20fecb3848a86}

当报表包包含来自多种设备类型的数据时，“设备协作”和“人员”量度在Adobe Analytics中的效果最佳。 例如，在同一报表包中组合Web和应用程序数据可使“人员”量度更强大和更有效。 数据中的设备交叉越多，将多个独特访客分组为单个人员的可能性就越大。

![](assets/people-device-types.png)

## Experience CloudID服务范围 {#section-bbf0098cac2e467289e7a644a1dea05c}

Device Co-op要求使用Experience CloudID (MCID)服务检测您的数字资产。 如果报表包中的数据包含大量未使用MCID的访客，则设备协作和人员量度的有效性会降低。

<!--
mcdc-people-metric-apply.xml
-->

在Analysis Workspace中，创建 [项目](https://docs.adobe.com/content/help/zh-Hans/analytics/analyze/analysis-workspace/build-workspace-project/t-freeform-project.html)，然后拖动 **[!UICONTROL People]** 量度到项目表：

![](assets/people-metric.png)

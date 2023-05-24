---
description: 设备图如何分析确定性和概率数据以构建将设备链接在一起的映射。
seo-description: How the Device Graph analyzes deterministic and probabilistic data to build a map that links devices together.
seo-title: Deterministic and probabilistic links
title: 确定性和概率性链接
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
exl-id: e9bd2b7a-7d39-425d-adbb-298944009fcc
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '845'
ht-degree: 0%

---

# 确定性和概率性链接{#deterministic-and-probabilistic-links}

设备图如何分析确定性和概率数据以构建将设备链接在一起的映射。

在 [!DNL Device Graph]，内部进程会构建一个标识层次结构，该层次结构将映射设备并将设备连接到各个匿名人员。 该图表的输出包含可用于定位的跨设备链接，以及选定Experience Cloud解决方案中公开的数据。 可与配合使用的Adobe解决方案 [!DNL Device Graph] 数据包括Analytics、Audience Manager、Media Optimizer和Target。

此 [!DNL Device Graph] 分析确定性和概率性数据，以构建将设备链接在一起的地图。 确定性数据根据经过哈希处理的登录信息将设备链接在一起。 概率数据根据IP地址和其他元数据等信息将设备链接在一起。 此 [!DNL Device Graph] 将链接的设备群集与匿名个人相关联。这些连接使数字营销人员能够联系到人，而不是设备。 在 [!DNL Device Graph]，设备的所有者是真实用户的匿名表示形式。 确定性链接和概率性链接都有助于构建用户身份的结构。

>[!NOTE]
>
>在Adobe Experience Cloud Device Co-op中，使用诸如 *设备*， *人员*、和 *身份* 都有特定的含义。 例如， *设备* 可以指物理硬件，例如手机或平板电脑，以及在该硬件上运行的应用程序。 请参阅 [术语表](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) 以了解定义。

## 什么是链接？ {#section-2df4c6f01eba49369993146df0661f13}

当我们谈论链接时，重要的是要牢记这些链接在 [!DNL Experience Cloud] 设备图。 在这种情况下，链接不是设备之间的物理连接。 相反，链接是设备图将不同设备与同一个未知人员关联起来的方式。 例如，假设我们有一部手机和一台桌面浏览器。 一旦设备图确定电话和浏览器由同一未知人员使用，即可认为这两台设备是“已链接”的。 正如您将在下面阅读的，设备图通过确定性链接和概率性链接来构建身份。 在设备图中，设备的所有者是一个真实人物的匿名代表。

## 确定性链接 {#section-33d41e828a674b398e36fe63da20ac09}

确定性链接基于身份验证事件（例如，从设备登录到站点）将设备与人员相关联。 此操作创建一个名为消费者ID的匿名标识符。 让我们看一看确定性链接的工作原理。 在此示例中，人员A通过其移动设备上的应用程序登录到新闻网站。 当天晚些时候，A个人再次登录，但这次是通过笔记本电脑上的浏览器登录。

![](assets/link1.png)

根据登录信息，设备图：

* 知道人员A已通过移动电话/应用程序和笔记本电脑/浏览器设备组合访问新闻网站。
* 将这些设备链接到人员A。
* 基于与匿名人员关联的链接设备构建身份。

![](assets/link2.png)

>[!NOTE]
>
>两者都不 [!DNL Adobe Experience Cloud Device Co-op] 或 [!DNL Device Graph] 接收此数据中的实际身份验证信息或个人身份信息(PII)。 董事会成员 [!DNL Experience Cloud Device Co-op]，将经过加密哈希处理的唯一使用者ID传递到设备图。 消费者ID表示图中的经过身份验证的用户，并保护消费者隐私。

## 概率链接 {#section-5f5aa755da984f9d851f7cb380262998}

概率链接根据特征和元数据，通过算法将设备连接到人员，例如：

* 浏览行为
* IP地址
* 操作系统
* IDFA和GAID标识符

让我们看一下概率链接是如何运作的。 在此示例中，人员A先在平板电脑上浏览新闻网站，随后又从台式计算机浏览。 浏览时，人员A未登录到新闻网站。 在每次单独访问期间，平板电脑和台式机共享相同的IP地址。

![](assets/link3.png)

基于此信息， [!DNL Device Graph] 评估两个设备之间的IP地址共享模式，如果结果表明这些设备属于人员A，则将这些设备链接在一起。最终结果是从算法概率计算中派生出的标识层次结构。

![](assets/link4.png)

在此示例中，设备图在使用两个设备访问同一新闻网站后链接了它们。 但是，设备不必出现在同一网站上即可链接。 为了说明这一点，假设此示例中的每个设备访问完全不同的网站。 此 [!DNL Device Graph] 算法仍然可以根据它们共享的IP地址并根据其他数据分析来建立概率链接。 此过程有助于使概率链接对于成员如此强大 [!DNL Experience Cloud] 设备协作。

## 这两种类型的数据都提供了价值 {#section-43d22d8c10634edcb261e7bda6fdf323}

确定性数据和概率性数据是相辅相成的。 相反，仅包含确定性数据的设备图只能让您有限地查看一个人的身份。 如果没有身份验证，设备图将无法告知您浏览网站的其他设备和人员。 概率数据可以建立这些连接，并帮助您访问未经身份验证的设备、人员和家庭。

但是，确定性数据也很重要。 例如，它可以通过消除在概率信号丰富和重叠的地方（例如，咖啡馆、图书馆、机场等）产生的虚假链接来改进概率决策。

对于这两种类型的数据，设备图为您提供了比单独使用其中任一类型更全面的人员身份描述。

![](assets/link5.png)

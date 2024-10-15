---
title: 準同型写像・同型写像・同型の定義
date: 2024-10-15
lastmod: 2024-10-15
author: Author Name
categories:
  - 代数学
  - 群論
tags:
  - 定義
draft: false
---

準同型写像の定義を解説します。

<!--more-->

## 前提知識

- [群の定義]({{< ref "def_group">}})

## 定義

{{% def "準同型写像・同型写像・同型" %}}
$G, H$を群とする。以下の条件を満たす写像$\phi: G \to H$を$G$から$H$への**準同型写像**という。

$$\forall g, g' \in G, \phi(g g') = \phi(g) \phi(g')$$

また、全単射な準同型写像を**同型写像**という。

$G$から$H$への同型写像が存在するとき、$G$と$H$は**同型**であるといい、$G \cong H$とかく。

{{% /def %}}

## 注意

- $f$が同型写像のとき、その$f$は全単射なので逆写像が$f^{-1}$存在するが、$f^{-1}$は自動的に準同型写像である。
- 準同型写像はしばしば**準同型**と略される。
- 環や体といった、群とは別の対象についても準同型写像が定義される。この混乱を避けるために、群の間の準同型を**群準同型**と呼ぶことも多い。
- $G$から$H$への準同型があっても、群$G$と$H$は**準同型であるとは言わない**。実は、$G$のすべての元を$H$の単位元へ移す写像は準同型なので、すべての２つの群の間には準同型写像が存在する。
- $G \cong H$の他に、$G \simeq H$や$G \approx H$と書かれることもある。
- 準同型のイメージは、$f$で送る操作と、$G$や$G'$における演算が交換可能（可換）であるということ。

## 参考文献
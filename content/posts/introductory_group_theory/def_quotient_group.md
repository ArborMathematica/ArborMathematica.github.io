---
title: 剰余群（商群）
date: 2024-10-15
categories:
  - 代数学
  - 群論
tags:
  - 定義
draft: false
---

商群（剰余群）の定義を解説します。

<!--more-->

## 前提知識

- [正規部分群の定義]({{< ref "def_normal_subgroup">}})
- [商集合の定義]({{< ref "def_quotient_set">}})

## 定義

{{% def "剰余群（商群）" %}}
$G$を群、$N$をその[**正規部分群**]({{< ref "def_normal_subgroup">}})とする。

$G$上の関係$\sim$を
$$g \sim g' :\iff g^{-1} g' \in N $$により定義すると、これは[同値関係]({{< ref "def_equivalence">}})となる。
この同値関係による[商集合]({{< ref "def_quotient_set">}})を$G/N$とかく。

$G/N$の上の演算を
$$[g][g'] = [gg']$$
で定める。これは代表元のとり方によらず、well-definedである。

さらに、この演算は[群の公理]({{< ref "def_group">}})を満たす。この演算のもとで$G/N$を群とみなしたものを$G$の$N$による**剰余群（商群）** という。

{{% /def %}}

## 注意

- この定義には、証明すべきことがいくつか含まれている。具体的には、以下の3つを示さなければならない。
  1. $\sim$が実際に同値関係であること。
  2. $G/N$上の演算がwell-definedであること。
  3. $G/N$上の演算が群の公理を満たすこと。
- $\sim$が同値関係であることは、$N$が$G$の部分群であれば成り立つ。演算のwell-definednessには正規部分軍である必要がある。
- $[g] \in G/N$をよく$gN$とかく。この記法を用いると、$G/N$の演算は
$$(gN) (g'N) = gg'N$$
とかける。
- 体論における商体は全く別の概念であることに注意。剰余群、商群は英語でquotient groupやfactor groupと言われるが、商体はfield of fractionsという。

## 参考文献

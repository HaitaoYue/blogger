---
title: 关于cello
date: 2018-01-26 22:01:23
description: 关于cello的一些介绍。
categories: hyperledger
tags: [hyperledger, cello, baas]
---

# 什么是cello?

{% link Cello在hyperledger官网的介绍信息 https://www.hyperledger.org/projects/cello cello在hyperledger官网的一些介绍信息 %}

一句话介绍，cello就是支持多元化基础设施的"区块链即服务"的管理和使用平台。
{% blockquote %}
底层可以支持在docker, docker swarm, bare metal, vmware, kubernetes部署。
{% endblockquote %}

# 为什么会产生cello这个项目？
1. hyperledger fabric部署门槛高
{% blockquote %}
现在区块链非常热，很多的开发者或是公司，都特别想开发自己的一套区块链应用，但是，hyperledger的这套环境的搭建和如何配置节点，证书的生成以及链路的初始化等等复杂度比较高，学习成本很高，所以，可能就会止步与环境的搭建。
{% endblockquote %}
2. baas的市场需求
{% blockquote %}
所有好的东西最根本的是内容，比如苹果手机，如果没有这么多的好的应用支撑，这么好的生态系统，也不会有用户买账。所以，我觉得区块链将来能否很好的发展，智能合约应用也是关键之一，所以，将来会有大量的开发者进入到智能合约的开发中来，虽然我现在还没有开始学习怎么开发智能合约。这样，就需一个这样的区块链即服务的快捷部署的平台，为开发者提供一个快速开发智能合约的通道。
{% endblockquote %}

# 设计图
## 架构图

{% asset_img arch.png 架构图 %}

## 网络拓扑图

{% asset_img network.png 网络拓扑图 %}

## 层次关系图

{% asset_img layer.png 层次关系图 %}

# PPT

{% asset_link Cello.pptx 下载 %}

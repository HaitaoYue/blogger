---
title: 版本v0.8.0-alpha发布
date: 2018-01-20 13:43:09
categories: release
tags: [hyperledger, cello, release]
---

# 版本说明

## 新特性

* Blockchain-Explorer support;
* Enable user dashboard, can apply chain, query block/transaction, upload/invoke/query chain code;
* Support v3 docker compose format;
* Support fabric 1.0.5;
* Support fabric with kafaka mode;
* Enable creating/hosting service images at dockerhub;

<!-- more -->

## 提升

* Use mongoengine instead of mongodb library for admin dashboard.

## 已知的问题

* Health check should ignore blockchain explorer port.
* Cluster's user_id should be empty when the chain is created.
* User dashboard does not support debug/product mode.

## 修改日志

{% link 链接 https://github.com/hyperledger/cello/blob/master/CHANGELOG.md#v080-alpha %}

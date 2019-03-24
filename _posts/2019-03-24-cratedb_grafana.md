---
layout: post

title: "cratedb+grafana搭建可承载大数据量的监控平台"

date: 2019-03-23

description: "cratedb安装，grafana监控配置"

tag: 博客

---

### 介绍

&ensp;&ensp; cratedb是分布式的、基于Elasticsearch的SQL数据库，存储数据量大，因为底层是ES（Elasticsearch简称，以下都称为ES），可以支持在几十亿行数据级别进行实时的模糊检索，比ES对SQL的支持得更好，支持联表查询join、聚合、搜索。

&ensp;&ensp;grafana是一套开源的可视化套件，可用于基于时间序列的数据展示，如项目中的监测数据、程序内存数据。运维同学常通过grafana+zabbix的组合进行资源的监控的可视化分析。

### 目标

&ensp;&ensp;学习cratedb、grafana的基本概念和使用，研究cratedb单节点承载的数据量大小、联表查询和grafana添加cratedb的方法。

### 安装

**在winodws上安装cratedb**


















---
layout: post

title: "Cratedb+Grafana搭建可承载大数据量的监控平台"

date: 2019-03-23

description: "Cratedb安装，Grafana监控配置"

tag: 博客

---

### 介绍

&ensp;&ensp; Cratedb是分布式的、基于Elasticsearch的SQL数据库，存储数据量大，因为底层是ES（Elasticsearch简称，以下都称为ES），可以支持在几十亿行数据级别进行实时的模糊检索，比ES对SQL的支持得更好，支持联表查询join、聚合、搜索。

&ensp;&ensp;Grafana是一套开源的可视化套件，可用于基于时间序列的数据展示，如项目中的监测数据、程序内存数据。运维同学常通过Grafana+Zabbix的组合进行机器资源监控的可视化分析。

### 目标

&ensp;&ensp;学习Cratedb、Grafana的基本概念和使用，研究Cratedb单节点承载的数据量大小、联表查询和Grafana添加Cratedb数据源的方法。

### 安装

**在Winodws上安装Cratedb**

&ensp;&ensp;在https://crate.io/download/ 下载Tarball.tar.gz，需要在jdk11及以上版本运行。在解压目录bin文件夹下运行crate.bat。

**在Centos上安装Cratedb**

### 使用

**使用Cratedb**

&ensp;&ensp;暂时没有linux云主机，先在本地进行使用。在浏览器上输入localhost:4200，访问管理界面。

![](/images/posts/cratedb_grafana/manager_main.png)







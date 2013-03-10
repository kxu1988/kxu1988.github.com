---
layout: post
title: "Ad Hoc网络基本概念"
description: ""
category: Ad hoc
tags: [Ad hoc]
---
{% include JB/setup %}

移动Ad hoc网络（Mobile Ad hoc network, MANET)由自主的、互助的无线节点组成，是一种自主创建、自动组织和自我管理的网络[2][3]。
Ad hoc网络最显著的特点是不依赖于固定的基础设施；可以在无网络基础设施可用的环境，或者在网络基础设置的覆盖范围外，快速组建网络。
由于移动Adhoc网络中的节点自主运动，因此网络的拓扑结构会发生不可预期的变化。
Ad hoc网络中的节点需要兼备路由器和移动终端两种功能：移动终端功能指的是运行应用程序；路由器功能指的是节点充当路由器运行相应的路由协议、参与分组转发和路由维护工作。移动节点具有路由功能，因此数据在Adhoc网络中传递可以通过直接传递的方式。此外，由于移动节点的通信覆盖范围有限，一些节点无法和某些节点直接通信。因此，移动Adhoc网络中的数据传播经常通过多个节点转发，即多跳连接的方式。与其它无线网络的多跳路山不同，移动Ad hoc网络中不需要专用的路由设备，而是利用普通节点来实现多跳路由
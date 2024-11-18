# One Map Playstyle

## [第零章：ISO 网络模型](docs/00-chapter_0.md)

- 介绍前三层网络的架构和基础概念。
- 解释前三层网络之间的通信原理。

## [第一章：Kubernetes 网络概述](docs/01-chapter_1.md)

- 1.1 Kubernetes 网络模型
  - 介绍 Kubernetes 的网络架构和基本概念。
  - 解释 Pod、Service 和网络策略之间的关系。
- 1.2 网络通信原理
  - 描述容器之间的通信方式。
  - 讨论网络命名空间和虚拟网络接口。

## [第二章：单机视角的容器网络栈](docs/02-chapter_2.md)

- 2.1 容器网络栈概述
  - 介绍容器如何使用 Linux 网络栈。
  - 描述容器与宿主机之间的网络交互。
- 2.2 网络命名空间
  - 深入讲解 Linux 网络命名空间的工作原理。
  - 展示如何在命名空间中配置网络。
- 2.3 虚拟网络接口
  - 介绍虚拟以太网对（veth pairs）的概念。
  - 演示如何创建和使用 veth 接口。

## [第三章：CNI（容器网络接口）](docs/03-chapter_3.md)

- 3.1 CNI 概述
  - 定义 CNI 的作用和重要性。
  - 讨论 CNI 插件的类型和功能。
- 3.2 常用 CNI 插件
  - 比较不同的 CNI 插件（如 Flannel、Calico、Weave）。
  - 展示如何安装和配置一个 CNI 插件。
- 3.3 CNI 的工作机制
  - 深入探讨 CNI 的工作流程，包括 Pod 创建时的网络配置过程。

## [第四章：Kubernetes Service](docs/04-chapter_4.md)

- 4.1 Service 的类型
  - 描述 ClusterIP、NodePort 和 LoadBalancer 的区别和使用场景。
- 4.2 Service 的工作原理
  - 深入讲解 Kubernetes 如何实现服务发现和负载均衡。
- 4.3 Headless 服务与 DNS
  - 讨论无头服务的概念及其在服务发现中的应用。

## 第五章：[Kubernetes DNS](docs/05-chapter_5.md)

- 5.1 DNS 在 Kubernetes 中的角色
  - 描述 Kubernetes 内置 DNS 的功能和重要性。
- 5.2 DNS 配置与使用
  - 展示如何配置和使用 Kubernetes DNS。
- 5.3 常见问题与故障排除
  - 列出常见 DNS 问题及其解决方案。

## [第六章：BGP（边界网关协议）](docs/06-chapter_6.md)

- 6.1 BGP 概述
  - 定义 BGP 的基本概念及其在互联网中的作用。
- 6.2 BGP 的工作原理
  - 深入探讨 BGP 路由选择过程及其算法。
- 6.3 在 Kubernetes 中使用 BGP
  - 描述如何在 Kubernetes 集群中配置 BGP，以实现跨节点路由。

## [第七章：BIRD](docs/07-chapter_7.md)

- 7.1 BIRD 概述
  - 简介 BIRD 软件及其在 BGP 中的应用。
- 7.2 BIRD 配置与管理
  - 展示如何安装和配置 BIRD，进行基本操作。
- 7.3 与 Kubernetes 集成
  - 描述如何将 BIRD 与 Kubernetes 集成，实现 Pod 路由广告。

## [第八章：案例研究与最佳实践](docs/08-chapter_8.md)

- 8.1 实际案例分析
  - 分析一些使用 Kubernetes 网络的实际案例，展示最佳实践。
- 8.2 故障排除与优化建议
  - 提供常见问题的解决方案和优化建议，以提高网络性能和可靠性。

## [第章：总结与展望](docs/09-chapter_9.md)

- 9.1 本书总结
  - 总结各章节要点，重申 Kubernetes 网络的重要性。
- 9.2 前景展望
  - 探讨未来 Kubernetes 网络的发展方向及新技术趋势。

## 附录

- 附录 A: 常用命令汇总
- 附录 B: 配置文件示例
- 附录 C: 故障排除指南

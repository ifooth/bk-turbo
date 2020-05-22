![LOGO](docs/resource/img/bkci_cn.png)
---
[![license](https://img.shields.io/badge/license-mit-brightgreen.svg?style=flat)](https://github.com/Tencent/bk-ci/blob/master/LICENSE) [![Release Version](https://img.shields.io/badge/release-0.0.1-brightgreen.svg)](https://github.com/Tencent/bk-ci/releases) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Tencent/bk-ci/pulls) ![Backend CI](https://github.com/Tencent/bk-ci/workflows/Backend%20CI/badge.svg?branch=master)

> **重要提示**: `master` 分支在开发过程中可能处于 *不稳定或者不可用状态* 。
请通过[releases](https://github.com/tencent/bk-ci/releases) 而非 `master` 去获取稳定的二进制文件。

bk-ci是一个免费并开源的CI服务，可助你自动化构建-测试-发布工作流，持续、快速、高质量地交付你的产品。

使用bk-ci屏蔽掉所有研发流程中的繁琐环节，让你聚焦于编码。它通常被用于：
- 工程编译
- 静态代码检查
- 运行测试用例，及时发现BUG
- 部署与发布

bk-ci提供了流水线、代码库、凭证管理、环境管理、研发商店5大核心服务，多重组合，满足企业不同场景的需求：
- **流水线**：将团队现有的研发流程以可视化方式呈现出来，编译、测试、部署，一条流水线搞定
- **代码库**：将企业内已有的代码托管服务关联至bk-ci
- **凭证管理**：为代码库、流水线等服务提供不同类型的凭据、证书管理功能
- **环境管理**：可以将企业内部的开发编译机托管至bk-ci
- **研发商店**：由流水线插件和流水线模板组成，插件用于对接企业内部的各种第三方服务，模板助力企业内部的研发流程规范化

## Overview
- [架构设计](docs/overview/architecture.md)
- [代码目录](docs/overview/code_framework.md)
- [设计理念](docs/overview/design.md)

## Features
- 持续集成和持续交付: 由于框架的可扩展性，bk-ci既可以用作简单的CI场景，也可以成为企业内所有项目的持续交付中心
- 所见即所得:  bk-ci提供了灵活的可视化编排流水线，动动指尖，将研发流程描述与此
- 架构平行可扩展: 灵活的架构设计可以随意横向扩容，满足企业大规模使用
- 分布式: bk-ci可以便捷的管控多台构建机，助你更快的跨多平台构建、测试和部署
- 流水线插件: bk-ci拥有完善的插件开发体系，其具备了低门槛、灵活可扩展等特性
- 流水线模板: 流水线模板将是企业内部推行研发规范的一大助力

## Experience
- [bk-ci in docker](https://hub.docker.com/r/blueking/bk-ci)

## Getting started
- [下载与编译](docs/overview/source_compile.md)
- [一分钟安装部署](docs/overview/installation.md)

## RoadMap
- [版本规划](docs/VERSION.md)
- [版本日志](version.md)

## Support
1. [wiki](https://github.com/Tencent/bk-ci/wiki)
2. [蓝鲸社区](https://bk.tencent.com/s-mart/community)
3. QQ群：744672165

## BlueKing Community
- [BK-BCS](https://github.com/Tencent/bk-bcs)：蓝鲸容器管理平台是以容器技术为基础，为微服务业务提供编排管理的基础服务平台。
- [BK-BCS-SaaS](https://github.com/Tencent/bk-bcs-saas)：蓝鲸容器管理平台SaaS基于原生Kubernetes和Mesos自研的两种模式，提供给用户高度可扩展、灵活易用的容器产品服务。
- [BK-CMDB](https://github.com/Tencent/bk-cmdb)：蓝鲸配置平台（蓝鲸CMDB）是一个面向资产及应用的企业级配置管理平台。
- [BK-PaaS](https://github.com/Tencent/bk-PaaS)：蓝鲸PaaS平台是一个开放式的开发平台，让开发者可以方便快捷地创建、开发、部署和管理SaaS应用。
- [BK-SOPS](https://github.com/Tencent/bk-sops)：蓝鲸标准运维（SOPS）是通过可视化的图形界面进行任务流程编排和执行的系统，是蓝鲸体系中一款轻量级的调度编排类SaaS产品。

## Contributing
- 关于 bk-ci 分支管理、issue 以及 pr 规范，请阅读 [Contributing](CONTRIBUTING.md)
- [腾讯开源激励计划](https://opensource.tencent.com/contribution) 鼓励开发者的参与和贡献，期待你的加入


## License
BK-CI 是基于 MIT 协议， 详细请参考 [LICENSE](LICENSE.txt)

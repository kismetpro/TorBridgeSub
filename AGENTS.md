# AGENTS.md

This file provides guidance to agents when working with code in this repository.

## 项目概述

- **这是一个数据仓库，而不是一个典型的软件项目。** 请不要尝试执行标准的构建、测试或 linting 命令，因为这些命令在这里不适用。
- 项目的核心是 [`output/WebTunnel.txt`](output/WebTunnel.txt:1) 文件，该文件包含了 Tor 网桥的订阅链接。

## 工作流程

- 与此仓库交互的主要任务是更新或使用 [`output/WebTunnel.txt`](output/WebTunnel.txt:1) 文件中的数据。
- 没有与代码相关的命令（如编译、测试等）。
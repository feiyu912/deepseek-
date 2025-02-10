# 本地部署deepseek，解决网络连接，ollama下载慢的问题
## 概述

DeepSeek 是一款开源的大语言模型，凭借其先进的算法架构，为 AI 对话交互带来了革新性的体验。通过本地部署，可以自由选择是否要使用网络，直接接入jetbrain旗下的软件中。

这里将完整介绍ollama下载，LM Studio下载，网络连接问题以及ollama直接下载过慢的问题。

## 前置准备

**硬件环境：**

- CPU >= 2 Core
- 显存/RAM ≥ 16 GiB（推荐）
- 以上是最低标准
- 附：本人使用的是14700kf， 3060 12g 以及32g内存，使用的是32b q4模型

## 开始部署

### 1. 安装 Ollama

[Ollama](https://ollama.com/) 是一款跨平台的大模型管理客户端（MacOS、Windows、Linux），旨在无缝部署大型语言模型 (LLM)，例如 DeepSeek、Llama、Mistral 等。Ollama 提供大模型一键部署，所有使用数据均会保存在本地机器内，提供全方面的数据隐私和安全性。

访问 [Ollama 官网](https://ollama.com/)，根据提示下载并安装 Ollama 客户端。安装完成后，在终端内运行 `ollama -v` 命令将输出版本号。

![](image/1.1png)





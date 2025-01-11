# Opentracker 二进制文件 / Opentracker Binaries

## 简介 / Introduction

本仓库包含基于开源 [Opentracker 项目](https://erdgeist.org/gitweb/opentracker/) 预编译的二进制文件。这些二进制文件让您能够快速部署 Opentracker，无需从源代码编译。

This repository contains precompiled binaries of Opentracker based on the open-source [Opentracker repository](https://erdgeist.org/gitweb/opentracker/). These binaries make it easy to quickly set up Opentracker without the need to compile from source.

## 特性 / Features

- 预编译的即用型二进制文件 / Precompiled and ready-to-use binaries
- 无需从源代码编译 / No need to compile from source
- 快速简便的服务器部署 / Fast and easy deployment on your server

## 安装说明 / Installation

### 系统要求 / Prerequisites
- Linux 系统服务器（如 Ubuntu、Debian 等）/ A Linux-based server (Ubuntu, Debian, etc.)
- 基本的终端使用知识 / Basic knowledge of how to use the terminal

### 安装步骤 / Installation Steps

1. 从 [Releases](https://github.com/bigcaibao/opentracker-binaries/releases) 页面下载预编译的二进制文件。
   Download the precompiled binary from the [Releases](https://github.com/bigcaibao/opentracker-binaries/releases) page.
   
2. 下载完成后，解压文件并运行：
   Once downloaded, extract the tarball or zip file and run:
   
   ```bash
   tar -xzvf opentracker-binaries.tar.gz
   cd opentracker
   chmod +x opentracker
   ./opentracker -f ./opentracker.conf
   ```

## 配置说明 / Configuration

您可以通过编辑 `opentracker.conf` 文件来配置 Opentracker。详细的配置选项请参考 Opentracker 官方文档。

You can configure Opentracker by editing the `opentracker.conf` file. Please refer to the official Opentracker documentation for detailed configuration options.

## 使用方法 / Usage

使用指定的配置文件启动 Opentracker：
To start Opentracker with a specific configuration file:

```bash
./opentracker -f /opentracker.conf
```


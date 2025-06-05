# RWKV模型部署指南

## ‌一、环境准备

### 1.系统配置
**服务器：** 鲲鹏服务器

**操作系统：** Huawei Cloud EulerOS 2.0 64bit

**硬件：**
CPU：2核

内存：4GB

存储：40GB

#### 2.软件依赖
Java：OpenJDK 11


## ‌二、下载

### EulerOS2.0

####1.下载安装
```bash
# 下载 v0.22.1 版本
wget https://github.com/kestra-io/kestra/archive/refs/tags/v0.22.10.tar.gz
# 解压文件
tar -zxvf kestra-0.22.1.tar.gz
cd kestra-0.22.1
```
####2.启动 Kestra
```bash
./bin/kestra server run
```
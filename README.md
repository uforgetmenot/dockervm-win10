# DockerKVM-Win10

## 准备工作

### 1. 解压系统镜像

首先需要将 Windows 10 系统镜像解压到当前目录：

```bash
tar -xzf win10.qcow2.tgz
```

解压完成后，当前目录应包含 `win10.qcow2` 文件。

### 2. 启动容器

使用 Docker Compose 启动 KVM 虚拟机：

```bash
docker compose up
```
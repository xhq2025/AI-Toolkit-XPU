# 更易用的 AI Toolkit-XPU版本（中文 README）

> 原项目作者：Ostris
> 
> AI-Toolkit-Easy2use项目作者：DocWorkBox
> 
> 本项目是基于[（I卡）AI-Toolkit安装教程｜ARC.AI.Next｜腾讯频道](https://pd.qq.com/g/mojr1c1n4v/post/B_6f843f69d1e10a001441152196989399570X60)  进行二次开发。

## 特别说明
- 项目用于intel显卡，其他类型显卡暂不支持。
- 测试设备：Arc A770 16G + 32G内存


## 项目简介

- 面向扩散模型（Diffusion Models）的训练与推理一体化工具。
- 支持常见的图像与视频模型，适配消费级硬件。
- 提供命令行（CLI）与 Web 用户界面（UI），上手门槛低同时功能完备。

## 环境要求

- Python ≥ 3.10
- Git（用于拉取仓库）
- Intel GPU（显存需满足你的训练或推理需求）
- Python 虚拟环境（建议）
- Node.js ≥ 18（用于运行 Web UI）

## 安装（Linux / Windows）

> 🐳 **推荐**：如需使用 Docker 快速部署，请查看 [Docker 部署指南](DOCKER_README.md)。

### 1）克隆仓库

```bash
git clone https://github.com/xhq2025/ai-toolkit-xpu.git
cd ai-toolkit-xpu
```

### 2）创建并激活虚拟环境

Linux / macOS：

```bash
python3 -m venv venv
source venv/bin/activate
```

Windows（PowerShell）：

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```


### 3）安装项目依赖
```bash
pip install -r requirements.txt
```

本仓库遵循原项目的许可证政策（如有变更将于此处更新）。请在商用或分发前确认模型及数据集的独立许可证要求。

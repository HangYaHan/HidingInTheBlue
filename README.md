# FPGA Video Image Processing Project

基于安路 FPGA `PH1P35MDG324` 的高清视频图像采集、处理与显示系统。

## 项目简介

本项目面向 FPGA 视频图像处理赛题，目标是基于指定开发板实现一套完整的视频处理链路，包括：

- MIPI 视频流输入与解码
- 视频数据缓存
- 图像处理与算法加速
- HDMI 高清显示输出
- 在基本功能基础上进行算法创新，例如：
  - 边缘检测
  - 图像增强
  - 卡通化
  - 目标识别
  - 机电联动控制

## 硬件平台

- FPGA: `PH1P35MDG324`
- Vendor: 安路科技
- Board: 自定义/比赛指定开发板
- Toolchain: 待补充

## 仓库目标

本仓库用于团队协作开发，强调：

- 清晰的目录结构
- 可复现的工程组织
- 基本的 Git/GitHub 协作规范
- 对 FPGA 工程中间文件和大文件的管理

## 仓库结构

详细说明见：

- `docs/repo_structure.md`

主要目录：

- `project/`：工程文件
- `rtl/`：HDL 源码
- `sim/`：仿真文件
- `constraints/`：约束文件
- `ip/`：IP 核相关文件
- `docs/`：项目文档
- `scripts/`：辅助脚本
- `local/`：本地私有文件，不上传

## 快速开始

1. 克隆仓库
2. 阅读 `docs/setup.md`
3. 阅读 `CONTRIBUTING.md`
4. 不要直接在 `main` 上开发
5. 从 `main` 创建自己的分支进行开发

## 协作规范

请先阅读：

- `CONTRIBUTING.md`

## 当前任务

见：

- `TODO.md`

## 说明

- 请不要上传编译中间文件、日志、缓存、临时大文件
- 本地临时文件请放在 `local/` 中
- 大文件管理策略见 `CONTRIBUTING.md`
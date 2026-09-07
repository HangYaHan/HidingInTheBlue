# Contributing Guide

本仓库用于 FPGA 比赛团队协作开发。由于部分成员是 GitHub 新手，请务必先阅读本文件。

## 1. 基本原则

- 不要直接向 `main` 分支提交开发内容
- 每个功能、修复或文档更新都在单独分支进行
- 一次提交只做一件事
- 不要上传编译产物、缓存、日志和本地私有文件
- 改动接口或目录结构时，请同步更新文档

## 2. 分支开发

推荐分支命名：

- `feature/<name>`
- `fix/<name>`
- `docs/<name>`
- `refactor/<name>`
- `test/<name>`

示例：

- `feature/mipi-rx`
- `feature/hdmi-output`
- `feature/sobel-filter`
- `fix/frame-sync`
- `docs/setup-guide`

开发流程建议：

1. 先同步最新 `main`
2. 从 `main` 创建自己的分支
3. 在自己的分支上开发
4. 完成后发起 Pull Request
5. 合并后删除分支

## 3. 提交规范

### 推荐提交信息格式

```text
type: short description
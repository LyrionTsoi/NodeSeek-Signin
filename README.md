# NodeSeek-Signin（增强版）

> 基于 [yowiv/NodeSeek-Signin](https://github.com/yowiv/NodeSeek-Signin) 的功能增强版本

## � 原项目说明

完整的功能说明和基础配置请参考：**[原仓库 README](https://github.com/yowiv/NodeSeek-Signin/blob/main/README.md)**

## ✨ 新增功能

### 🎲 签到模式选择

原仓库只支持随机签到模式，本增强版新增了**签到模式选择**功能：

- **随机签到**：随机获得 1-5 个鸡腿（原版默认）
- **固定签到**：固定获得 5 个鸡腿（新增功能）

## ⚙️ 配置方法

### 设置签到模式

在仓库的 `Settings` → `Secrets and variables` → `Actions` → `Variables` 标签页中：

点击 `New repository variable` 添加：

| Variable 名称 | 值 | 说明 |
|--------------|-----|------|
| `NS_RANDOM` | `true` | 随机签到（1-5个鸡腿）|
| `NS_RANDOM` | `false` | 固定签到（5个鸡腿）|

### 其他配置

其他所有配置（账号密码、验证码、通知等）请参考 [原仓库文档](https://github.com/yowiv/NodeSeek-Signin/blob/main/README.md)

## � 使用方法

1. Fork 本仓库
2. 按照 [原仓库说明](https://github.com/yowiv/NodeSeek-Signin/blob/main/README.md) 配置基础设置
3. 添加 `NS_RANDOM` 变量选择签到模式
4. 启用 GitHub Actions

---

**💡 提示**：如果不设置 `NS_RANDOM` 变量，默认使用随机签到模式
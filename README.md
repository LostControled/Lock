# 一键锁屏（LockNow）

一个面向 TrollStore 的极简 iOS/iPadOS 工具。

## 功能

- 点击桌面图标：立即锁屏。
- 长按桌面图标：在快捷菜单中选择“重启设备”。
- 不需要常驻后台，也不需要越狱环境。

## 设备要求

- iOS / iPadOS 16.0 或更新版本
- TrollStore

本项目借用 [TrollCuts](https://github.com/udevsharold/TrollCuts) 中已验证的私有框架调用方式和 TrollStore entitlements。构建产物不是 App Store 签名包。

## 编译

1. 打开 GitHub 仓库的 Actions。
2. 选择 **Build LockNow**。
3. 点击 **Run workflow**。
4. 构建成功后，在运行记录的 Artifacts 下载 `LockNow-tipa`。
5. 用 TrollStore 安装 `LockNow.tipa`。

首次安装后，桌面图标名称为“一键锁屏”。长按图标可呼出“重启设备”快捷操作。

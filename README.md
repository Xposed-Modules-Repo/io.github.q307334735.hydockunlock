# 底栏无界 (HyDockUnlock)

HyperOS 桌面底栏（Dock / Hotseat）解锁 LSPosed 模块。

* **包名**：io.github.q307334735.hydockunlock
* **当前版本**：v1.0.1 (versionCode 2)
* **源码与下载**：https://github.com/q307334735/HyDockUnlock

## 功能

* 解除 `com.miui.home` 底栏图标数量限制，**容量与单元格数一并生效**
* **同时修好第 6 个图标被挤出屏幕右侧**的溢出问题
* 无 ROOT 重启桌面；底栏图标个数 4–12 可调，**修改即时生效**
* 液态玻璃设置界面 + 全局彩虹文字

## 适用性

**只适用于「秋成刷机包」内的系统桌面**（com.miui.home RELEASE-8.01.02.7719，
HyperOS 4 的 Flutter + Dart AOT 实现）。其他系统桌面版本请自测：
本模块内置 48 字节函数签名扫描，对不上时会放弃打补丁，不会把桌面搞崩。

## 授权

[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)（署名 · 非商业 · **禁止二改**）。
允许原样转载与个人使用；**禁止修改后重新打包分发，禁止任何商业用途**。
完整条文见源码仓库的 LICENSE。

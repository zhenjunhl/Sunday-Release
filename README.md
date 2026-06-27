# Sunday macOS App

一款高效的 macOS 辅助工具，提供多种实用插件功能。

## 下载

[![Download](https://img.shields.io/badge/⬇️_下载-Sunday.dmg-blue?style=for-the-badge)](https://github.com/zhenjunhl/Sunday-Release/raw/main/Sunday.dmg)

## 安装

1. 点击上方下载按钮下载 `Sunday.dmg`
2. 双击打开 `.dmg` 文件
3. 将 `Sunday.app` 拖到 `Applications` 图标上
4. 双击运行

**系统要求**：macOS 13.0 或更高版本

## 功能特性

### 计算器插件
- 支持基本运算：`+`, `-`, `*`, `/`, `^`, `%`
- 支持括号和复杂表达式：`(1+2)*3`
- 支持数学函数：`sqrt(16)`, `sin(30)`, `cos(45)`
- 支持常量：`π`, `e`
- 输入表达式后按 Enter 自动复制结果到剪贴板

### JSON 视图插件
- 解析和格式化 JSON 数据
- 支持多窗口显示
- 可搜索 JSON 键和值
- 支持排序键名
- 自定义字体大小和窗口透明度

### 时间戳插件
- 时间戳转换为可读日期格式
- 支持秒、毫秒、微秒、纳秒单位
- 双向转换：时间戳 ↔ 日期字符串

### 应用搜索
- 快速搜索 macOS 应用程序
- 键盘快捷键快速启动

### iCloud 配置同步
- 自动同步设置到 iCloud Drive
- 本机和云端配置自动合并
- 跨设备保持一致的体验

### 截图插件
- 全局快捷键快速截图（Command+Shift+1）
- 支持多种动作：复制、置顶、OCR 识别、保存
- Pin 窗口可配置透明度
- OCR 支持多语言识别

### 剪贴板历史
- 全局快捷键快速访问（Command+Shift+V）
- 自动记录剪贴板文本历史
- 支持搜索、固定、删除历史记录
- 可配置记录数量和排除应用
- 选择历史项后自动粘贴到目标 App

### 取色器插件
- 全局快捷键快速取色（Command+Shift+Q）
- 支持屏幕任意位置取色，带放大镜预览
- 支持多种颜色格式：HEX、RGB、HSL
- 一键复制颜色值到剪贴板
- 支持输入 HEX/RGB 颜色值预览

## 快捷键

| 快捷键 | 功能 |
|--------|------|
| `Cmd+Shift+M` | 打开主界面 |
| `Cmd+Shift+Q` | 取色器 |
| `Cmd+Shift+1` | 截图 |
| `Cmd+Shift+V` | 剪贴板历史 |
| `Cmd+Shift+2` | 聚焦到搜索框 |
| `Enter` | 执行/复制计算结果 |
| `J/K/N/M` | 选择插件窗口位置 |

## 设置

设置文件存储位置：
- 本机：`~/.sunday/settings.json`
- iCloud：`~/Library/Mobile Documents/com~apple~CloudDocs/Sunday/settings.json`

可配置项：
- 用户名称
- 欢迎语
- 语音播报
- 主题颜色
- 各插件窗口行为（置顶、透明度等）
- 自定义快捷键

## 许可证

MIT License
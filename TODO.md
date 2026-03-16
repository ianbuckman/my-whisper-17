# My Whisper — 后续迭代 TODO

## 待办

- [ ] **菜单栏支持**：将 App 改为菜单栏常驻模式（NSStatusItem），无需保持主窗口在前台也能快捷录音

## 已完成

- [x] 基本流程跑通（录音 → VAD → MLX Whisper 转录 → 显示）
- [x] 全局快捷键 ⌘⇧Space 开始/停止
- [x] 语言切换菜单
- [x] 幻觉过滤
- [x] 打包为 DMG 安装包
- [x] **模型选择**：UI 中提供 Whisper 系列模型下拉选择（tiny / base / small / medium / large-v3-turbo）
- [x] **换行分段**：每次转录结果追加时换行显示，每段转录各占一行
- [x] **关闭窗口不退出**：关闭窗口后快捷键仍可录音，点 Dock 图标重新打开窗口
- [x] **Web UI 重构**：使用 WKWebView + HTML/CSS 替代原生控件，支持深色/浅色模式自适应

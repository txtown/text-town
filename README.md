# Text Town 文字小鎮

> 🚧 **開發中 | Under Development**

全螢幕終端聊天應用程式，支援自動更新。

A full-screen terminal chat application with auto-update support.

## 🚀 快速安裝 | Quick Install

### macOS

**Apple Silicon (M1, M2, M3, M4):**

```bash
curl -fsSL https://github.com/txtown/text-town/releases/latest/download/txtown-macos-arm64 -o txtown && chmod +x txtown && ./txtown
```

**Intel:**

```bash
curl -fsSL https://github.com/txtown/text-town/releases/latest/download/txtown-macos-x64 -o txtown && chmod +x txtown && ./txtown
```

### Linux

```bash
curl -fsSL https://github.com/txtown/text-town/releases/latest/download/txtown-linux -o txtown && chmod +x txtown && ./txtown
```

### Windows

**PowerShell 一鍵安裝:**

```powershell
Invoke-WebRequest -Uri "https://github.com/txtown/text-town/releases/latest/download/txtown-windows.exe" -OutFile "txtown.exe"; .\txtown.exe
```

**或手動下載:**

1. 下載 [txtown-windows.exe](https://github.com/txtown/text-town/releases/latest/download/txtown-windows.exe)
2. 雙擊執行，或在終端執行: `.\txtown.exe`

## 📦 全域安裝 | Global Install

安裝到系統路徑，任何地方都能執行 `txtown`:

Install to system PATH to run `txtown` from anywhere:

**macOS / Linux:**

```bash
# Apple Silicon Mac
sudo curl -fsSL https://github.com/txtown/text-town/releases/latest/download/txtown-macos-arm64 -o /usr/local/bin/txtown && sudo chmod +x /usr/local/bin/txtown

# Intel Mac
sudo curl -fsSL https://github.com/txtown/text-town/releases/latest/download/txtown-macos-x64 -o /usr/local/bin/txtown && sudo chmod +x /usr/local/bin/txtown

# Linux
sudo curl -fsSL https://github.com/txtown/text-town/releases/latest/download/txtown-linux -o /usr/local/bin/txtown && sudo chmod +x /usr/local/bin/txtown
```

安裝後直接執行 | Then run:
```bash
txtown
```

## ✨ 功能特色 | Features

- 🖥️ 全螢幕終端介面 | Full-screen terminal interface
- 💬 可捲動聊天記錄 | Scrollable chat history
- ⌨️ Tab 切換焦點 | Tab-based focus switching
- 🔄 自動更新系統 | Auto-update system
- 📦 獨立執行檔 | Standalone executable (no Node.js required)

## 🎮 使用方式 | Usage

首次執行時，啟動器會自動下載核心應用程式（約 50-80MB）。

On first run, the launcher automatically downloads the core application (~50-80MB).

### 鍵盤快捷鍵 | Keyboard Shortcuts

- **Tab** - 切換聊天視窗和輸入框 | Switch between panes
- **↑/↓** - 捲動聊天記錄 | Scroll chat history
- **Enter** - 送出訊息 | Send message
- **Esc** - 清空輸入 | Clear input
- **Ctrl+C** (按兩次) - 退出程式 | Exit (press twice)

## 🔄 自動更新 | Auto-Updates

應用程式啟動時會自動檢查更新：

The app checks for updates on startup:

- **可選更新** | Optional updates - 會詢問是否更新 | Prompts for confirmation
- **強制更新** | Force updates - 自動下載更新 | Automatically downloads

## 💡 系統需求 | Requirements

- **macOS**: 10.15+ (Catalina or later)
- **Linux**: 64-bit
- **Windows**: Windows 10+

無需安裝 Node.js 或其他相依套件！

No Node.js or other dependencies required!

## 🐛 問題回報 | Issues

遇到問題？請到 Issues 回報：

Found a bug? Please report it:

https://github.com/txtown/text-town/issues

## 📝 授權條款 | License

MIT License

---

**Made with ❤️ using [Ink](https://github.com/vadimdemedes/ink) & [TypeScript](https://www.typescriptlang.org)**

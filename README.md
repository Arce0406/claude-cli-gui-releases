# Claude CLI GUI — 安裝檔

這個 repo 只放 [Claude CLI GUI](https://claude.com/claude-code) 的安裝檔與版本紀錄，沒有原始碼。
程式裡的「檢查更新」也是來這裡查，所以不需要任何 GitHub 帳號或權限。

## 下載

到 [Releases](../../releases) 拿最新版：

| 系統 | 檔案 |
|---|---|
| Windows | `ClaudeCliGui-<版本>-setup.exe` |
| macOS（Apple Silicon） | `ClaudeCliGui-<版本>.dmg` |

安裝檔沒有付費簽章，第一次開啟時系統會擋一下：

- **Windows**：出現藍色的「Windows 已保護您的電腦」→ 按「其他資訊」→「仍要執行」。
- **macOS**：在「應用程式」裡對它按右鍵 →「打開」，再按一次「打開」。

裝好之後，程式會自己來這裡檢查新版，按「立即更新」就能裝上。

## 這是什麼

Claude Code CLI 的本機圖形介面：介面仿照 Claude 桌面版，打字在一般文字框裡進行，中英文輸入法可以正常切換，不會像終端機 TUI 那樣卡住。背後跑的是你自己電腦上的官方 `claude` 指令，用你自己登入的 Claude 帳號與額度；本程式不提供、也不經手任何帳號或金鑰。

本專案與 Anthropic 無關，非官方產品。

# Tickets Hunter v2026.10.25（測試版封裝）

本資料夾是 [bouob/tickets_hunter](https://github.com/bouob/tickets_hunter) 的 Windows 打包版本，
供測試使用。**本封裝並非原作者官方發行版，也未獲原作者背書。**

## 來源與作者

- 原始專案：https://github.com/bouob/tickets_hunter
- 原作者：bouob 及原專案貢獻者，著作權屬其所有。
- 本版本以原專案原始碼為基礎，使用專案內的 `build_scripts/`（PyInstaller）在 Windows 上打包。
- 本版本的變更內容請見 `CHANGELOG.txt`。

## 授權

- 本專案採用 **GNU General Public License v3.0（GPL-3.0）**，完整條款見 `LICENSE`。
- 依 GPL-3.0，散布執行檔時必須同時提供對應的原始碼。本封裝對應的原始碼：
  **（上傳後填入本儲存庫原始碼位置，例如 `tickets_hunter_source/` 或 Release 連結）**
- 依原作者要求，使用與散布時請遵守：
  - 保持開源授權條款（GPL-3.0）
  - 標註原作者資訊
  - 不得用於商業牟利

## 使用限制（沿用原專案聲明）

- 僅供教育與研究及個人合法使用，嚴禁加價轉售、商業牟利或惡意囤票。
- 台灣地區禁止用於《文化創意產業發展法》涵蓋之票券（演唱會、戲劇、展覽等）。
- 程式不會自動付款，付款須由使用者手動完成。
- 完整免責與法律條款見 `LEGAL_NOTICE.md`，使用前請先閱讀。

## 內容

| 檔案 | 說明 |
|------|------|
| `settings.exe` | 設定介面，先執行這個 |
| `nodriver_tixcraft.exe` | 搶票主程式 |
| `README_Release.txt` | 使用說明（沿用原專案） |
| `CHANGELOG.txt` | 變更記錄 |
| `LICENSE` / `LEGAL_NOTICE.md` | 授權條款與法律聲明 |

## 測試版注意事項

- 此版本**尚未在真實票務網站上實測**，請測試者回報問題時附上平台、活動網址類型與錯誤訊息。
- 回報時請勿貼出帳號、密碼、Cookie 或 `settings.json` 內容。
- 僅支援 Windows。

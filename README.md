# rime-eo

**Esperanta Klavara Aranĝo por Rime | Esperanto Input for Rime | 中州韻世界語輸入方案**

---

## Pri ĉi tiu projekto

Rime-agordo por tajpi Esperantajn supersignojn (ĉ, ĝ, ĥ, ĵ, ŝ, ŭ) per la **X-sistemo** kaj la **dulitera sistemo**.

Tajpu `cx` aŭ `cc` por ĉ, `gx` aŭ `gg` por ĝ, ktp.

---

## English

### About

A Rime input schema for typing Esperanto diacritical letters (ĉ, ĝ, ĥ, ĵ, ŝ, ŭ) using the widely-adopted **X-system** and **double-letter system**.

Type `cx` or `cc` for ĉ, `gx` or `gg` for ĝ, etc.

### Other Esperanto Schemas

Other Rime Esperanto schemas also exist:

| Project                                                               | Notes                                                                                                                                       |
| --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| [arsenali/rime-esperanto](https://github.com/arsenali/rime-esperanto) | Uses X-system. Sometimes pressing space after certain inputs confirms the letter but do not output a space; needs extra key press for space |
| [afive10/Rime-Esperanto](https://github.com/afive10/Rime-Esperanto)   | Uses keyboard remapping for single-key input (e.g., `x` → ĉ). Offers faster typing but requires memorizing new key positions                |

**rime-eo** features:

-   ✅ **Intuitive** — uses X-system (`cx` → ĉ) + double-letter system (`cc` → ĉ)
-   ✅ **Smooth** — space key works properly
-   ✅ **Simple** — minimal, maintainable codebase

### Input Methods

#### X-system (Recommended)

| Input | Output | Input       | Output |
| ----- | ------ | ----------- | ------ |
| `cx`  | ĉ      | `Cx` / `CX` | Ĉ      |
| `gx`  | ĝ      | `Gx` / `GX` | Ĝ      |
| `hx`  | ĥ      | `Hx` / `HX` | Ĥ      |
| `jx`  | ĵ      | `Jx` / `JX` | Ĵ      |
| `sx`  | ŝ      | `Sx` / `SX` | Ŝ      |
| `ux`  | ŭ      | `Ux` / `UX` | Ŭ      |

#### Double-letter System (Alternative)

| Input | Output | Input | Output |
| ----- | ------ | ----- | ------ |
| `cc`  | ĉ      | `CC`  | Ĉ      |
| `gg`  | ĝ      | `GG`  | Ĝ      |
| `hh`  | ĥ      | `HH`  | Ĥ      |
| `jj`  | ĵ      | `JJ`  | Ĵ      |
| `ss`  | ŝ      | `SS`  | Ŝ      |
| `uu`  | ŭ      | `UU`  | Ŭ      |

> ⚠️ Note: This also means you need more keystrokes to type literal `cc`, `gg`, etc.

### Installation

1. Copy `eo.schema.yaml` and `eo.dict.yaml` to your Rime user directory:

    - **macOS (Squirrel)**: `~/Library/Rime/`
    - **Windows (Weasel)**: `%APPDATA%\Rime\`
    - **Linux (ibus-rime)**: `~/.config/ibus/rime/`

2. Add `eo` to your schema list in `default.custom.yaml`:

```yaml
patch:
    schema_list:
        - schema: eo
        # ... your other schemas
```

3. Redeploy Rime (重新部署)

### License

MIT

---

## 中文

### 簡介

這是一個用於輸入世界語戴帽字母（ĉ, ĝ, ĥ, ĵ, ŝ, ŭ）的中州韻輸入方案，支持 **X-system** 和**雙字母系統**。

輸入 `cx` 或 `cc` 得到 ĉ，輸入 `gx` 或 `gg` 得到 ĝ，以此類推。

### 其他世界語方案

現有的 Rime 世界語方案：

| 項目                                                                  | 說明                                                                       |
| --------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [arsenali/rime-esperanto](https://github.com/arsenali/rime-esperanto) | 使用 X-system。某些情況下按空格確認字符但不輸出空格；需要額外按下空格鍵    |
| [afive10/Rime-Esperanto](https://github.com/afive10/Rime-Esperanto)   | 使用鍵盤重映射實現單鍵輸入（如 `x` → ĉ）。熟悉後打字更快，但需要記憶新鍵位 |

**rime-eo** 的特色：

-   ✅ **直覺** — 使用 X-system（`cx` → ĉ）+ 雙字母系統（`cc` → ĉ）
-   ✅ **流暢** — 空格正常運作
-   ✅ **簡潔** — 詞庫更精簡，易於維護

### 輸入方式

#### X-system（推薦）

| 輸入 | 輸出 | 輸入        | 輸出 |
| ---- | ---- | ----------- | ---- |
| `cx` | ĉ    | `Cx` / `CX` | Ĉ    |
| `gx` | ĝ    | `Gx` / `GX` | Ĝ    |
| `hx` | ĥ    | `Hx` / `HX` | Ĥ    |
| `jx` | ĵ    | `Jx` / `JX` | Ĵ    |
| `sx` | ŝ    | `Sx` / `SX` | Ŝ    |
| `ux` | ŭ    | `Ux` / `UX` | Ŭ    |

#### 雙字母系統（備選）

| 輸入 | 輸出 | 輸入 | 輸出 |
| ---- | ---- | ---- | ---- |
| `cc` | ĉ    | `CC` | Ĉ    |
| `gg` | ĝ    | `GG` | Ĝ    |
| `hh` | ĥ    | `HH` | Ĥ    |
| `jj` | ĵ    | `JJ` | Ĵ    |
| `ss` | ŝ    | `SS` | Ŝ    |
| `uu` | ŭ    | `UU` | Ŭ    |

> ⚠️ 注意：本方案採用雙字母系統，也意味著需要更多的按鍵來輸入原始的 `cc`、`gg` 等。

### 安裝

1. 將 `eo.schema.yaml` 和 `eo.dict.yaml` 複製到 Rime 用戶目錄：

    - **macOS 鼠鬚管**: `~/Library/Rime/`
    - **Windows 小狼毫**: `%APPDATA%\Rime\`
    - **Linux ibus-rime**: `~/.config/ibus/rime/`

2. 在 `default.custom.yaml` 中加入方案：

```yaml
patch:
    schema_list:
        - schema: eo
        # ... 其他方案
```

3. 重新部署

### 方案比較

| 特性       | rime-eo           | arsenali/rime-esperanto | afive10/Rime-Esperanto |
| ---------- | ----------------- | ----------------------- | ---------------------- |
| 輸入系統   | X-system + 雙字母 | X-system                | 鍵盤重映射             |
| 按鍵數     | 2 鍵              | 2 鍵                    | 1 鍵                   |
| 學習成本   | 低                | 低                      | 較高                   |
| 雙字母系統 | ✅ 支持           | —                       | —                      |
| 詞庫大小   | ~70 行            | ~200 行                 | 無需詞庫               |

### 授權

MIT

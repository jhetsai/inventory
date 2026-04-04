# 門市智能管理系統 - 文件中心

_維護：蝦助 🦐_

---

## 📁 專案結構

```
├── docs/                    # 操作手冊
│   ├── INVENTORY_MANUAL.md           # 庫存系統 - 詳細技術手冊
│   ├── INVENTORY_QUICK_GUIDE.md      # 庫存系統 - 簡單使用說明（純文字）
│   └── INVENTORY_QUICK_GUIDE.html    # 庫存系統 - 簡單使用說明（美觀版）
│
├── index.html               # 庫存系統主頁面
├── inventory.json           # 庫存資料庫
├── electricity_final.html   # 台電電費分析系統
│
└── README.md               # 本文件
```

---

## 🚀 快速連結

| 系統 | 連結 |
|------|------|
| 📦 庫存系統 | https://jhetsai.github.io/inventory/ |
| ⚡ 台電分析 | https://jhetsai.github.io/openclaw/electricity_final.html |

---

## 📋 操作手冊

### 庫存系統

| 手冊 | 適合對象 | 說明 |
|------|---------|------|
| [INVENTORY_QUICK_GUIDE](docs/INVENTORY_QUICK_GUIDE.md) | 門市人員 | 3步驟快速上手 |
| [INVENTORY_MANUAL](docs/INVENTORY_MANUAL.md) | 管理人員 | 完整功能說明 |

### 台電系統

請參考系統內建說明（按「？」按鈕）

---

## 🔧 技術架構

```
┌─────────────┐     ┌──────────────┐     ┌──────────────┐
│   LINE     │────▶│   AI Bot    │────▶│   GitHub     │
│   App      │     │  (自動分析)  │     │  (資料儲存)  │
└─────────────┘     └──────────────┘     └──────────────┘
                                               │
                                               ▼
                                      ┌──────────────┐
                                      │   網頁顯示    │
                                      │ (GitHub Pages)│
                                      └──────────────┘
```

---

## 📞 聯繫

有問題找蔡哲維 🦐

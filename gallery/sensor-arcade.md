# Sensor Arcade

> **English:** Use device sensors (e.g. accelerometer) for playful interactions.

**一句講完：** 用裝置感應器（加速計等）做小遊戲／互動。

| | |
|--|--|
| **適合邊啲人** | 初學＋裝置感測／ Sensors + play |
| **類型** | Playground Book（`.playgroundbook`） |
| **圖庫位置** | Apple Swift Playground 圖庫／Get Started（Feed `7A53`） |

---

## 點樣打開

1. 安裝 [Swift Playground](https://apps.apple.com/app/swift-playground/id1496833156)（Mac／iPad）。
2. Swift Playground → Get／圖庫 → Sensor Arcade（建議用支援感測嘅 iPad／iPhone；Mac 體驗可能受限）。
3. 第一次下載可能要等；完成後跟書內 **intro／提示** 開始。

用已下載嘅 zip（自行由 Apple CDN 攞，**唔好** commit 入 git）：

```bash
# 例：下載後解壓再開
open -a "Swift Playground" "/path/to/extracted-book-or-swiftpm"
```

---

## 官方 CDN（只提供連結）

[https://playgrounds-cdn.apple.com/7A53/Content/SensorArcade/SensorArcade.playgroundbook.zip](https://playgrounds-cdn.apple.com/7A53/Content/SensorArcade/SensorArcade.playgroundbook.zip)

> 本頁同本 repo **唔包含** Apple 二進位檔。下載僅供個人／課堂合法使用。

---

## 學習目標／課堂建議

- 理解「感測數據 → 程式反應」
- 課堂：傾側裝置控制角色／指標
- 討論權限同安全（點解 App 要問加速計）
- 銜接 Sensor Create

---

## 關鍵概念／API

感測輸入、事件驅動 UI。跟 in-app intro。

若書內 API 同本頁描述有出入，**一律以 App 內說明為準**。

---

## 相關教程

- [Sensor Create](sensor-create.md)
- [Seismometer](seismometer.md)
- [圖庫總目](README.md)
- [CDN URL 清單](../docs/CDN-MANIFEST.md)
- [根目錄指南（Learn to Code 焦點）](../README.md)

---

## 免責

教程文字為原創（MIT，見 [LICENSE](../LICENSE)）。Apple、Swift、Swift Playground 同所有教材／美術版權屬 Apple Inc.；**唔重新發佈** `.playgroundbook`／`.swiftpm`／zip。

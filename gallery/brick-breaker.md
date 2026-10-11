# Brick Breaker

> **English:** Classic brick-breaker: ball, paddle, collisions, level pacing.

**一句講完：** 經典打磚塊：球、板、碰撞同關卡節奏。

| | |
|--|--|
| **適合邊啲人** | 初學＋興趣（遊戲循環）／ Beginner+ game loop |
| **類型** | Playground Book（`.playgroundbook`） |
| **圖庫位置** | Apple Swift Playground 圖庫／Get Started（Feed `7A53`） |

---

## 點樣打開

1. 安裝 [Swift Playground](https://apps.apple.com/app/swift-playground/id1496833156)（Mac／iPad）。
2. Swift Playground → Get／圖庫 → Brick Breaker。
3. 第一次下載可能要等；完成後跟書內 **intro／提示** 開始。

用已下載嘅 zip（自行由 Apple CDN 攞，**唔好** commit 入 git）：

```bash
# 例：下載後解壓再開
open -a "Swift Playground" "/path/to/extracted-book-or-swiftpm"
```

---

## 官方 CDN（只提供連結）

[https://playgrounds-cdn.apple.com/7A53/Content/BrickBreaker/BrickBreaker.playgroundbook.zip](https://playgrounds-cdn.apple.com/7A53/Content/BrickBreaker/BrickBreaker.playgroundbook.zip)

> 本頁同本 repo **唔包含** Apple 二進位檔。下載僅供個人／課堂合法使用。

---

## 學習目標／課堂建議

- 觀察遊戲循環（更新位置 → 偵測碰撞 → 重繪）
- 討論變數：球速、板位置、剩餘磚數
- 課堂：改一個參數（例如板闊）再玩，睇對手感影響
- 連線計算思維：重複更新＝迴圈概念

---

## 關鍵概念／API

遊戲迴圈、座標／速度概念。打開書跟 in-app intro；唔臆造 API。

若書內 API 同本頁描述有出入，**一律以 App 內說明為準**。

---

## 相關教程

- [Code Machine](code-machine.md)
- [Sensor Arcade](sensor-arcade.md)
- [圖庫總目](README.md)
- [CDN URL 清單](../docs/CDN-MANIFEST.md)
- [根目錄指南（Learn to Code 焦點）](../README.md)

---

## 免責

教程文字為原創（MIT，見 [LICENSE](../LICENSE)）。Apple、Swift、Swift Playground 同所有教材／美術版權屬 Apple Inc.；**唔重新發佈** `.playgroundbook`／`.swiftpm`／zip。

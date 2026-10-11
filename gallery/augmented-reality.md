# Augmented Reality

> **English:** Intro to AR: place virtual content in a real scene.

**一句講完：** 擴增實境入門：虛擬物件疊喺真實場景。

| | |
|--|--|
| **適合邊啲人** | 進階興趣（AR）／ Intermediate AR intro |
| **類型** | Playground Book（`.playgroundbook`） |
| **圖庫位置** | Apple Swift Playground 圖庫／Get Started（Feed `7A53`） |

---

## 點樣打開

1. 安裝 [Swift Playground](https://apps.apple.com/app/swift-playground/id1496833156)（Mac／iPad）。
2. Swift Playground → Get／圖庫 → Augmented Reality（需要支援 AR 嘅裝置同相機權限）。
3. 第一次下載可能要等；完成後跟書內 **intro／提示** 開始。

用已下載嘅 zip（自行由 Apple CDN 攞，**唔好** commit 入 git）：

```bash
# 例：下載後解壓再開
open -a "Swift Playground" "/path/to/extracted-book-or-swiftpm"
```

---

## 官方 CDN（只提供連結）

[https://playgrounds-cdn.apple.com/7A53/Content/AugmentedReality/AugmentedReality.playgroundbook.zip](https://playgrounds-cdn.apple.com/7A53/Content/AugmentedReality/AugmentedReality.playgroundbook.zip)

> 本頁同本 repo **唔包含** Apple 二進位檔。下載僅供個人／課堂合法使用。

---

## 學習目標／課堂建議

- 理解 AR 需要相機／追蹤世界
- 課堂：每人放一個簡單 3D／標記物件
- 討論光線、平面偵測對體驗影響
- 銜接 AR Create

---

## 關鍵概念／API

相機、世界追蹤、場景內容。跟 in-app intro；唔臆造 RealityKit API 細節。

若書內 API 同本頁描述有出入，**一律以 App 內說明為準**。

---

## 相關教程

- [AR Create](ar-create.md)
- [Lights, Camera, Code](lights-camera-code.md)
- [圖庫總目](README.md)
- [CDN URL 清單](../docs/CDN-MANIFEST.md)
- [根目錄指南（Learn to Code 焦點）](../README.md)

---

## 免責

教程文字為原創（MIT，見 [LICENSE](../LICENSE)）。Apple、Swift、Swift Playground 同所有教材／美術版權屬 Apple Inc.；**唔重新發佈** `.playgroundbook`／`.swiftpm`／zip。

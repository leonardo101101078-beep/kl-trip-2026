# 吉隆坡旅遊規劃 · KUL 2026.05.30–06.01

## 專案概覽

朋友標注的吉隆坡美食與旅遊地標規劃，地圖來源：
`https://www.google.com/maps/d/viewer?mid=1dBgJbu1D0vvGf86U-sP_2K3kTliXtbw`

---

## 航班資訊（星宇航空）

| 方向 | 日期 | 出發 | 抵達 |
|------|------|------|------|
| 去程 | 5/30（六） | 11:15（台灣） | 16:10（KLIA） |
| 回程 | 6/1（一） | 17:10（KLIA） | 22:05（台灣） |

> 注意：星宇週五週二無航班。6/1 需在 15:00 前抵達機場。

---

## 檔案結構

| 檔案 | 說明 |
|------|------|
| `吉隆坡旅遊規劃.md` | 三個方案完整行程（Markdown 文字版） |
| `吉隆坡方案比較.html` | 方案 A vs B 視覺化比較頁（旅遊雜誌 Editorial 風格） |

---

## 三個方案摘要

### 方案 A：吉隆坡深度美食遊
- 全程留守 KL，系統性打通地圖上的食堂
- 移動量低，適合純吃貨、不愛趕路
- 涵蓋：碧華樓點心、Village Park 椰漿飯、BKT、亞羅街夜市、Batu Caves

### 方案 B：KL + 馬六甲一日遊
- 5/31 整天搭巴士去馬六甲（TBS → 馬六甲，約 2 小時）
- 移動量高，需 07:30 出發
- 馬六甲：大樹下鴨麵、McQuek's Satay Celup、Klebang 椰子奶昔、Putu Piring、河遊船
- 適合想看 UNESCO 世遺古城、嚐娘惹料理的人


---

## 地圖標注地點分類

### 吉隆坡 — 景點
- Batu Caves（黑風洞）
- 雙峰塔（Petronas Twin Towers）
- 茨廠街（Petaling Street Market）
- 蘇丹阿都沙末占美回教堂
- 獨立廣場（Merdeka Square）
- 蘇丹沙拉胡汀清真寺（藍色清真寺，Shah Alam）

### 吉隆坡 — 餐廳（精選）
碧華樓、Village Park、NZ Curry House、黃亞華小食店、亦是好肉骨茶、
巴生葉記（乾）肉骨茶、冠記雲吞麵、金蓮記、頌記牛肉丸粉、
何九海南茶店、Capitol Cafe、亞羅街美食街、ICC PUDU

### 吉隆坡 — 夜生活
Coley、Reka:Bar、THREE X CO、Penrose KL

### 馬六甲 — 景點
Jonker Walk、Stadthuys（荷蘭廣場）、聖保羅堂、青雲亭、馬六甲河遊船

### 馬六甲 — 餐廳（精選）
大樹下鴨麵（Tengkera Duck Noodle）、McQuek's Satay Celup、
Klebang Original Coconut Shake、Putu Piring、Nanyang Chicken Rice Ball

### 布城（Putrajaya）
布特拉回教堂、Moroccan Pavilion、Ole-Ole Bali

---

## HTML 設計規格

視覺風格：**旅遊雜誌 Editorial（Monocle × Bloomberg Businessweek）**

```
字型：Playfair Display Italic（食物名、標題）
      DM Sans 300/600（描述、label）
      DM Mono（時間戳記、標籤）

色彩：#FAF7F2 暖奶油底
      #1C1A17 暖近黑墨
      #BF5A2B KL 赤陶橙（方案 A）
      #2B6B5F 馬六甲松綠（方案 B）
      #D4C9B8 hairline 分隔線

版面：max-width 1080px，雙欄，hairline 分隔行取代卡片
      馬六甲日程 = full-bleed 松綠 insert block
```

---

## 待完善項目

- [ ] 確認幾個人同行（影響餐廳訂位策略）
- [ ] 確認住宿（地圖標注：Infini Suites @ The Robertson Bukit Bintang）
- [ ] 有無飲食禁忌或偏好
- [ ] 交通方式：全程 Grab vs 自租車 vs 大眾運輸
- [ ] 是否加入方案 C（夜生活路線）的元素

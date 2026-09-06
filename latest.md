# 台股 AI 情報官｜每日晨報 MVP

產生時間：2026-09-06 07:33
自選股數：14｜新聞數：37

## 今日 3 個觀察重點
- 台積電（2330）：交叉分數 110；技術 97/100（偏多）; 消息 4 則; EPS 為正
- 元大高股息（0056）：交叉分數 102；技術 92/100（偏多）; 消息 5 則
- 富邦科技（0052）：交叉分數 101；技術 97/100（偏多）; 消息 2 則

## 五面向 Agent 交叉驗證

> 分數只採用目前已接資料：技術面、基本面、消息面。籌碼面與期權籌碼先明確標示為待接資料，避免假裝有訊號。

### 台積電（2330）｜交叉分數 110
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60
- 基本面 Agent：可參考｜最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：有訊號｜4 則｜CMoney, UDN, stock.ltn.com.tw｜最新：2330 台積電 - 09/01 台股盤前：輝達砸35億美元認購聯發科，費半逆勢漲0.57%，台股AI能抗總經利空？ - 股市爆料同學會
- 期權籌碼 Agent：待接資料｜尚未串期交所 OI、P/C Ratio、Max Pain、IV；目前不作方向判斷。
- 綜合判讀：技術 97/100（偏多）; 消息 4 則; EPS 為正

### 元大高股息（0056）｜交叉分數 102
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60
- 基本面 Agent：資料不足｜ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：高熱度｜5 則｜CMoney, CMoney投資網誌, ETtoday財經雲｜最新：高股息接棒漲 0056規模衝破6,000億元關卡
- 期權籌碼 Agent：不適用｜個股/ETF 報告暫不做期權解讀；台指選擇權可作大盤溫度計。
- 綜合判讀：技術 92/100（偏多）; 消息 5 則

### 富邦科技（0052）｜交叉分數 101
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60
- 基本面 Agent：資料不足｜ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：有訊號｜2 則｜FTNN 新聞網, 自由財經｜最新：0050、0052準備換股! 散戶搶搭便車聚焦這五檔個股
- 期權籌碼 Agent：不適用｜個股/ETF 報告暫不做期權解讀；台指選擇權可作大盤溫度計。
- 綜合判讀：技術 97/100（偏多）; 消息 2 則

### 統一證（2855）｜交叉分數 101
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60
- 基本面 Agent：可參考｜最近一季 EPS 為正；TTM EPS 為正；PER 相對低，需查是否循環或一次性因素
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：有訊號｜2 則｜CMoney投資網誌, 今周刊｜最新：【13:24 即時新聞】統一證(2855)股價上漲至50.5元，受證券景氣回溫與營收年增帶動＋投信連續買超、主力近5日偏多挹注
- 期權籌碼 Agent：待接資料｜尚未串期交所 OI、P/C Ratio、Max Pain、IV；目前不作方向判斷。
- 綜合判讀：技術 92/100（偏多）; 消息 2 則; EPS 為正

### 主動群益台灣強棒（00982A）｜交叉分數 99
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60
- 基本面 Agent：資料不足｜ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：有訊號｜1 則｜CMoney｜最新：8/28 00982A 台半堆到 6484 張
- 期權籌碼 Agent：不適用｜個股/ETF 報告暫不做期權解讀；台指選擇權可作大盤溫度計。
- 綜合判讀：技術 97/100（偏多）; 消息 1 則

## Agent 建置順序
1. 籌碼面：先接三大法人、融資券、借券、集保大戶持股，做每日異常警示。
2. 技術面：沿用現有均線、RSI、MACD、量價結構，強化支撐/壓力與訊號分級。
3. 消息面：保留原始連結，加入重大性分級與假消息交叉查證。
4. 基本面：從個股 EPS/PER/PBR 擴充到同業比較；ETF 改接成分股、折溢價與配息品質。
5. 期權籌碼：接台指選擇權 OI、P/C Ratio、Max Pain、IV，作為大盤溫度計，不當單一進出場訊號。


## 個股追蹤

### 富邦科技（0052）｜科技 ETF
- 技術分數：97/100（偏多）
- 收盤：62.70，日變動：1.79%
- 均線：MA5 62.25 / MA20 61.55 / MA60 61.14
- RSI14：55.11；MACD hist：0.10；量能比：0.76x
- 目標觀察價：63.30；支撐觀察價：61.60
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：下影線轉強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：2 則｜FTNN 新聞網, 自由財經｜最新：0050、0052準備換股! 散戶搶搭便車聚焦這五檔個股
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：
  - [0050、0052準備換股! 散戶搶搭便車聚焦這五檔個股](https://news.google.com/rss/articles/CBMiX0FVX3lxTE1HaEc5N2VDeFBZbUZrcWZhQzloMjhNRnNocEJqT3Axa3JjRFZkU0oyem1GdXFNQTJoblpTdDdLNVllSG12R2NPRGltZEhIWXkwcDNnNFdWOTl4WWgwaElr?oc=5)（自由財經）
  - [0050、0052換股大洗牌！市場搶先卡位這5檔 「這檔生技妖股」狂飆上1640元呼聲最高](https://news.google.com/rss/articles/CBMiS0FVX3lxTE5DMHJ0R3JSMnlEWDQtbWdFOHpMS09lUV9QNWRMYTk5bmpDUEZBYTdjRHFSbnh4MUV2N3dqdS1hVVVfaE9tOENoUFF6Zw?oc=5)（FTNN 新聞網）
### 元大高股息（0056）｜高股息 ETF
- 技術分數：92/100（偏多）
- 收盤：55.40，日變動：1.65%
- 均線：MA5 54.89 / MA20 53.30 / MA60 52.00
- RSI14：70.69；MACD hist：0.21；量能比：0.72x
- 目標觀察價：55.80；支撐觀察價：54.50
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：下影線轉強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：5 則｜CMoney, CMoney投資網誌, ETtoday財經雲｜最新：高股息接棒漲 0056規模衝破6,000億元關卡
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、MACD 柱狀體偏多
- 近 7 日新聞：
  - [高股息接棒漲 0056規模衝破6,000億元關卡](https://news.google.com/rss/articles/CBMiWkFVX3lxTE9jZkpMODlCX2ZtRmMyRm80MTRQSE1JNW8yclNZaWt6LUtmLTIzNDBkN0QwQlJnSUZjd1RPVW5lOWhfS2lKT0EtRFVVYThMSnR1QmtsalNfeXJnUdIBX0FVX3lxTFBTMkhUeEg1bUlwVk1JU0xmRkJLbm5MT0dKNW9pSTRmNmlTQnNQY1hIenJwRWM2SGxNby1CbDIydWlRWnZkajJzbWViczVZRkFmaTYzOUlqNzZpT3B6eDVr?oc=5)（經濟日報）
  - [【台股ETF五天王】一表看0050、00878、0056 等最愛買什麼？全撞「這2檔」！](https://news.google.com/rss/articles/CBMiqwNBVV95cUxOc3QtMVFfQ2FYcEpwcXdiWktncnRQU2hEdmhpSnNJUWZYbzMwTjdfTnFUV2k3RU52NEk0Z2haMFRndk1QVXFmWWFNeFVXemkxOXdjY2R6VUtsOS0xQVZQdkstZG1IOVlqOERwTEp0N280R2t3VVZWbXFDU29mRnNMQzZxN3VPX1FhUXc4MldWVzdUUS1zUlpJMG05b3Uwb0x3d3R5V01zVVlYb3YzbGtkeDRuNVZBbUlFNFh1QmFzLW5uOTJEdk9SRzlpYmM5WlIzMl92ZGo1V2JCM3l0RHh5RFBNZDQySzdPOE5TN2F3bG9sZkNfY0FBN2IzcEo0Q01HVFpCV0c4S1A3VGwydHZsR0Z2bGdDVFpEZkZEX1R6U09NbnRySUVTcTVyUnNPaDZtdHlpNExRejdsdXJzT1VNcmFaWmhWV3dRVml4TFRiSVBWTGpmOHRXclpNLW52M2dXTXMxWnNoTEhUMU11Qkp1WV85VXNud1FqbXJtM2pZTC05dm9PV3F1YjlDRnE4M01FelJkUVhsbE8yd0ZQdDVKZnVpZDB1N0o2aU4w?oc=5)（Yahoo股市）
  - [元大高股息(0056) 個股概覽 | 個股 - 股市](https://news.google.com/rss/articles/CBMiU0FVX3lxTFBUclNKaHBtTmlhUkpJSzUzZEJSQUM0UDlvS2p3Q2RWdldoeVJXN1M5TnF4OEN5SUV6NHBvTkNaOUVERDM4dU5kSW50Nk9JaU5LT0RB?oc=5)（CMoney）
### 中信臺灣智慧50（00912）｜智慧型 ETF
- 技術分數：97/100（偏多）
- 收盤：35.15，日變動：1.53%
- 均線：MA5 34.92 / MA20 34.36 / MA60 33.55
- RSI14：55.23；MACD hist：0.05；量能比：0.26x
- 目標觀察價：35.40；支撐觀察價：34.60
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 低訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：近 7 日未抓到明確新聞；今日消息面不加分。
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：未抓到明確新聞，今日先以技術面觀察。
### 群益台灣精選高息（00919）｜高股息 ETF
- 技術分數：84/100（偏多）
- 收盤：33.02，日變動：1.54%
- 均線：MA5 32.43 / MA20 31.07 / MA60 30.13
- RSI14：92.68；MACD hist：0.19；量能比：1.23x
- 目標觀察價：33.50；支撐觀察價：32.50
- 目標依據：已在近期高檔，改用 ATR 波動推估下一段觀察價。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60、RSI 偏熱，避免追價
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：5 則｜CMoney, ETtoday財經雲, news.cnyes.com｜最新：百萬國民高股息 ETF 00919成分股調整名單出爐 18進18出
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 偏熱，追價風險升高
- 近 7 日新聞：
  - [百萬國民高股息 ETF 00919成分股調整名單出爐 18進18出](https://news.google.com/rss/articles/CBMiWkFVX3lxTE51WTFZdlItVnpxY2hKZnZsdzF2Y29RbDJLVUthTzU4cTRMZG5WVlN2SDhpTlQ0MkJmR0tkMDRSeWhJLXF2Y0pyNGRqNHFHbkVkQzVteG5DRV84UdIBX0FVX3lxTE5TTFFDck8tdGY1Vm5PZTVrM2tpLW9YUXRLZThlWFlYc1FWcjhOY1ZGLTRkZGdTUXZtTkpTR2xyTVo4eFVWUDhYWjRqeTlDNlNGYU5uOGtBNzFzTmRQdTJ3?oc=5)（經濟日報）
  - [00919配息1.1元創新高！配息／除息日、最後買進日、成分股一次看－ETF指南](https://news.google.com/rss/articles/CBMiZkFVX3lxTE8xbjdaQjRNSzI4TVozSHZRemxZX01zbWlSRTlqYUZkQ0ZkYnIzc2RxandWOXQyWVFLbHlON0ViMFpQWVFyUFBVRFdZVllOdjRlbXQtYTJmQnc4MkVqcUU3X3huV1V0Zw?oc=5)（商周）
  - [00919 群益台灣精選高息- 台股ETF 發股息新一波聚焦八檔公告第一階段金額檔檔飆高- 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE1tSkFabXNtLWdYSnJCY3dYTUp2QTRjSkFUQTRRYWhJUlM1X1hWVTYzRUVLX095QXAyR292TU9TYXVJeUdNN1k5Mll1Y3NlVEU5cVNYMEo2Mlk?oc=5)（CMoney）
### 元大台灣價值高息（00940）｜高股息 ETF
- 技術分數：84/100（偏多）
- 收盤：13.01，日變動：1.80%
- 均線：MA5 12.88 / MA20 12.59 / MA60 12.42
- RSI14：75.23；MACD hist：0.04；量能比：1.80x
- 目標觀察價：13.20；支撐觀察價：12.80
- 目標依據：已在近期高檔，改用 ATR 波動推估下一段觀察價。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60、RSI 偏熱，避免追價、量能放大 1.80x
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：2 則｜FTNN 新聞網, 經濟日報｜最新：00940單月配息數字再現0.05元 年化配息率逾5%
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 偏熱，追價風險升高
- 近 7 日新聞：
  - [00940單月配息數字再現0.05元 年化配息率逾5%](https://news.google.com/rss/articles/CBMiWkFVX3lxTE5uNVhHekpYS3hFaHdsQUY3QmdKa05rYVRwZHd4WUJIa3V4Ui0wODcxVGV4d242Y1lMaGdMU1RoRDVUb0ZMbmE2UGhjc3JxMHdBUXZWZ2g0X05wUdIBX0FVX3lxTE13dy10ODJacV9jRXZBR2VrcHVFMFVoTVNlTWozbUFzTTZIS0RrVGk0MzdIa0RGdE9wTmNqd3ZDdW1RMDY5UDRYUnRzbjc3M2xsbVlkd0FjbmRtNDV2Slk0?oc=5)（經濟日報）
  - [00940要衝13元、配息也創新高！32萬人還能抱？達人搖頭：存這3檔CP值更高](https://news.google.com/rss/articles/CBMiS0FVX3lxTE9NOUZONDNpdmF5U1BzMWxMRERLVFRhQmRobkcxM2ZaU0VlUE1fZHlPMXBfaUppd25PNjllSW11Vkk5NlpWbFdzbWNwMA?oc=5)（FTNN 新聞網）
### 主動群益台灣強棒（00982A）｜主動式 ETF
- 技術分數：97/100（偏多）
- 收盤：22.96，日變動：2.45%
- 均線：MA5 22.82 / MA20 22.46 / MA60 22.88
- RSI14：46.00；MACD hist：0.11；量能比：0.63x
- 目標觀察價：23.55；支撐觀察價：22.45
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：十字線，短多排列；位於 20 日區間中段，等方向表態。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：1 則｜CMoney｜最新：8/28 00982A 台半堆到 6484 張
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：
  - [8/28 00982A 台半堆到 6484 張](https://news.google.com/rss/articles/CBMiWEFVX3lxTE40M0FodF9PMzRJeFpFQVBkaTNkNjNjZzE0dlpCR1RwNlFLQVBjeUJiNnBtSTBfM182d1A2SExoNUc3bUZnZm5FRkFxZHgzall5cGx3UFZPVmM?oc=5)（CMoney）
### 中纖（1718）｜化纖 / 紡織原料
- 技術分數：71/100（偏多）
- 收盤：10.60，日變動：-0.93%
- 均線：MA5 10.83 / MA20 10.70 / MA60 11.23
- RSI14：48.65；MACD hist：0.04；量能比：0.72x
- 目標觀察價：10.70；支撐觀察價：9.94
- 目標依據：目前在 MA20 下方，目標先看能否站回月線。
- K 線：一般 K 線，月線下方；位於 20 日區間中段，等方向表態。
- 基本面：EPS 0.29（2026-06-30）；TTM EPS 0.59；PER 18.14；PBR 0.60；殖利率 0.00%
- Agent 快讀：技術面 中性觀察｜基本面 可參考｜消息面 低訊號
  - 技術：短均線優於月線、RSI 位於健康區間、MACD 柱狀體偏多
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
  - 消息：近 7 日未抓到明確新聞；今日消息面不加分。
- 訊號：短均線優於月線、RSI 位於健康區間、MACD 柱狀體偏多
- 近 7 日新聞：未抓到明確新聞，今日先以技術面觀察。
### 台積電（2330）｜晶圓代工 / AI 權值
- 技術分數：97/100（偏多）
- 收盤：2410.00，日變動：0.84%
- 均線：MA5 2406.00 / MA20 2399.25 / MA60 2390.75
- RSI14：51.52；MACD hist：0.08；量能比：0.71x
- 目標觀察價：2445.00；支撐觀察價：2400.00
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：一般 K 線，短多排列；位於 20 日區間中段，等方向表態。
- 基本面：EPS 27.25（2026-06-30）；TTM EPS 86.28；PER 27.70；PBR 9.64；殖利率 0.92%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
  - 消息：4 則｜CMoney, UDN, stock.ltn.com.tw｜最新：2330 台積電 - 09/01 台股盤前：輝達砸35億美元認購聯發科，費半逆勢漲0.57%，台股AI能抗總經利空？ - 股市爆料同學會
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：
  - [2330 台積電 - 09/01 台股盤前：輝達砸35億美元認購聯發科，費半逆勢漲0.57%，台股AI能抗總經利空？ - 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE9ieXVRcHNMSGp5LWhXcHBsOWQtUTdnYUFwc3I3MWUxOFA5UTdmakRsa1AtTlJ3NUNRcFUzV1Zwd0VCZDBNeWxVQ1RrOXBmZktScmYtdmVEYkM?oc=5)（CMoney）
  - [長庚醫院台積電（2330）放3年多驚人！63億變352億 PTT：長庚投顧](https://news.google.com/rss/articles/CBMiUkFVX3lxTE1HdEVVWV9JemlTWENTZThHeXNTbUdLU0xYUWd6M1duc0NLcXpvTmNFLWFJZ2ZwTXJEa1ZjUVhFZnMwXzBsM1BtSjVramg4UmtMb0HSAVdBVV95cUxOZWg1NHNQVENaTnY3aGF4Z1kxNmkwX21PZFg5d0IzX3prRzRCdzNYd19KR0NRanRaYmtYTzdtRkZYeWZ0SUFUeElQRUN6alYwcHh0UTlDc0U?oc=5)（UDN）
  - [焦點股》台積電：ADR勁揚 創2345元新天價](https://news.google.com/rss/articles/CBMiWEFVX3lxTE5IVlFHbF9neGg0UVhrckcxTm5PUWpyZFJZRjZ0dUNHOWpGR1hFMWhhLUdYT2hURC1vTURCdGpvZ0hONW90RkFkbkNnU3k3Z1VvMkZsTXltUzY?oc=5)（stock.ltn.com.tw）
### 統一證（2855）｜證券 / 金融
- 技術分數：92/100（偏多）
- 收盤：50.70，日變動：0.20%
- 均線：MA5 50.09 / MA20 47.70 / MA60 47.68
- RSI14：73.56；MACD hist：0.44；量能比：1.15x
- 目標觀察價：51.20；支撐觀察價：50.60
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：一般 K 線，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：EPS 1.33（2025-12-31）；TTM EPS 3.00；PER 5.25；PBR 1.69；殖利率 4.17%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 相對低，需查是否循環或一次性因素
  - 消息：2 則｜CMoney投資網誌, 今周刊｜最新：【13:24 即時新聞】統一證(2855)股價上漲至50.5元，受證券景氣回溫與營收年增帶動＋投信連續買超、主力近5日偏多挹注
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、MACD 柱狀體偏多
- 近 7 日新聞：
  - [【13:24 即時新聞】統一證(2855)股價上漲至50.5元，受證券景氣回溫與營收年增帶動＋投信連續買超、主力近5日偏多挹注](https://news.google.com/rss/articles/CBMijgFBVV95cUxPQmh5d1MyOWw3UTRZS3FaSjVQUExCbGxYaUdpLWpLQ3p2UldmbXI5al9DYjdPYkJHdUc3THNVRmdocEhYLURDOEVsLS1BaUJfUlZEdjMtZUVCSU9oeThnYjJkNUtaMk03UXB0cm82VlR2VmFrNkh3ME1pMXFQZmpuaVY0ZUpmZGozTWRGR0hn?oc=5)（CMoney投資網誌）
  - [存股助理第842期｜統一2026年半年報評析—統一證券扮演獲利成長大功臣｜股池更新](https://news.google.com/rss/articles/CBMikgFBVV95cUxNV0JZX3ZWb3NBdk9jTUZZYy1BbHRtOG5ab3pmbzJtUHVSd2FjVWFKcC0zdHZ5aVR4WGY0dEY4cm1Qc0UwM1prNk5iOUVQV2hyNWg5MUdfcmVZYzFZdUgwNldJMjVRclBLcjJWTkU5SDFKQU1IQjhpWm9uRFhKQW1xWHV2VmpTZy1VZ0lSYnExM0VjZw?oc=5)（今周刊）
### 凱基金（2883）｜金融控股
- 技術分數：84/100（偏多）
- 收盤：36.70，日變動：2.23%
- 均線：MA5 35.38 / MA20 32.39 / MA60 30.68
- RSI14：80.81；MACD hist：0.49；量能比：0.94x
- 目標觀察價：37.90；支撐觀察價：35.90
- 目標依據：已在近期高檔，改用 ATR 波動推估下一段觀察價。
- K 線：下影線轉強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：EPS 0.65（2025-12-31）；TTM EPS 1.74；PER 12.55；PBR 1.42；殖利率 2.79%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60、RSI 偏熱，避免追價
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 相對低，需查是否循環或一次性因素
  - 消息：5 則｜CMoney, Yahoo股市, stock.ltn.com.tw｜最新：全球創舉！凱基金推首檔連結台股ETF 的虛擬代幣kTW50
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 偏熱，追價風險升高
- 近 7 日新聞：
  - [全球創舉！凱基金推首檔連結台股ETF 的虛擬代幣kTW50](https://news.google.com/rss/articles/CBMi1wJBVV95cUxORC1zaUNRMnIwY01LUWR2UE8xelE0U2pheUN4RTRhSGMtNmVMNG5LLU5NSWJUWGtqclRuT0VHNWs4MVBfNmlBRzZETnNObUpqdHBZUUxPMTd0d0tqT01fMC1Qd0QtNk1fSXRqOGFLaUNxTUJzdnFFMVQtQ052N1JFbGJhbS1WMXVhWFpPNUJYYW54dVdNLURGaFdKTHFDMW5WSW9KcXZ6ZV9DLXRacXl0VWJ0Z25uRW80aXU1YkNKZmlVSklTdXZSdTlEN1lZSDdhV0prNk95ZTZfMkZkbzdkN1NJSWkxUENfM2gzU2tWaXB5em15Z2RwdE1mV0d1alhXU3hicHZNZng3OTgxSDdXVFNJUnpONnFOUktiN3hWSXNDa3pkcWQ4NW1jMnNwQmZrZll0VG9ER2lTQUliZmpsZF9JMUJLOVZ5QUlubG9tMXhUVVdEeHRJ?oc=5)（Yahoo股市）
  - [凱基金(2883) 個股概覽 | 個股 - 股市](https://news.google.com/rss/articles/CBMiU0FVX3lxTE5razMwcGM0azNqYW5MRDVOWVRHSnI0ZlhJNnFDekNVcURPdXZURGMzQUlPQ2h4dHhTTjczdGl3RDlqYk5KbDJWQTdYdnJYWU9OMkZv?oc=5)（CMoney）
  - [00919換股納入凱基金 股價昨日飆漲停、今盤中續飆逾9%](https://news.google.com/rss/articles/CBMiWkFVX3lxTFBMYXlZNUdDb3Vhb1FQdGJ4bzYweWYwd2VhbmUtc2toaUpCYUpOeXd0UE4tWGVzSjlyd0tzb2hZNGlBdlV3Q3AyZm1JeGhkZzA2WEZjSzNwaUx0d9IBX0FVX3lxTE84Q01wNjJrWXNsRU9GVWFjRzQ2V2d3SXUxQW5kcllFYXpfN0IxQVFIUXM2RFM0UllqaGc4WGE1N2ZneXI2cUZ5eHlsUGpZdFZUUUtZb2RSMUQxN2o1RHdv?oc=5)（經濟日報）
### 群創（3481）｜面板 / 顯示器
- 技術分數：66/100（偏多）
- 收盤：48.50，日變動：0.83%
- 均線：MA5 48.96 / MA20 48.50 / MA60 53.88
- RSI14：40.00；MACD hist：0.40；量能比：0.63x
- 目標觀察價：48.50；支撐觀察價：48.10
- 目標依據：目前在 MA20 下方，目標先看能否站回月線。
- K 線：一般 K 線，月線下方；位於 20 日區間中段，等方向表態。
- 基本面：EPS 0.57（2026-06-30）；TTM EPS 0.78；PER 61.67；PBR 1.71；殖利率 2.08%
- Agent 快讀：技術面 中性觀察｜基本面 可參考｜消息面 高熱度
  - 技術：短均線優於月線、MACD 柱狀體偏多
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
  - 消息：5 則｜CMoney, CMoney投資網誌, Yahoo股市｜最新：3481 群創 - 大漲老師終於群創了 https://youtube.com/... - 股市爆料同學會
- 訊號：短均線優於月線、MACD 柱狀體偏多
- 近 7 日新聞：
  - [3481 群創 - 大漲老師終於群創了 https://youtube.com/... - 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE1TdDZvTk9laGU1ZTJmUi1ZcVZkdWxKNm1feEpNV1VvbFlsMnB1VUxrdnptTEFuNm05UnVpaGFiMTV6QnpwMzMyTzFRM3FHWU10cURlbWs2S2o?oc=5)（CMoney）
  - [00406A一小時炸19萬張巨量！力壓群創、00981A、力積電登頂台股成交王](https://news.google.com/rss/articles/CBMimgNBVV95cUxOcHBzSkdrZHhqckFuVUpxSDhrRkR4TVQweTlxYm1QM3NxTlRnLWQxNEtTVDhjVVRuc016QWlaZmVib3Jkck1Qb01LcTY1NDVkOHp6ekxiZ1RzMnlOTjZEb1FHakRKRGZmMlpzX1FqLVBIT2p5eldQSGJiV1JxUjVTdFNtSXd0NDA4Y1dIcVpnTi1nTXdIMFM0b2wzTTFPSFEtMGlpenpCdFdFRml1MEx6Q2hPN1laSFhvNzFJVnNNZ2o0M3lqaUtpXzBsb09EaE5pT2lQamFabnh5cXA4c2dFWm56aUJmUmlXeE5uRmR0akxOQXdBU1haV1JXZmZWcjZ2WEdpay1GUDF4TkY1MWxrNzkxVWEzaUt5YTlkbU5TNjhyX3ZNV2lvRHlpS0Y2bWQ4SEhpSzVIMUMxWXBjZDBUMVZkUUtLc3VDTFpJTHhRVGxGRGtheEVYSnVqRHhjaS1ScDN0cGZhMnJ0N05NZ01xVzlQMG1vYklac2Q3eVhIR1ZnemViSWh6Y3NRM0h2NXdwVFJWZlpWdW13dw?oc=5)（Yahoo股市）
  - [【即時新聞】群創(3481)沾AI爆量大漲6%！專家點出這隱憂，後市還能追嗎？](https://news.google.com/rss/articles/CBMikAFBVV95cUxPUVYwNUdoZ19sS0Rsa01qYnRYeDV4b1Q4NGdmYjhURDRkaXdfbVhjaGtVZjhVYTNNQldGbUIycjNRZWxwdjZRSlBfOFQ1eUZGQXVpVWM0UFJhaU0yMWJSOTBGN1F6c1d3cEowM08xMDZSR2Q4QW1idF9PV0NVOXVvem5iVnNvSUFyUVlaSTB1LUI?oc=5)（CMoney投資網誌）
### 日月光投控（3711）｜封測 / 半導體
- 技術分數：42/100（中性觀察）
- 收盤：588.00，日變動：-0.17%
- 均線：MA5 592.00 / MA20 603.10 / MA60 617.10
- RSI14：41.18；MACD hist：-0.42；量能比：0.86x
- 目標觀察價：603.00；支撐觀察價：564.00
- 目標依據：目前在 MA20 下方，目標先看能否站回月線。
- K 線：一般 K 線，短空排列；位於 20 日區間中段，等方向表態。
- 基本面：EPS 4.80（2026-06-30）；TTM EPS 13.92；PER 42.62；PBR 6.66；殖利率 1.12%
- Agent 快讀：技術面 中性觀察｜基本面 可參考｜消息面 有訊號
  - 技術：MACD 柱狀體偏弱
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
  - 消息：4 則｜CMoney, CMoney投資網誌, sinotrade.com.tw｜最新：【零股排行榜】盤中零股排行榜TOP 20｜0050 元大台灣50、2327 國巨*、00981A 主動統一台股增長、3711 日月光投控、1303 南亞 (0831)｜豐雲學堂2026 年 09 月
- 訊號：MACD 柱狀體偏弱
- 近 7 日新聞：
  - [【零股排行榜】盤中零股排行榜TOP 20｜0050 元大台灣50、2327 國巨*、00981A 主動統一台股增長、3711 日月光投控、1303 南亞 (0831)｜豐雲學堂2026 年 09 月](https://news.google.com/rss/articles/CBMi0ARBVV95cUxOeTBSRkRJb0xuOVQ4ZzBIeFRjNS1qRGZXREFEOE5oTzUtdnZVVXZrZFZPOVhSbVUyQ2I5czFkTlFkMzk5ckVQdzhPalc4bHlINndnWk9uS3BmelM4Qnd0M0lYV2h4WHZNd3pNeVpJTHppbkN4Y3hWMndqSlZseG5ldmhsRVU3eDBoUTFfN0RjVW9Da0JIQmh0SGVXeG9ycDBNX1VWVDF4OUJpSkd6T1FLNjR2M1FSTUZ6U2dkLWd5NWxNVV9HTHQ4Xzgxd2haaUduSjNVajVodXhYVjgxYXFWTGZOZmE3V1VQcDVpbENjMGJkVGVORXFxNDczdGhRQUZNXzh0NTI4eWk5T244aHlqTG5IRUJmQk9hOWxOTGVpQWJBWWpvdjl6ZWtKY3BWTXBLdFdsNGdPOF9Gb0t4anpZajhscXNNTVgyclY1T2lqSGxFaXJwcXpMbDVweHR5LTMyWDhQemdJT0tnQUtaLXRnbUg4Y1RQWDNQX2w2ZkVtRE53QUc0LXo1eS1jdlNpdUhvbW9RSF9SU1NLMTl0WG5kS0oyVng3SlQ5bHR3TUZjZFJybGc2dHI0ZUpsOG9jcTBONkV5aHdLQWZROGVpbEItWjl6cnBiVkpQTVZuSURfTWszeXpCQ3ljVXp4aHA0OG0zTThIbC13dmV5RXdzM3ZhY2ZFRi1fcUIzaW0zZnVFRGFlR01WVkRzMnBhekpSZ0N2NVZJVGhEUlpXWFE5NEktNEQ3WUE1M2tTcnZ3QjYzRGVlZTRYVVc2b2NmbWRqV2Ns?oc=5)（sinotrade.com.tw）
  - [3711 日月光投控- 【日月光投控(3711)盤後解析】法人主力同步大賣，股價帶量... - 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE9Sem9wTDRLLWg5Ums1TXh2ZVNuSXNWMWZScHJoUllSdE5uV05tTzlYR3BMOXRvTmtQOUMybWItZnNKZmRvNU5WZVlHdTlydUgxRFFrbUJlWDA?oc=5)（CMoney）
  - [【即時新聞】日月光投控(3711)獲先進封裝追單，這「6檔概念股」多空大洗牌！](https://news.google.com/rss/articles/CBMikAFBVV95cUxNdU1aU2ZEajlobTRobUc1NHNCWDJjSmd2ZkJtUW5wYmVoMkZTdnY2cmhHSHFaMVpUYi12ckhDY1VjQmNvbTJPMElMTVo1aVBhbVllVS1RVUtNYW1RalVNUTZDLXBIR2o0R3E3Y3I3WFNaZzBNSW5GVm1fM3Jrbk5yQTFxLUY4YzlCSEZNWFFsQlQ?oc=5)（CMoney投資網誌）
### 磐亞（4707）｜化工
- 技術分數：42/100（中性觀察）
- 收盤：30.10，日變動：-0.99%
- 均線：MA5 31.52 / MA20 32.44 / MA60 30.90
- RSI14：42.86；MACD hist：-0.42；量能比：0.66x
- 目標觀察價：32.45；支撐觀察價：28.80
- 目標依據：目前在 MA20 下方，目標先看能否站回月線。
- K 線：一般 K 線，短空排列；接近 20 日低檔，先看止跌與量能回溫。
- 基本面：EPS 0.43（2026-06-30）；TTM EPS 1.28；PER 23.57；PBR 1.48；殖利率 1.64%
- Agent 快讀：技術面 中性觀察｜基本面 可參考｜消息面 有訊號
  - 技術：MACD 柱狀體偏弱
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
  - 消息：2 則｜富聯網, 工商時報｜最新：磐亞處分台中銀27,200張 獲利8,125萬元 Q3 EPS估貢獻0.56元
- 訊號：MACD 柱狀體偏弱
- 近 7 日新聞：
  - [磐亞處分台中銀27,200張 獲利8,125萬元 Q3 EPS估貢獻0.56元](https://news.google.com/rss/articles/CBMiX0FVX3lxTFBKNDd2RFNCc0M5VUxzd1hXUExCc05QU201NkJvYk5kczU2Wnh2bTJRb1RuTkQ5OFZGZEdmbnFFMzNsNk9DaFlQc0xmZHllUEw5SzJSRHNSNXdORzRTX2JR?oc=5)（工商時報）
  - [個股：磐亞(4707)8/18～9/2累積處分台中銀股票27,200張，獲利約8,124萬元](https://news.google.com/rss/articles/CBMiiAFBVV95cUxPUEYyc3VQS0oyU2FOVlFaOWRJOG5pcmZTaTdUSjVRSG9vajlXOGd6VEFXMnBSVnJSdzRnR2o5SzFweGRzeVdWT0RPZjdkbG5HM29YeEZkanktSGpUVDlLdjBrd1RVU3JXTHB2ak0wZ3Zycl9JRGxiQ253YXVKbGdITmptdGtaclFQ?oc=5)（富聯網）
### 聯策（6658）｜電子零組件 / 題材股
- 技術分數：89/100（偏多）
- 收盤：178.00，日變動：2.30%
- 均線：MA5 179.00 / MA20 166.60 / MA60 173.76
- RSI14：61.35；MACD hist：2.59；量能比：0.66x
- 目標觀察價：197.00；支撐觀察價：174.00
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：下影線轉強，站上月線；位於 20 日區間中段，等方向表態。
- 基本面：EPS 1.42（2026-06-30）；TTM EPS 4.13；PER 42.23；PBR 4.44；殖利率 0.69%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 低訊號
  - 技術：站上 MA20、站上 MA60、短均線優於月線
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
  - 消息：近 7 日未抓到明確新聞；今日消息面不加分。
- 訊號：站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間、MACD 柱狀體偏多
- 近 7 日新聞：未抓到明確新聞，今日先以技術面觀察。

## 風險提醒
- 新聞來源以公開 RSS 搜尋為主，可能有延遲或誤配，正式版需接 FinMind/Fugle/券商 API 做校驗。
- 技術分數只反映量價結構，不代表未來報酬。
- 盤中盯盤目前走 Yahoo best-effort；正式版建議升級準即時行情 API。

本內容僅供資訊整理與研究學習，不構成任何投資建議或買賣依據。

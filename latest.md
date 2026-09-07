# 台股 AI 情報官｜每日晨報 MVP

產生時間：2026-09-07 07:24
自選股數：14｜新聞數：44

## 今日 3 個觀察重點
- 台積電（2330）：交叉分數 116；技術 97/100（偏多）; 量能 1.32x; 消息 5 則
- 富邦科技（0052）：交叉分數 107；技術 92/100（偏多）; 量能 1.57x; 消息 5 則
- 日月光投控（3711）：交叉分數 103；技術 89/100（偏多）; 量能 1.51x; 消息 5 則

## 五面向 Agent 交叉驗證

> 分數只採用目前已接資料：技術面、基本面、消息面。籌碼面與期權籌碼先明確標示為待接資料，避免假裝有訊號。

### 台積電（2330）｜交叉分數 116
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60
- 基本面 Agent：可參考｜最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：高熱度｜5 則｜CMoney, sinotrade.com.tw, udn｜最新：台積電(2330) 個股概覽 | 個股 - 股市
- 期權籌碼 Agent：待接資料｜尚未串期交所 OI、P/C Ratio、Max Pain、IV；目前不作方向判斷。
- 綜合判讀：技術 97/100（偏多）; 量能 1.32x; 消息 5 則; EPS 為正

### 富邦科技（0052）｜交叉分數 107
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60、量能放大 1.57x
- 基本面 Agent：資料不足｜ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：高熱度｜5 則｜FTNN 新聞網, LINE TODAY, pocket.tw｜最新：高含「積」ETF 長線俏 0052、0050、006208等掌握成長契機
- 期權籌碼 Agent：不適用｜個股/ETF 報告暫不做期權解讀；台指選擇權可作大盤溫度計。
- 綜合判讀：技術 92/100（偏多）; 量能 1.57x; 消息 5 則

### 日月光投控（3711）｜交叉分數 103
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60、量能放大 1.51x
- 基本面 Agent：可參考｜最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：高熱度｜5 則｜BigGo 財經, TradingView, cmnews.com.tw｜最新：【零股排行榜】盤中零股排行榜TOP 20｜0050 元大台灣50、2327 國巨*、00981A 主動統一台股增長、3711 日月光投控、1303 南亞 (0831)｜豐雲學堂2026 年 09 月
- 期權籌碼 Agent：待接資料｜尚未串期交所 OI、P/C Ratio、Max Pain、IV；目前不作方向判斷。
- 綜合判讀：技術 89/100（偏多）; 量能 1.51x; 消息 5 則; EPS 為正; 估值偏高需保守

### 主動群益台灣強棒（00982A）｜交叉分數 99
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60
- 基本面 Agent：資料不足｜ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：有訊號｜1 則｜CMoney｜最新：8/31 00982A 賣28筆但不是在挑股票
- 期權籌碼 Agent：不適用｜個股/ETF 報告暫不做期權解讀；台指選擇權可作大盤溫度計。
- 綜合判讀：技術 97/100（偏多）; 消息 1 則

### 群創（3481）｜交叉分數 98
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、短均線優於月線
- 基本面 Agent：可參考｜最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：高熱度｜5 則｜CMoney, FTNN 新聞網, cmnews.com.tw｜最新：3481群創 | 「量增突破、驗證情境 A」的強勢反彈格局
- 期權籌碼 Agent：待接資料｜尚未串期交所 OI、P/C Ratio、Max Pain、IV；目前不作方向判斷。
- 綜合判讀：技術 89/100（偏多）; 消息 5 則; EPS 為正; 估值偏高需保守

## Agent 建置順序
1. 籌碼面：先接三大法人、融資券、借券、集保大戶持股，做每日異常警示。
2. 技術面：沿用現有均線、RSI、MACD、量價結構，強化支撐/壓力與訊號分級。
3. 消息面：保留原始連結，加入重大性分級與假消息交叉查證。
4. 基本面：從個股 EPS/PER/PBR 擴充到同業比較；ETF 改接成分股、折溢價與配息品質。
5. 期權籌碼：接台指選擇權 OI、P/C Ratio、Max Pain、IV，作為大盤溫度計，不當單一進出場訊號。


## 個股追蹤

### 富邦科技（0052）｜科技 ETF
- 技術分數：92/100（偏多）
- 收盤：63.75，日變動：1.67%
- 均線：MA5 62.63 / MA20 61.69 / MA60 61.23
- RSI14：65.92；MACD hist：0.18；量能比：1.57x
- 目標觀察價：66.00；支撐觀察價：62.70
- 目標依據：已接近短壓，改看近 60 日高點壓力。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60、量能放大 1.57x
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：5 則｜FTNN 新聞網, LINE TODAY, pocket.tw｜最新：高含「積」ETF 長線俏 0052、0050、006208等掌握成長契機
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、MACD 柱狀體偏多
- 近 7 日新聞：
  - [高含「積」ETF 長線俏 0052、0050、006208等掌握成長契機](https://news.google.com/rss/articles/CBMiWkFVX3lxTE9Na1FLVDJrM1gzTHN3RnV6OTV5ZXRHcmtwMnBXQlhJcklESG1aYTQxbnpMTGZzaDBETnFKcXB2WEF5ekdrdmQ5RFI2ZE81VTdjc2F6Qy05UUVEQdIBX0FVX3lxTFBGZ1ViVmtfWE91VlU1R1RWd0VCMGpEUC10bk5pOHduZzg4eURVSlF2WFRlbFFuNTE1WjVHTHRHdnlzR1FpVzQzbDl2bmFQQ0czcjZ2TWJYTC1ud2pjbnJF?oc=5)（經濟日報）
  - [富邦科技(0052)ETF股票型基金的基本資料](https://news.google.com/rss/articles/CBMiUkFVX3lxTFBZdjNabUZBVDhxVjhEbUpGQWt5cTVmWGE3WTlPOVMwRHU2YVJfN0x0X0ZOX2p6UVVkTVlZWGJ1RURzX2dKNlpGZEllQ3dUdi1YSFE?oc=5)（pocket.tw）
  - [老牌科技型ETF要換血！0052相中晶豪科、剔除新唐 9/21日正式生效 | Newtalk](https://news.google.com/rss/articles/CBMiVkFVX3lxTE9wSjdJendaODJFR1p6bUVwSjFjcUpGczdHa21jSWwzcHF0ZDRIM2VXRmpic3hxSGVYQ0NxNWkwYkhnU0F0LUt3QjNMbVYyZERMRUpmMWV3?oc=5)（LINE TODAY）
### 元大高股息（0056）｜高股息 ETF
- 技術分數：84/100（偏多）
- 收盤：55.85，日變動：0.81%
- 均線：MA5 55.14 / MA20 53.47 / MA60 52.10
- RSI14：76.47；MACD hist：0.23；量能比：0.82x
- 目標觀察價：56.90；支撐觀察價：55.40
- 目標依據：已在近期高檔，改用 ATR 波動推估下一段觀察價。
- K 線：一般 K 線，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60、RSI 偏熱，避免追價
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：5 則｜CMoney, ETtoday財經雲, pocket.tw｜最新：元大高股息(0056)持股明細總覽
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 偏熱，追價風險升高
- 近 7 日新聞：
  - [元大高股息(0056)持股明細總覽](https://news.google.com/rss/articles/CBMiWkFVX3lxTE55ZlF1cHAxS1F4ZDlBaDFsVUVJQ3VqdkdIcW44eFhwMmFEYXBUN2ZLX1k0VU9PVnZ0U09pMWlIb1ZiQ0t4bFNEOFJ4OGdqdU1qallGTWJwOXlldw?oc=5)（pocket.tw）
  - [0056 元大高股息- 今日最夯ETF／台股震盪收黑0056突圍創新高- 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE90ZmQ4TjJrVS04dUhCTVFFT0c3YWl5V0llbFNRVzNNRXQ0bmZ2aU5mUF9fYm1EOGRqU3pxQ1BLQ3M4eTduUXNzSTJXeEdaTWt2UGtsOExPejc?oc=5)（CMoney）
  - [今日最夯 ETF／台股震盪收黑 0056突圍創新高](https://news.google.com/rss/articles/CBMiWkFVX3lxTE5LaWkxNTduYy0xSzEwalMweElhOUY5cmUwbjd5OUFBM2dHdWtTR2lvaVdIaExOaFBUVl9fWG1DdFhudFFLQjhqNmZBaEV4RjA5SVBsS0dYdEUtUdIBX0FVX3lxTE51R21kY1NQSVFJc0lwV3I0WDRiQWxveV95d2REYi1uWUVMSDZTOUdIQTJpeE1FSDk0cEhudjE4S3VZY1BEc1dDWXpKVmcydUxUbU9JdmJWRFdmdWUwczlR?oc=5)（經濟日報）
### 中信臺灣智慧50（00912）｜智慧型 ETF
- 技術分數：92/100（偏多）
- 收盤：35.86，日變動：2.02%
- 均線：MA5 35.15 / MA20 34.47 / MA60 33.62
- RSI14：66.60；MACD hist：0.09；量能比：0.81x
- 目標觀察價：36.20；支撐觀察價：35.15
- 目標依據：已接近短壓，改看近 60 日高點壓力。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 低訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：近 7 日未抓到明確新聞；今日消息面不加分。
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、MACD 柱狀體偏多
- 近 7 日新聞：未抓到明確新聞，今日先以技術面觀察。
### 群益台灣精選高息（00919）｜高股息 ETF
- 技術分數：84/100（偏多）
- 收盤：32.91，日變動：-0.33%
- 均線：MA5 32.62 / MA20 31.21 / MA60 30.17
- RSI14：89.54；MACD hist：0.18；量能比：2.33x
- 目標觀察價：33.20；支撐觀察價：31.20
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：一般 K 線，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60、RSI 偏熱，避免追價、量能放大 2.33x
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：5 則｜CMoney, Yahoo股市, sinotrade.com.tw｜最新：百萬國民高股息 ETF 00919成分股調整名單出爐 18進18出
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 偏熱，追價風險升高
- 近 7 日新聞：
  - [百萬國民高股息 ETF 00919成分股調整名單出爐 18進18出](https://news.google.com/rss/articles/CBMiWkFVX3lxTE51WTFZdlItVnpxY2hKZnZsdzF2Y29RbDJLVUthTzU4cTRMZG5WVlN2SDhpTlQ0MkJmR0tkMDRSeWhJLXF2Y0pyNGRqNHFHbkVkQzVteG5DRV84UdIBX0FVX3lxTE5TTFFDck8tdGY1Vm5PZTVrM2tpLW9YUXRLZThlWFlYc1FWcjhOY1ZGLTRkZGdTUXZtTkpTR2xyTVo4eFVWUDhYWjRqeTlDNlNGYU5uOGtBNzFzTmRQdTJ3?oc=5)（經濟日報）
  - [00919配息1.1元創新高！配息／除息日、最後買進日、成分股一次看－ETF指南](https://news.google.com/rss/articles/CBMiZkFVX3lxTE8xbjdaQjRNSzI4TVozSHZRemxZX01zbWlSRTlqYUZkQ0ZkYnIzc2RxandWOXQyWVFLbHlON0ViMFpQWVFyUFBVRFdZVllOdjRlbXQtYTJmQnc4MkVqcUU3X3huV1V0Zw?oc=5)（商周）
  - [高股息ETF被盯上！外資出清00919捲7.4億元 再砍破1.5萬張00918](https://news.google.com/rss/articles/CBMizwJBVV95cUxPczB5U1NVV2FFMVc3MEhQdzhpbUp0N1pWdlBTQV9xVkhKM3dFcmVnX3FDODJzNkEwWUlud2xINGp6bXc1aDlNMmxjZ2M1ZDJqbjZNYTlPRmhqelpjR211Mk9JOWtCZ0I5dTFCa0FtMDI0QXhsTldONTRCakdOWUVJVVdOc0dIYmZ5bWdPYkRITTdfM29jSzFLNU8wXzBGc1VFU1E5YmpVWmtTakJNNkpNNW1qNzI5UGM0a2N3VkY4Tm5UQlpwRURqQUFuWHp3RnE2S2ZKS0s0TDVJOVVNQmpFTzBoR0FVVHRKSWJWV3pZTlVsTVlPNzkzUEJMRUtDbVBDRndXUV9kNjNYNDV2SGZGNXZjSUZaTXNyVVh2QkY1d2t4TGJheW1mdnNfMHhvQm9wMGcyMTl0Z2ZjSTNYamFFNWNVQXJZN2p3VElnUHdsTQ?oc=5)（Yahoo股市）
### 元大台灣價值高息（00940）｜高股息 ETF
- 技術分數：84/100（偏多）
- 收盤：12.99，日變動：-0.15%
- 均線：MA5 12.92 / MA20 12.62 / MA60 12.44
- RSI14：82.00；MACD hist：0.04；量能比：1.16x
- 目標觀察價：13.15；支撐觀察價：12.60
- 目標依據：已在近期高檔，改用 ATR 波動推估下一段觀察價。
- K 線：一般 K 線，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60、RSI 偏熱，避免追價
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：1 則｜FTNN 新聞網｜最新：「巨嬰」再減7千股民！00940月配0.055元創新高今最後買進日 年化配息率5%「這天領錢」
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 偏熱，追價風險升高
- 近 7 日新聞：
  - [「巨嬰」再減7千股民！00940月配0.055元創新高今最後買進日 年化配息率5%「這天領錢」](https://news.google.com/rss/articles/CBMiS0FVX3lxTFBNZ0t0Y216S3R3cWFCa3ZadDRENTg2enp0c1M1emdvcHFXOGpTa21QX3VFUDA4SmhHR0dnYjY0MzVSbHNmQmJIVG00MA?oc=5)（FTNN 新聞網）
### 主動群益台灣強棒（00982A）｜主動式 ETF
- 技術分數：97/100（偏多）
- 收盤：23.13，日變動：0.74%
- 均線：MA5 22.97 / MA20 22.48 / MA60 22.89
- RSI14：59.92；MACD hist：0.12；量能比：0.96x
- 目標觀察價：23.55；支撐觀察價：22.95
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：十字線，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：1 則｜CMoney｜最新：8/31 00982A 賣28筆但不是在挑股票
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：
  - [8/31 00982A 賣28筆但不是在挑股票](https://news.google.com/rss/articles/CBMiWEFVX3lxTE1halQ2ZVd0VzhlLXJxWlAtNnNPYmtTWlhyQko5ci1ycDYwMkkzNDZNSXhrSGFLTllyY2FXZ3pMRUJrM1RuM0lFbG9YVnhidU1mWVNFZnFBS1M?oc=5)（CMoney）
### 中纖（1718）｜化纖 / 紡織原料
- 技術分數：71/100（偏多）
- 收盤：10.45，日變動：-1.42%
- 均線：MA5 10.74 / MA20 10.71 / MA60 11.25
- RSI14：48.65；MACD hist：0.02；量能比：0.48x
- 目標觀察價：10.70；支撐觀察價：10.15
- 目標依據：目前在 MA20 下方，目標先看能否站回月線。
- K 線：長黑偏弱，月線下方；接近 20 日低檔，先看止跌與量能回溫。
- 基本面：EPS 0.29（2026-06-30）；TTM EPS 0.59；PER 17.97；PBR 0.60；殖利率 0.00%
- Agent 快讀：技術面 中性觀察｜基本面 可參考｜消息面 有訊號
  - 技術：短均線優於月線、RSI 位於健康區間、MACD 柱狀體偏多
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
  - 消息：1 則｜CMoney｜最新：中纖(1718) 個股概覽 | 個股 - 股市
- 訊號：短均線優於月線、RSI 位於健康區間、MACD 柱狀體偏多、量能偏低，突破可信度不足
- 近 7 日新聞：
  - [中纖(1718) 個股概覽 | 個股 - 股市](https://news.google.com/rss/articles/CBMiU0FVX3lxTE9WNDFIdVFVTnhGVVpjT3A2UTQ2RkZDMXZXWmg5bElQNVM2M2JXdDNGYUdxWHdpblpMV3RoT1U0NUhDRmM5dUNqWVZwZVE2aU9xZjdz?oc=5)（CMoney）
### 台積電（2330）｜晶圓代工 / AI 權值
- 技術分數：97/100（偏多）
- 收盤：2460.00，日變動：2.07%
- 均線：MA5 2417.00 / MA20 2403.25 / MA60 2394.25
- RSI14：61.11；MACD hist：3.35；量能比：1.32x
- 目標觀察價：2535.00；支撐觀察價：2410.00
- 目標依據：已接近短壓，改看近 60 日高點壓力。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：EPS 27.25（2026-06-30）；TTM EPS 86.28；PER 27.94；PBR 9.72；殖利率 0.91%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
  - 消息：5 則｜CMoney, sinotrade.com.tw, udn｜最新：台積電(2330) 個股概覽 | 個股 - 股市
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：
  - [台積電(2330) 個股概覽 | 個股 - 股市](https://news.google.com/rss/articles/CBMiU0FVX3lxTE5SVkxvYUp1Tnk1ZXpiVjE5NnVGN01xajlQOE9obFZzT1hRLTV3OV94MWxlQWpwNkRQenlmVUJXb1ZScEtlc2xUYWs4WjNnRHhpNzlJ?oc=5)（CMoney）
  - [【零股排行榜】盤中零股成交量TOP 20｜0050 元大台灣50、2330 台積電、2308 台達電、2327 國巨*、2303 聯電 (0902)](https://news.google.com/rss/articles/CBMi-gNBVV95cUxQRUpWNzVEdXI5THJUNG1LUXdUXzlzS3pFeGtFQ2Q2LUREa2xlMHA0d05mZkZwN2FIaXZ2N2lwZ3dYaG9paDVGVjZGZk9NODRWYXpJZGdOU3FqM1FUc1BaRlgxS3FKNUNTbzNUSTJ0RVo4ZUNhU3pYWXJTUmJDNmFRUFJPQzZlT2tGa0dSYm9SWWRnTFdQMU5BdVRubWhCYWhoY1FzT2VER0FnLTRRWnBIZkkxNHBEMmFEaGgyX2E5ajhNbUl1LU5mY0NQRTZlT3pWWncxR0VUNndjM3l4RWxHdDJuWm1ZOGlELXRVWUs5T1lsTU5ROV96QVFYRmp2QU1LSEVfNmNidFMtako3dlRLeFBXd2c2X2ZkUjJfR3V0aHIwT3pYNGpQbV8yU2g3eFlpalVka25WNGZkcU00NXNheHU4SmZyMkZha3VDNWh1RXpDa1c5X21DTjUyVzFJeXhEb2V2eTZaT0NCcHl6TlFzMTNNVkxWMG5PeFFDTlI1MWgtbHNpZXRGNk1aN0Njcl9xSmVINnN0UE1xYV9YeVZKN3RuNjdfd09ac3BFWDBpQjU2aVFxRjV2TnFFUmVOc2hpMGFHZUIzNXB5OFNmaEFzSGd3OVM1d3pnakU3SE5pNllfYkZFMHNXa2JwVVd6STl0d3pzV3hNX1J1dw?oc=5)（sinotrade.com.tw）
  - [台積電領軍！台股開高一度大漲680點 衝破47K](https://news.google.com/rss/articles/CBMiUEFVX3lxTE9ENUNpN2RtbjgtMnY0Z3NEOVBUYjJpNTl3Z2FIY0xSb1JKUmpjeE1ZSGQ1RVBjUG4xQVk3bFQ4OGlpemh4TzgySVh5UWdrZ3BT0gFWQVVfeXFMT3MwdlBWU21Xc1phS3ZuNmRNbkNfYnNWdjU1ME1pa3ExZXhzSnU4QWhaQTh1TkJIQVhELVA0bm1SUVdPU3UwdEJSaVZFclVXN3lTakRRZWc?oc=5)（udn）
### 統一證（2855）｜證券 / 金融
- 技術分數：84/100（偏多）
- 收盤：52.00，日變動：2.56%
- 均線：MA5 50.58 / MA20 48.01 / MA60 47.70
- RSI14：76.41；MACD hist：0.49；量能比：1.51x
- 目標觀察價：52.30；支撐觀察價：50.70
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：一般 K 線，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：EPS 1.33（2025-12-31）；TTM EPS 3.00；PER 5.26；PBR 1.69；殖利率 4.16%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60、RSI 偏熱，避免追價、量能放大 1.51x
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 相對低，需查是否循環或一次性因素
  - 消息：3 則｜cmnews.com.tw, 中時新聞網, 今周刊｜最新：【13:24 即時新聞】統一證(2855)股價上漲至50.5元，受證券景氣回溫與營收年增帶動＋投信連續買超、主力近5日偏多挹注
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 偏熱，追價風險升高
- 近 7 日新聞：
  - [【13:24 即時新聞】統一證(2855)股價上漲至50.5元，受證券景氣回溫與營收年增帶動＋投信連續買超、主力近5日偏多挹注](https://news.google.com/rss/articles/CBMijgFBVV95cUxPQmh5d1MyOWw3UTRZS3FaSjVQUExCbGxYaUdpLWpLQ3p2UldmbXI5al9DYjdPYkJHdUc3THNVRmdocEhYLURDOEVsLS1BaUJfUlZEdjMtZUVCSU9oeThnYjJkNUtaMk03UXB0cm82VlR2VmFrNkh3ME1pMXFQZmpuaVY0ZUpmZGozTWRGR0hn?oc=5)（cmnews.com.tw）
  - [統一證 股價逐步墊高](https://news.google.com/rss/articles/CBMia0FVX3lxTFBzQzNDbWwyRHNBalJaTURjZkp0clM2U3FEOVktRFZ2eHdvQTVIUlJ2QzlPWnZDODg1ZWpKMlkzNWU5UGNJdXhONzV4aTN0WC1CTm5EN1h1UlhWaGl6X2JpZ2trNDNocFAyZG8w?oc=5)（中時新聞網）
  - [存股助理第842期｜統一2026年半年報評析—統一證券扮演獲利成長大功臣｜股池更新](https://news.google.com/rss/articles/CBMikgFBVV95cUxNV0JZX3ZWb3NBdk9jTUZZYy1BbHRtOG5ab3pmbzJtUHVSd2FjVWFKcC0zdHZ5aVR4WGY0dEY4cm1Qc0UwM1prNk5iOUVQV2hyNWg5MUdfcmVZYzFZdUgwNldJMjVRclBLcjJWTkU5SDFKQU1IQjhpWm9uRFhKQW1xWHV2VmpTZy1VZ0lSYnExM0VjZw?oc=5)（今周刊）
### 凱基金（2883）｜金融控股
- 技術分數：84/100（偏多）
- 收盤：36.95，日變動：0.68%
- 均線：MA5 36.00 / MA20 32.69 / MA60 30.83
- RSI14：85.71；MACD hist：0.50；量能比：1.11x
- 目標觀察價：37.45；支撐觀察價：36.70
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：十字線，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：EPS 0.65（2025-12-31）；TTM EPS 1.74；PER 12.83；PBR 1.45；殖利率 2.72%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60、RSI 偏熱，避免追價
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 相對低，需查是否循環或一次性因素
  - 消息：5 則｜CMoney, Yahoo股市, news.cnyes.com｜最新：全球創舉！凱基金推首檔連結台股ETF 的虛擬代幣kTW50
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 偏熱，追價風險升高
- 近 7 日新聞：
  - [全球創舉！凱基金推首檔連結台股ETF 的虛擬代幣kTW50](https://news.google.com/rss/articles/CBMi1wJBVV95cUxORC1zaUNRMnIwY01LUWR2UE8xelE0U2pheUN4RTRhSGMtNmVMNG5LLU5NSWJUWGtqclRuT0VHNWs4MVBfNmlBRzZETnNObUpqdHBZUUxPMTd0d0tqT01fMC1Qd0QtNk1fSXRqOGFLaUNxTUJzdnFFMVQtQ052N1JFbGJhbS1WMXVhWFpPNUJYYW54dVdNLURGaFdKTHFDMW5WSW9KcXZ6ZV9DLXRacXl0VWJ0Z25uRW80aXU1YkNKZmlVSklTdXZSdTlEN1lZSDdhV0prNk95ZTZfMkZkbzdkN1NJSWkxUENfM2gzU2tWaXB5em15Z2RwdE1mV0d1alhXU3hicHZNZng3OTgxSDdXVFNJUnpONnFOUktiN3hWSXNDa3pkcWQ4NW1jMnNwQmZrZll0VG9ER2lTQUliZmpsZF9JMUJLOVZ5QUlubG9tMXhUVVdEeHRJ?oc=5)（Yahoo股市）
  - [00919換股納入凱基金 股價昨日飆漲停、今盤中續飆逾9%](https://news.google.com/rss/articles/CBMiWkFVX3lxTFBMYXlZNUdDb3Vhb1FQdGJ4bzYweWYwd2VhbmUtc2toaUpCYUpOeXd0UE4tWGVzSjlyd0tzb2hZNGlBdlV3Q3AyZm1JeGhkZzA2WEZjSzNwaUx0d9IBX0FVX3lxTE84Q01wNjJrWXNsRU9GVWFjRzQ2V2d3SXUxQW5kcllFYXpfN0IxQVFIUXM2RFM0UllqaGc4WGE1N2ZneXI2cUZ5eHlsUGpZdFZUUUtZb2RSMUQxN2o1RHdv?oc=5)（經濟日報）
  - [〈凱基金法說〉凱壽上半年台股投報率飆38% 打造信義區旗艦康養住宅](https://news.google.com/rss/articles/CBMiT0FVX3lxTFBLVjBkOEtzZmctaTE4YVlYRFJWdG14X3ZsSnowcjFqYnVaNDdmT0RxQzhZaWRKSGRUZWMxQmI2SkwxWEw3eS1za1Z0MkhITU0?oc=5)（news.cnyes.com）
### 群創（3481）｜面板 / 顯示器
- 技術分數：89/100（偏多）
- 收盤：49.95，日變動：2.99%
- 均線：MA5 48.98 / MA20 48.39 / MA60 53.93
- RSI14：51.70；MACD hist：0.46；量能比：1.20x
- 目標觀察價：52.40；支撐觀察價：48.50
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：下影線轉強，短多排列；位於 20 日區間中段，等方向表態。
- 基本面：EPS 0.57（2026-06-30）；TTM EPS 0.78；PER 62.18；PBR 1.72；殖利率 2.06%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、短均線優於月線
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
  - 消息：5 則｜CMoney, FTNN 新聞網, cmnews.com.tw｜最新：3481群創 | 「量增突破、驗證情境 A」的強勢反彈格局
- 訊號：站上 MA5、站上 MA20、短均線優於月線、RSI 位於健康區間、MACD 柱狀體偏多
- 近 7 日新聞：
  - [3481群創 | 「量增突破、驗證情境 A」的強勢反彈格局](https://news.google.com/rss/articles/CBMiWEFVX3lxTFBJZHF6SWp4dTlkYTlWUnRfTy1aaWtzdUxKNVpsT19FQ2NEVDhCT1dKS3pyQTZteWJDOF9pNS1tNHdBRmZZeWpWMm1IalhuY1V3WmVvWm1lYi0?oc=5)（CMoney）
  - [【即時新聞】群創(3481)沾AI爆量大漲6%！專家點出這隱憂，後市還能追嗎？](https://news.google.com/rss/articles/CBMikAFBVV95cUxPUVYwNUdoZ19sS0Rsa01qYnRYeDV4b1Q4NGdmYjhURDRkaXdfbVhjaGtVZjhVYTNNQldGbUIycjNRZWxwdjZRSlBfOFQ1eUZGQXVpVWM0UFJhaU0yMWJSOTBGN1F6c1d3cEowM08xMDZSR2Q4QW1idF9PV0NVOXVvem5iVnNvSUFyUVlaSTB1LUI?oc=5)（cmnews.com.tw）
  - [群創驚魂一日！跌停後急拉反彈 網嘆「散戶被玩到體無完膚」](https://news.google.com/rss/articles/CBMiWEFVX3lxTE5IeFlBaXlaTUJ1WnZBY0ZJcVhTWXRiTGNfVGtCS0lZRUM3WDREVExydUx6YWppX1hsdlRKd016eWlsYzJfM2xyX1gzOGhEQUlTZTBhYmt4Y24?oc=5)（自由時報）
### 日月光投控（3711）｜封測 / 半導體
- 技術分數：89/100（偏多）
- 收盤：621.00，日變動：5.61%
- 均線：MA5 599.40 / MA20 602.65 / MA60 618.38
- RSI14：56.47；MACD hist：1.52；量能比：1.51x
- 目標觀察價：643.00；支撐觀察價：603.00
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：長紅偏強，站上月線；位於 20 日區間中段，等方向表態。
- 基本面：EPS 4.80（2026-06-30）；TTM EPS 13.92；PER 42.55；PBR 6.64；殖利率 1.12%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60、量能放大 1.51x
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
  - 消息：5 則｜BigGo 財經, TradingView, cmnews.com.tw｜最新：【零股排行榜】盤中零股排行榜TOP 20｜0050 元大台灣50、2327 國巨*、00981A 主動統一台股增長、3711 日月光投控、1303 南亞 (0831)｜豐雲學堂2026 年 09 月
- 訊號：站上 MA5、站上 MA20、站上 MA60、RSI 位於健康區間、MACD 柱狀體偏多
- 近 7 日新聞：
  - [【零股排行榜】盤中零股排行榜TOP 20｜0050 元大台灣50、2327 國巨*、00981A 主動統一台股增長、3711 日月光投控、1303 南亞 (0831)｜豐雲學堂2026 年 09 月](https://news.google.com/rss/articles/CBMi0ARBVV95cUxOeTBSRkRJb0xuOVQ4ZzBIeFRjNS1qRGZXREFEOE5oTzUtdnZVVXZrZFZPOVhSbVUyQ2I5czFkTlFkMzk5ckVQdzhPalc4bHlINndnWk9uS3BmelM4Qnd0M0lYV2h4WHZNd3pNeVpJTHppbkN4Y3hWMndqSlZseG5ldmhsRVU3eDBoUTFfN0RjVW9Da0JIQmh0SGVXeG9ycDBNX1VWVDF4OUJpSkd6T1FLNjR2M1FSTUZ6U2dkLWd5NWxNVV9HTHQ4Xzgxd2haaUduSjNVajVodXhYVjgxYXFWTGZOZmE3V1VQcDVpbENjMGJkVGVORXFxNDczdGhRQUZNXzh0NTI4eWk5T244aHlqTG5IRUJmQk9hOWxOTGVpQWJBWWpvdjl6ZWtKY3BWTXBLdFdsNGdPOF9Gb0t4anpZajhscXNNTVgyclY1T2lqSGxFaXJwcXpMbDVweHR5LTMyWDhQemdJT0tnQUtaLXRnbUg4Y1RQWDNQX2w2ZkVtRE53QUc0LXo1eS1jdlNpdUhvbW9RSF9SU1NLMTl0WG5kS0oyVng3SlQ5bHR3TUZjZFJybGc2dHI0ZUpsOG9jcTBONkV5aHdLQWZROGVpbEItWjl6cnBiVkpQTVZuSURfTWszeXpCQ3ljVXp4aHA0OG0zTThIbC13dmV5RXdzM3ZhY2ZFRi1fcUIzaW0zZnVFRGFlR01WVkRzMnBhekpSZ0N2NVZJVGhEUlpXWFE5NEktNEQ3WUE1M2tTcnZ3QjYzRGVlZTRYVVc2b2NmbWRqV2Ns?oc=5)（sinotrade.com.tw）
  - [日月光投資控股股份有限公司 | 3711.TW 股價走勢與即時報價](https://news.google.com/rss/articles/CBMiVEFVX3lxTE5rcDdudXVRTEdqQl90eU9UVlFTREdoMml5WmYwZTJ4NHRNTGJiRi1IcG8zZmQ3SXphZTd2cUhLNGt4MDg4Q1ZqVHU1ZTNYa3l6YWV0RQ?oc=5)（BigGo 財經）
  - [日月光投控大漲立馬翻臉慘摔！兇手抓到了 36萬股東心碎](https://news.google.com/rss/articles/CBMiX0FVX3lxTE94TW92WVpyN2xlei1oRnFZQVpsREpKWGJQMm0yQ2JDaC1KRVpyclQzODdkbmd2S0dnRFZPSTY1WkpzSF9zOTRRX2RKU0E3Sk5BQ0hfaGlOWmpxOTh5WGJR0gFkQVVfeXFMTkpVNU92M2xYX2stcGlVa1VRMGtYOXk1cHhyc1NKVVhvZUI2dXhPOFRHQmZ5RFJSRlVuQTJRN0dad3pQLTVHWmZVR19FQ0tTWkt6cWxScVhlUlB5R2F4S3pLZXh5QQ?oc=5)（自由財經）
### 磐亞（4707）｜化工
- 技術分數：42/100（中性觀察）
- 收盤：28.30，日變動：-5.98%
- 均線：MA5 30.50 / MA20 32.26 / MA60 31.04
- RSI14：35.44；MACD hist：-0.57；量能比：0.94x
- 目標觀察價：32.25；支撐觀察價：28.20
- 目標依據：目前在 MA20 下方，目標先看能否站回月線。
- K 線：長黑偏弱，短空排列；接近 20 日低檔，先看止跌與量能回溫。
- 基本面：EPS 0.43（2026-06-30）；TTM EPS 1.28；PER 23.33；PBR 1.47；殖利率 1.66%
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
- 收盤：175.50，日變動：-1.40%
- 均線：MA5 179.80 / MA20 167.30 / MA60 173.77
- RSI14：58.54；MACD hist：2.10；量能比：0.61x
- 目標觀察價：197.00；支撐觀察價：167.50
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：一般 K 線，站上月線；位於 20 日區間中段，等方向表態。
- 基本面：EPS 1.42（2026-06-30）；TTM EPS 4.13；PER 43.20；PBR 4.54；殖利率 0.67%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 有訊號
  - 技術：站上 MA20、站上 MA60、短均線優於月線
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
  - 消息：1 則｜BigGo 財經｜最新：【聯策FY2026 H1 法說會】7月營收年增128%創新高聯策攜手Brooks切入FOUP檢測、玻璃載板AOI亮相SEMICON
- 訊號：站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間、MACD 柱狀體偏多
- 近 7 日新聞：
  - [【聯策FY2026 H1 法說會】7月營收年增128%創新高聯策攜手Brooks切入FOUP檢測、玻璃載板AOI亮相SEMICON](https://news.google.com/rss/articles/CBMiZkFVX3lxTE9fa203MnZ3NzdqQjV4QS1kQVZ2a0lGQkp2T0RfYjBqOGI2dHA4X1VyV2ptYVdXSHg2bFVqUDRTODBIeWx3R0JKdlVheUpJeTZaWUp1RVpSdFg1OWVlU3FHSXNyeGtPdw?oc=5)（BigGo 財經）

## 風險提醒
- 新聞來源以公開 RSS 搜尋為主，可能有延遲或誤配，正式版需接 FinMind/Fugle/券商 API 做校驗。
- 技術分數只反映量價結構，不代表未來報酬。
- 盤中盯盤目前走 Yahoo best-effort；正式版建議升級準即時行情 API。

本內容僅供資訊整理與研究學習，不構成任何投資建議或買賣依據。

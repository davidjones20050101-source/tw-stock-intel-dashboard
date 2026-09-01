# 台股 AI 情報官｜每日晨報 MVP

產生時間：2026-09-01 15:42
自選股數：14｜新聞數：48

## 今日 3 個觀察重點
- 台積電（2330）：交叉分數 112；技術 97/100（偏多）; 消息 5 則; EPS 為正
- 聯策（6658）：交叉分數 112；技術 97/100（偏多）; 量能 3.01x; 消息 4 則
- 凱基金（2883）：交叉分數 111；技術 92/100（偏多）; 量能 1.26x; 消息 5 則

## 五面向 Agent 交叉驗證

> 分數只採用目前已接資料：技術面、基本面、消息面。籌碼面與期權籌碼先明確標示為待接資料，避免假裝有訊號。

### 台積電（2330）｜交叉分數 112
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60
- 基本面 Agent：可參考｜最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：高熱度｜5 則｜CMoney, Yahoo股市, cmnews.com.tw｜最新：【零股排行榜】盤中零股成交量TOP 20｜0050 元大台灣50、1303 南亞、2330 台積電、2609 陽明、00981A 主動統一台股增長(0826)｜豐雲學堂2026 年 08 月
- 期權籌碼 Agent：待接資料｜尚未串期交所 OI、P/C Ratio、Max Pain、IV；目前不作方向判斷。
- 綜合判讀：技術 97/100（偏多）; 消息 5 則; EPS 為正

### 聯策（6658）｜交叉分數 112
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60、量能放大 3.01x
- 基本面 Agent：可參考｜最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：有訊號｜4 則｜CMoney投資網誌, sinotrade.com.tw, ww2.money-link.com.tw｜最新：家登創投參與 AOI 廠聯策私募 累計持股2,137張比率達5.57%｜新聞快訊｜豐雲學堂
- 期權籌碼 Agent：待接資料｜尚未串期交所 OI、P/C Ratio、Max Pain、IV；目前不作方向判斷。
- 綜合判讀：技術 97/100（偏多）; 量能 3.01x; 消息 4 則; EPS 為正; 估值偏高需保守

### 凱基金（2883）｜交叉分數 111
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60
- 基本面 Agent：可參考｜最近一季 EPS 為正；TTM EPS 為正；PER 相對低，需查是否循環或一次性因素
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：高熱度｜5 則｜CMoney, Yahoo股市, news.cnyes.com｜最新：凱基金(2883) 個股概覽 | 個股 - 股市
- 期權籌碼 Agent：待接資料｜尚未串期交所 OI、P/C Ratio、Max Pain、IV；目前不作方向判斷。
- 綜合判讀：技術 92/100（偏多）; 量能 1.26x; 消息 5 則; EPS 為正

### 富邦科技（0052）｜交叉分數 109
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60
- 基本面 Agent：資料不足｜ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：有訊號｜4 則｜CMoney, FTNN 新聞網, 經濟日報｜最新：高含「積」ETF 長線俏 0052、0050、006208等掌握成長契機
- 期權籌碼 Agent：不適用｜個股/ETF 報告暫不做期權解讀；台指選擇權可作大盤溫度計。
- 綜合判讀：技術 97/100（偏多）; 量能 1.39x; 消息 4 則

### 主動群益台灣強棒（00982A）｜交叉分數 109
- 技術面 Agent：偏多｜站上 MA5、站上 MA20、站上 MA60、量能放大 1.99x
- 基本面 Agent：資料不足｜ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
- 籌碼面 Agent：待接資料｜尚未串三大法人、融資券、借券與集保股權分散；目前只列為下一階段，不納入分數。
- 消息面 Agent：有訊號｜3 則｜CMoney, FTNN 新聞網, 今周刊｜最新：8/28 00982A 台半堆到 6484 張
- 期權籌碼 Agent：不適用｜個股/ETF 報告暫不做期權解讀；台指選擇權可作大盤溫度計。
- 綜合判讀：技術 97/100（偏多）; 量能 1.99x; 消息 3 則

## Agent 建置順序
1. 籌碼面：先接三大法人、融資券、借券、集保大戶持股，做每日異常警示。
2. 技術面：沿用現有均線、RSI、MACD、量價結構，強化支撐/壓力與訊號分級。
3. 消息面：保留原始連結，加入重大性分級與假消息交叉查證。
4. 基本面：從個股 EPS/PER/PBR 擴充到同業比較；ETF 改接成分股、折溢價與配息品質。
5. 期權籌碼：接台指選擇權 OI、P/C Ratio、Max Pain、IV，作為大盤溫度計，不當單一進出場訊號。


## 個股追蹤

### 富邦科技（0052）｜科技 ETF
- 技術分數：97/100（偏多）
- 收盤：63.05，日變動：1.94%
- 均線：MA5 62.22 / MA20 61.30 / MA60 60.99
- RSI14：60.00；MACD hist：0.20；量能比：1.39x
- 目標觀察價：66.00；支撐觀察價：61.80
- 目標依據：已接近短壓，改看近 60 日高點壓力。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：4 則｜CMoney, FTNN 新聞網, 經濟日報｜最新：高含「積」ETF 長線俏 0052、0050、006208等掌握成長契機
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：
  - [高含「積」ETF 長線俏 0052、0050、006208等掌握成長契機](https://news.google.com/rss/articles/CBMiWkFVX3lxTE9Na1FLVDJrM1gzTHN3RnV6OTV5ZXRHcmtwMnBXQlhJcklESG1aYTQxbnpMTGZzaDBETnFKcXB2WEF5ekdrdmQ5RFI2ZE81VTdjc2F6Qy05UUVEQdIBX0FVX3lxTFBGZ1ViVmtfWE91VlU1R1RWd0VCMGpEUC10bk5pOHduZzg4eURVSlF2WFRlbFFuNTE1WjVHTHRHdnlzR1FpVzQzbDl2bmFQQ0czcjZ2TWJYTC1ud2pjbnJF?oc=5)（經濟日報）
  - [富邦科技(0052) 個股概覽 | 個股 - 股市](https://news.google.com/rss/articles/CBMiU0FVX3lxTE04cjNnZVhpZWhiVVRZWUNld3NOZXhVaGIzazVYRXlwLVpqaGdkV3YyU0twcERJNi1FSURwblk4NS13NUdmTWdRS2NWLVFMaTl5RG5J?oc=5)（CMoney）
  - [0050、0052準備換股! 散戶搶搭便車聚焦這五檔個股](https://news.google.com/rss/articles/CBMiX0FVX3lxTE1HaEc5N2VDeFBZbUZrcWZhQzloMjhNRnNocEJqT3Axa3JjRFZkU0oyem1GdXFNQTJoblpTdDdLNVllSG12R2NPRGltZEhIWXkwcDNnNFdWOTl4WWgwaElr?oc=5)（自由財經）
### 元大高股息（0056）｜高股息 ETF
- 技術分數：92/100（偏多）
- 收盤：54.85，日變動：0.46%
- 均線：MA5 54.03 / MA20 52.74 / MA60 51.75
- RSI14：70.87；MACD hist：0.22；量能比：0.88x
- 目標觀察價：55.20；支撐觀察價：54.60
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：十字線，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：4 則｜CMoney, Yahoo股市, cmnews.com.tw｜最新：高股息接棒漲 0056規模衝破6,000億元關卡
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、MACD 柱狀體偏多
- 近 7 日新聞：
  - [高股息接棒漲 0056規模衝破6,000億元關卡](https://news.google.com/rss/articles/CBMiWkFVX3lxTE9jZkpMODlCX2ZtRmMyRm80MTRQSE1JNW8yclNZaWt6LUtmLTIzNDBkN0QwQlJnSUZjd1RPVW5lOWhfS2lKT0EtRFVVYThMSnR1QmtsalNfeXJnUdIBX0FVX3lxTFBTMkhUeEg1bUlwVk1JU0xmRkJLbm5MT0dKNW9pSTRmNmlTQnNQY1hIenJwRWM2SGxNby1CbDIydWlRWnZkajJzbWViczVZRkFmaTYzOUlqNzZpT3B6eDVr?oc=5)（經濟日報）
  - [0056 元大高股息- 今日最夯ETF／台股震盪收黑0056突圍創新高- 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE90ZmQ4TjJrVS04dUhCTVFFT0c3YWl5V0llbFNRVzNNRXQ0bmZ2aU5mUF9fYm1EOGRqU3pxQ1BLQ3M4eTduUXNzSTJXeEdaTWt2UGtsOExPejc?oc=5)（CMoney）
  - [【台股ETF五天王】一表看0050、00878、0056 等最愛買什麼？全撞「這2檔」！](https://news.google.com/rss/articles/CBMiqwNBVV95cUxOc3QtMVFfQ2FYcEpwcXdiWktncnRQU2hEdmhpSnNJUWZYbzMwTjdfTnFUV2k3RU52NEk0Z2haMFRndk1QVXFmWWFNeFVXemkxOXdjY2R6VUtsOS0xQVZQdkstZG1IOVlqOERwTEp0N280R2t3VVZWbXFDU29mRnNMQzZxN3VPX1FhUXc4MldWVzdUUS1zUlpJMG05b3Uwb0x3d3R5V01zVVlYb3YzbGtkeDRuNVZBbUlFNFh1QmFzLW5uOTJEdk9SRzlpYmM5WlIzMl92ZGo1V2JCM3l0RHh5RFBNZDQySzdPOE5TN2F3bG9sZkNfY0FBN2IzcEo0Q01HVFpCV0c4S1A3VGwydHZsR0Z2bGdDVFpEZkZEX1R6U09NbnRySUVTcTVyUnNPaDZtdHlpNExRejdsdXJzT1VNcmFaWmhWV3dRVml4TFRiSVBWTGpmOHRXclpNLW52M2dXTXMxWnNoTEhUMU11Qkp1WV85VXNud1FqbXJtM2pZTC05dm9PV3F1YjlDRnE4M01FelJkUVhsbE8yd0ZQdDVKZnVpZDB1N0o2aU4w?oc=5)（Yahoo股市）
### 中信臺灣智慧50（00912）｜智慧型 ETF
- 技術分數：97/100（偏多）
- 收盤：35.24，日變動：1.56%
- 均線：MA5 34.70 / MA20 34.08 / MA60 33.43
- RSI14：64.34；MACD hist：0.09；量能比：1.30x
- 目標觀察價：36.20；支撐觀察價：34.70
- 目標依據：已接近短壓，改看近 60 日高點壓力。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：1 則｜news.cnyes.com｜最新：萬金股行情帶旺00912、00406A 重倉布局信驊、川湖
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：
  - [萬金股行情帶旺00912、00406A 重倉布局信驊、川湖](https://news.google.com/rss/articles/CBMiU0FVX3lxTFBCUkdPTGNEbUF1SURSN2dMdXRJWF9taDJIaW9qU3A2eGEzQnNxWVh5RjZ1Wm1jLUUtS1oxNkx4NDdoVkJhYnEzRlJfcW1MU0tmcENF?oc=5)（news.cnyes.com）
### 群益台灣精選高息（00919）｜高股息 ETF
- 技術分數：84/100（偏多）
- 收盤：32.31，日變動：1.10%
- 均線：MA5 31.65 / MA20 30.64 / MA60 30.00
- RSI14：84.87；MACD hist：0.16；量能比：2.10x
- 目標觀察價：32.75；支撐觀察價：31.95
- 目標依據：已在近期高檔，改用 ATR 波動推估下一段觀察價。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60、RSI 偏熱，避免追價、量能放大 2.10x
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：5 則｜CMoney, ETtoday財經雲, 數位時代｜最新：百萬國民高股息 ETF 00919成分股調整名單出爐 18進18出
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 偏熱，追價風險升高
- 近 7 日新聞：
  - [百萬國民高股息 ETF 00919成分股調整名單出爐 18進18出](https://news.google.com/rss/articles/CBMiWkFVX3lxTE51WTFZdlItVnpxY2hKZnZsdzF2Y29RbDJLVUthTzU4cTRMZG5WVlN2SDhpTlQ0MkJmR0tkMDRSeWhJLXF2Y0pyNGRqNHFHbkVkQzVteG5DRV84UdIBX0FVX3lxTE5TTFFDck8tdGY1Vm5PZTVrM2tpLW9YUXRLZThlWFlYc1FWcjhOY1ZGLTRkZGdTUXZtTkpTR2xyTVo4eFVWUDhYWjRqeTlDNlNGYU5uOGtBNzFzTmRQdTJ3?oc=5)（經濟日報）
  - [00919 群益台灣精選高息- 台股ETF 發股息新一波聚焦八檔公告第一階段金額檔檔飆高- 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE1tSkFabXNtLWdYSnJCY3dYTUp2QTRjSkFUQTRRYWhJUlM1X1hWVTYzRUVLX095QXAyR292TU9TYXVJeUdNN1k5Mll1Y3NlVEU5cVNYMEo2Mlk?oc=5)（CMoney）
  - [137萬投資人注意！00919配息1.1元連3季創新高 年化配息率近14%](https://news.google.com/rss/articles/CBMiS0FVX3lxTE1mbGw3eVV6dWxsczVEWmZuWTh4bXU2Q0pOYzVWNEE3WWdnbEpCanpxdEF0YUpfVnRNUjBTMGNoWlFza0MwSjJxNUlwQQ?oc=5)（鉅亨網）
### 元大台灣價值高息（00940）｜高股息 ETF
- 技術分數：84/100（偏多）
- 收盤：12.93，日變動：1.17%
- 均線：MA5 12.74 / MA20 12.52 / MA60 12.38
- RSI14：76.60；MACD hist：0.04；量能比：1.18x
- 目標觀察價：13.10；支撐觀察價：12.80
- 目標依據：已在近期高檔，改用 ATR 波動推估下一段觀察價。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60、RSI 偏熱，避免追價
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：4 則｜Yahoo股市, sinotrade.com.tw, 旺得富理財網｜最新：9月配息ETF一表看！00939、00940、00406A率先登場，除息日、配息金額與熱門高股息ETF比較！
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 偏熱，追價風險升高
- 近 7 日新聞：
  - [9月配息ETF一表看！00939、00940、00406A率先登場，除息日、配息金額與熱門高股息ETF比較！](https://news.google.com/rss/articles/CBMizwNBVV95cUxOSUVNaDlmRnhGWTRNQXd3ZlNfdDFiNGlKcjhtNy1raE50SkI1MWRtVDlESklWaFN4UWw5Z3VXVFd2Ym1jYjFlQzNwNUszbFpFaEVFRjAxbzFVLUZlVmh1X1BmelJDUldJTW1jRENNWDF2MEFacEpCV0Q0ejdCTlU3VWV1MDlCeFVKRVRVZXh0Y19uLWFsX25GVzdzSWdpaHh6OWJWWkktUmNLUjJZeUZRX3p2aWctM2NHRjV3MFMxaF9WV1lEaGlzNmJRYWtOS3RkN0VhbU1OMEVZOVRCY2NhYnBEX1hpaHlUbkJ5TFFJdHQ2ZTRqdXBBVzZnN2RERHRpemdJbHZILU8zTnhhbmJPOGlZdlp1cGZqcUczRC1kRWQyOF93SV9pX2dlenB5dkJPUFJpNVdpMTQxX2UxcFV4R3pvdnd6WEhmTWsydnBJUFF5TFZZYUxGMW10aTl2U0xTUUhDc2J1TTdsd0FfQngzaklfV09VaE9CWFFaM2h6Z1JRX3U5b3NwWWNXYmNMcEU3ZjZzWE03VlpzNHRBTjZzQjV3R2pHbS13NGNvVFFra0c2NU83ckhaZldCTjlicjA0ckd5OWkxRHFYSjRNTXNv?oc=5)（sinotrade.com.tw）
  - [00940要衝13元、配息也創新高！32萬人還能抱？達人搖頭：存這3檔CP值更高](https://news.google.com/rss/articles/CBMikANBVV95cUxNRTR5V1FvNFp6clJMd3paWFJPQU81dFE3c0Q5NVpWWGEtZmxROHJXclZ3U1A4MzZZbjBxaG5PelhwdWR1dm5jSV9VNlBNSkVtYUJTMzgyd3AyMnJqNlIyOFktUUcwbnJzX1ZaTlMtVmN1WUQ1ZmlDS1lya014VlhYendxOHZMa3dDOW5OSTJHRHdwM2lEQWpFM0k2YXpmZmhkY2Y3UHpUTHBZSUpnM0tORUdmVmo0YTRnNzQzN2JfVlBOU1dUZVNxa3pjc1dnb1FxZmpGQXAyMHQ2VGFnaGtuOWFPVjE5bjhVbnVLVGY4U2pxakN6RFZVam4zVTRTT2k2SGlES0tEaXZ4MVVmeHF3eDJHQUdkQXRQVkpSNFgtVUVVSXhOSXJYR0xubDJyTTY0RnlsTlBZZXFyWHAtd1o1SWY2Mkt5c24yWHdzZFRqSGhobm9YeVhJZVF2QllOZ3docEtkRDg2RXFrTG1xbmtyNHVMMldjcFltVDVfejNQYzVaZDJrZmh3LTlXSjdvWnU4?oc=5)（Yahoo股市）
  - [00940單月配息數字再現0.05元 年化配息率逾5%](https://news.google.com/rss/articles/CBMiWkFVX3lxTE5uNVhHekpYS3hFaHdsQUY3QmdKa05rYVRwZHd4WUJIa3V4Ui0wODcxVGV4d242Y1lMaGdMU1RoRDVUb0ZMbmE2UGhjc3JxMHdBUXZWZ2g0X05wUdIBX0FVX3lxTE13dy10ODJacV9jRXZBR2VrcHVFMFVoTVNlTWozbUFzTTZIS0RrVGk0MzdIa0RGdE9wTmNqd3ZDdW1RMDY5UDRYUnRzbjc3M2xsbVlkd0FjbmRtNDV2Slk0?oc=5)（經濟日報）
### 主動群益台灣強棒（00982A）｜主動式 ETF
- 技術分數：97/100（偏多）
- 收盤：23.34，日變動：4.24%
- 均線：MA5 22.56 / MA20 22.41 / MA60 22.88
- RSI14：54.92；MACD hist：0.13；量能比：1.99x
- 目標觀察價：23.55；支撐觀察價：22.40
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：ETF：EPS / PER / PBR 不適用；殖利率 資料源暫無
- Agent 快讀：技術面 偏多｜基本面 資料不足｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60、量能放大 1.99x
  - 基本：ETF 需改看成分股、折溢價、配息與追蹤誤差；目前不納入估值分數。
  - 消息：3 則｜CMoney, FTNN 新聞網, 今周刊｜最新：8/28 00982A 台半堆到 6484 張
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：
  - [8/28 00982A 台半堆到 6484 張](https://news.google.com/rss/articles/CBMiWEFVX3lxTE40M0FodF9PMzRJeFpFQVBkaTNkNjNjZzE0dlpCR1RwNlFLQVBjeUJiNnBtSTBfM182d1A2SExoNUc3bUZnZm5FRkFxZHgzall5cGx3UFZPVmM?oc=5)（CMoney）
  - [00982A、00992A、00400A、00900…大立光可能變萬金股！12檔含「光」ETF出列，達人一理由：我會看它](https://news.google.com/rss/articles/CBMigAFBVV95cUxNdFBya1VSZndfa2NRWVhmY1hPMDZleDd4UmZ1YVJtYVpmVktjRm8xd2xGMmV6bk95eVo5YXZYVDdia1k4cFVGUjl6dWtoSDE1VUxYYmhJdGN4Z0tIUUlmQ2lkQzUtLUdsNUVUMERKM1lWblQ5OTkwN1pwU0VDTEUtQg?oc=5)（今周刊）
  - [擁緯穎、聯發科、穩懋齊亮燈！00982A拚11個交易日填息「盤中暴漲4.82%」 18萬股民這天領錢](https://news.google.com/rss/articles/CBMiS0FVX3lxTFBBZHZRZXdHbWhnX2RaVEtidmNKbV9wcEt1R21VUzZnd08xeDN4QmNNSG84clcyYXdEc3J0NEZaRmtMNGdtMVkwbzBWaw?oc=5)（FTNN 新聞網）
### 中纖（1718）｜化纖 / 紡織原料
- 技術分數：89/100（偏多）
- 收盤：11.15，日變動：2.29%
- 均線：MA5 10.84 / MA20 10.60 / MA60 11.17
- RSI14：48.65；MACD hist：0.10；量能比：2.11x
- 目標觀察價：11.95；支撐觀察價：10.90
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：一般 K 線，短多排列；位於 20 日區間中段，等方向表態。
- 基本面：EPS 0.29（2026-06-30）；TTM EPS 0.59；PER 18.47；PBR 0.61；殖利率 0.00%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、短均線優於月線、量能放大 2.11x
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
  - 消息：1 則｜CMoney｜最新：1718 中纖 - 今日10.8買進等待後市，期待😊 - 股市爆料同學會
- 訊號：站上 MA5、站上 MA20、短均線優於月線、RSI 位於健康區間、MACD 柱狀體偏多
- 近 7 日新聞：
  - [1718 中纖 - 今日10.8買進等待後市，期待😊 - 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE1SOTcxdzZZZm56LURGNDZQSFRISWU1Qm53MWMtLWUtdjJnN0YtVXNIRnlxM1daNHJVT1BLUElnTS03enN1MWl1Si1lTE9IeGwxOXFZWUNlVEc?oc=5)（CMoney）
### 台積電（2330）｜晶圓代工 / AI 權值
- 技術分數：97/100（偏多）
- 收盤：2440.00，日變動：1.46%
- 均線：MA5 2418.00 / MA20 2397.00 / MA60 2385.25
- RSI14：53.97；MACD hist：4.48；量能比：0.90x
- 目標觀察價：2535.00；支撐觀察價：2405.00
- 目標依據：已接近短壓，改看近 60 日高點壓力。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：EPS 27.25（2026-06-30）；TTM EPS 86.28；PER 27.88；PBR 9.70；殖利率 0.91%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
  - 消息：5 則｜CMoney, Yahoo股市, cmnews.com.tw｜最新：【零股排行榜】盤中零股成交量TOP 20｜0050 元大台灣50、1303 南亞、2330 台積電、2609 陽明、00981A 主動統一台股增長(0826)｜豐雲學堂2026 年 08 月
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：
  - [【零股排行榜】盤中零股成交量TOP 20｜0050 元大台灣50、1303 南亞、2330 台積電、2609 陽明、00981A 主動統一台股增長(0826)｜豐雲學堂2026 年 08 月](https://news.google.com/rss/articles/CBMitwRBVV95cUxOdDVnUDU3THRNN0JqWC1mU21DNXIwRnBobHR5dkRJTlQ5SlU0MFVvR01VN1pwdkhrbFFNRkZUbHhrYlFDRmd6dlZlS3RGaUtOSDFGakt2WUdJWUp0V0tQZU1Yd042RWtLZmtqZGNzVjk0eDlrZldHLW1TOVhWU0x1WXNtb2xnX1dYWTR6NGdONW9Scy1WTVhyakduQWJuVFFpUzBma0dKM2ZOMWFXR25nejN2bHVDODNzOTVzNTQ5NGJ1ZnRHd1dLS0lqbWh0ckhUa1NLUkxmeEpTcXUxSktPdjgwWHBpbWJLV1JNXzFfUkNqYUZ3ZzJXZnZvcW9HWlRPeVZ2dzhmdE1wbFJMMjdkWF9OUW52VFhOT0Z1bkxoRGRTb01JbzZxVlV2UFVaSHpYbmFEZmZubl9KMW5ja3ZZVkFaUGVmNk9xbUxtampPemNBcERKTldVRUZWWHdnOE83bTBNbnlRMFZBOFFFMEtzWllzVlc4MTJhR1d5MVhIS1M0YW50TEhOY3RVRVh3Q0pZOHE2aWxrWHltaWtfeFVQb1ZTX2ZoVzBraEVNdXlEWmpnRzdBTXRHVVRURE1OMUx6WGQ1ekNuTmNoaXVoRlZpN3JoSVNfWklvU096bmpqbDZzc3ctM0NmT0tkbUhqMG9zUnpoa21Od2V3WHBkY2FzeEMyUGJZcUN4YUJpUjhRQUtlMTBoN3M1aGpSNnMwNjlZdkM2SU1zVkhkSEJlLXlFMFM0SEVwVDA?oc=5)（sinotrade.com.tw）
  - [2330 台積電 - 09/01 台股盤前：輝達砸35億美元認購聯發科，費半逆勢漲0.57%，台股AI能抗總經利空？ - 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE9ieXVRcHNMSGp5LWhXcHBsOWQtUTdnYUFwc3I3MWUxOFA5UTdmakRsa1AtTlJ3NUNRcFUzV1Zwd0VCZDBNeWxVQ1RrOXBmZktScmYtdmVEYkM?oc=5)（CMoney）
  - [買0050不如台積電（2330）？楚狂人公開復盤：別小看其餘四成持股威力| 存股族愛ETF | 股市](https://news.google.com/rss/articles/CBMiU0FVX3lxTFB1ZDlIbDU1VzVnLWh1SU90Unh6STNFWExNYWp5MlByaWw3NXItWThVeW1DU2tNYjRQVklZalUyY3NJbUJMMVEzNldQcG9HM2VZdTh3?oc=5)（udn）
### 統一證（2855）｜證券 / 金融
- 技術分數：92/100（偏多）
- 收盤：50.00，日變動：0.91%
- 均線：MA5 48.66 / MA20 46.92 / MA60 47.81
- RSI14：65.24；MACD hist：0.43；量能比：1.41x
- 目標觀察價：50.30；支撐觀察價：49.55
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：一般 K 線，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：EPS 1.33（2025-12-31）；TTM EPS 3.00；PER 5.15；PBR 1.65；殖利率 4.26%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 相對低，需查是否循環或一次性因素
  - 消息：3 則｜BigGo 財經, 今周刊, 旺得富理財網｜最新：《金融股》統一證Q2獲利三級跳H1爆賺111億元締年度新猷- 上市櫃
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、MACD 柱狀體偏多
- 近 7 日新聞：
  - [《金融股》統一證Q2獲利三級跳H1爆賺111億元締年度新猷- 上市櫃](https://news.google.com/rss/articles/CBMiakFVX3lxTFBMc0sydGNqWUJEd2Y5TnhpOW1hcDRsdWJEWmhOT1RNajFFS002Ulg2MkIyT2d4MXJiWVVRWWQ3bEhwNzloVng2RlFOWW02OXFsRGc3NTBSM2c5bkdCVEkxNmRseks3OGl6d2c?oc=5)（旺得富理財網）
  - [【統一證 FY2026 Q2 法說會】上半年每股大賺6.96元 自營業務改寫單月獲利紀錄](https://news.google.com/rss/articles/CBMiZkFVX3lxTE9pajNjcnJQSE9SZEs2V21SVk1YcWxYQktGYkE1ZUxYMldDRlE2Smp6czNWRVdUNGJqOEdGcmIxajFKeTV2TDNHalhPcVNJa3U5YmdtN3djUVpjQlVNYmNYTzBfNGh2dw?oc=5)（BigGo 財經）
  - [存股助理第842期｜統一2026年半年報評析—統一證券扮演獲利成長大功臣｜股池更新](https://news.google.com/rss/articles/CBMikgFBVV95cUxNV0JZX3ZWb3NBdk9jTUZZYy1BbHRtOG5ab3pmbzJtUHVSd2FjVWFKcC0zdHZ5aVR4WGY0dEY4cm1Qc0UwM1prNk5iOUVQV2hyNWg5MUdfcmVZYzFZdUgwNldJMjVRclBLcjJWTkU5SDFKQU1IQjhpWm9uRFhKQW1xWHV2VmpTZy1VZ0lSYnExM0VjZw?oc=5)（今周刊）
### 凱基金（2883）｜金融控股
- 技術分數：92/100（偏多）
- 收盤：34.95，日變動：3.25%
- 均線：MA5 33.19 / MA20 31.64 / MA60 30.27
- RSI14：74.83；MACD hist：0.29；量能比：1.26x
- 目標觀察價：36.05；支撐觀察價：33.85
- 目標依據：已在近期高檔，改用 ATR 波動推估下一段觀察價。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：EPS 0.65（2025-12-31）；TTM EPS 1.74；PER 11.84；PBR 1.34；殖利率 2.95%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 高熱度
  - 技術：站上 MA5、站上 MA20、站上 MA60
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 相對低，需查是否循環或一次性因素
  - 消息：5 則｜CMoney, Yahoo股市, news.cnyes.com｜最新：凱基金(2883) 個股概覽 | 個股 - 股市
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、MACD 柱狀體偏多
- 近 7 日新聞：
  - [凱基金(2883) 個股概覽 | 個股 - 股市](https://news.google.com/rss/articles/CBMiU0FVX3lxTE5razMwcGM0azNqYW5MRDVOWVRHSnI0ZlhJNnFDekNVcURPdXZURGMzQUlPQ2h4dHhTTjczdGl3RDlqYk5KbDJWQTdYdnJYWU9OMkZv?oc=5)（CMoney）
  - [凱基金法說》72萬股東關心股利！總座：證券銀行上繳7成 人壽成長樂觀「不會掉隊」](https://news.google.com/rss/articles/CBMikARBVV95cUxQeGJlM0dGU1c5SFhxRDVxczNYVkxmdF9WdGl3aWNkM0d4eWVrWm1sN3N0WHRfeWJwbldSX2wwR2FZSzNfV1lFUWdUSXd3aXVDVU1lNk1UejdTRmR4Um9TNTVpZHp4QkZMbmpyQUZfbjRRVzd4TVlaMnlyMHNPakVvSWFOd01MQVNIeWY5VDZFQjJzUFVDWGMwa2gyQUpLbG44ai1JWUxQYWhROUU1UlZ1eHBnYUVFU0o5UEprYk91cmRLUkpUWEE0Z3FabGRGRzRfdzZ0REY5aTdOVGZEQng3MWphWXlobVg0aVdMODZHWEVaRU1YQ0VnSm5OZ182YnFTazlWb1E2RUZic0RtYVhWaXM1Q29lVHRaOEFUdWJ4dExlVnplUTBMVXVHTzVJNGdDU2pZZHEwamRDS2xDZzBNN1NnTE1UTHh5MjZQSTNYOExrWFgzQzJ5RW00MDNNX0dXM0pjSkZETzBMRlltZ0RYN2Z1YU40RThSaVBmUlFqNmxmRjI0cUl6Y3piVVpjeUtnUF8yTjc0Y29GTGNmLUV1ZUNLMmNTdGNwMUNXN0hJeVhNQnVyX21WNzBFbFB0ZWNWTTdxMmppRlN3V0V2dkVoNFp2dE9DU2RPa0VvWVlLVWRVSUVsVHdySjNaTmZkYnRyVHQ4UUM5S2hxUmJGM3lrZGE1QjAza0gwcHhsRUxSOUk?oc=5)（Yahoo股市）
  - [00919換股納入凱基金 股價昨日飆漲停、今盤中續飆逾9%](https://news.google.com/rss/articles/CBMiWkFVX3lxTFBMYXlZNUdDb3Vhb1FQdGJ4bzYweWYwd2VhbmUtc2toaUpCYUpOeXd0UE4tWGVzSjlyd0tzb2hZNGlBdlV3Q3AyZm1JeGhkZzA2WEZjSzNwaUx0d9IBX0FVX3lxTE84Q01wNjJrWXNsRU9GVWFjRzQ2V2d3SXUxQW5kcllFYXpfN0IxQVFIUXM2RFM0UllqaGc4WGE1N2ZneXI2cUZ5eHlsUGpZdFZUUUtZb2RSMUQxN2o1RHdv?oc=5)（經濟日報）
### 群創（3481）｜面板 / 顯示器
- 技術分數：81/100（偏多）
- 收盤：49.30，日變動：-1.10%
- 均線：MA5 48.08 / MA20 48.49 / MA60 53.82
- RSI14：46.26；MACD hist：0.46；量能比：0.62x
- 目標觀察價：52.30；支撐觀察價：48.50
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：長黑偏弱，站上月線；位於 20 日區間中段，等方向表態。
- 基本面：EPS 0.57（2026-06-30）；TTM EPS 0.78；PER 63.91；PBR 1.77；殖利率 2.01%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、RSI 位於健康區間
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
  - 消息：4 則｜BigGo 財經, CMoney, 工商時報｜最新：3481 群創 - 大漲老師終於群創了 https://youtube.com/... - 股市爆料同學會
- 訊號：站上 MA5、站上 MA20、RSI 位於健康區間、MACD 柱狀體偏多
- 近 7 日新聞：
  - [3481 群創 - 大漲老師終於群創了 https://youtube.com/... - 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE1TdDZvTk9laGU1ZTJmUi1ZcVZkdWxKNm1feEpNV1VvbFlsMnB1VUxrdnptTEFuNm05UnVpaGFiMTV6QnpwMzMyTzFRM3FHWU10cURlbWs2S2o?oc=5)（CMoney）
  - [群創光電 | 3481.TW 股價走勢與即時報價](https://news.google.com/rss/articles/CBMiVEFVX3lxTFBJSUJWaVg0Z0VlNmtudTBZUm9ZaGlRd2w2UEh5SV9ETGdHYkEyRUpKblhfY19xQWJMRWhWVXN1MmlmZlVJYzZLSFNuc1lKYUYxV0RuRQ?oc=5)（BigGo 財經）
  - [買群創身心受創？跌破50元後何時能解套？杜金龍看轉機、再點名3檔績優股- 證券](https://news.google.com/rss/articles/CBMiX0FVX3lxTE92R01SWEk5bGhITFYyM2RfaUpXaWZOT2VRaERLc3M0WTI0OE9tamNQdDQ2RHVOb2xtaXozTU1UZlZrREtjYmVPYUJ6OVhPZ3c0Y0VwYU9qdlg2OFJFWUhB?oc=5)（工商時報）
### 日月光投控（3711）｜封測 / 半導體
- 技術分數：81/100（偏多）
- 收盤：610.00，日變動：4.45%
- 均線：MA5 602.40 / MA20 603.45 / MA60 615.13
- RSI14：46.26；MACD hist：1.39；量能比：1.29x
- 目標觀察價：643.00；支撐觀察價：603.00
- 目標依據：取近 20 日高點作為第一壓力/目標觀察價。
- K 線：長紅偏強，站上月線；位於 20 日區間中段，等方向表態。
- 基本面：EPS 4.80（2026-06-30）；TTM EPS 13.92；PER 42.26；PBR 6.60；殖利率 1.13%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、RSI 位於健康區間
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
  - 消息：4 則｜CMoney, cmnews.com.tw, sinotrade.com.tw｜最新：【零股排行榜】盤中零股排行榜TOP 20｜0050 元大台灣50、2327 國巨*、00981A 主動統一台股增長、3711 日月光投控、1303 南亞 (0831)｜豐雲學堂2026 年 08 月
- 訊號：站上 MA5、站上 MA20、RSI 位於健康區間、MACD 柱狀體偏多
- 近 7 日新聞：
  - [【零股排行榜】盤中零股排行榜TOP 20｜0050 元大台灣50、2327 國巨*、00981A 主動統一台股增長、3711 日月光投控、1303 南亞 (0831)｜豐雲學堂2026 年 08 月](https://news.google.com/rss/articles/CBMi0ARBVV95cUxOeTBSRkRJb0xuOVQ4ZzBIeFRjNS1qRGZXREFEOE5oTzUtdnZVVXZrZFZPOVhSbVUyQ2I5czFkTlFkMzk5ckVQdzhPalc4bHlINndnWk9uS3BmelM4Qnd0M0lYV2h4WHZNd3pNeVpJTHppbkN4Y3hWMndqSlZseG5ldmhsRVU3eDBoUTFfN0RjVW9Da0JIQmh0SGVXeG9ycDBNX1VWVDF4OUJpSkd6T1FLNjR2M1FSTUZ6U2dkLWd5NWxNVV9HTHQ4Xzgxd2haaUduSjNVajVodXhYVjgxYXFWTGZOZmE3V1VQcDVpbENjMGJkVGVORXFxNDczdGhRQUZNXzh0NTI4eWk5T244aHlqTG5IRUJmQk9hOWxOTGVpQWJBWWpvdjl6ZWtKY3BWTXBLdFdsNGdPOF9Gb0t4anpZajhscXNNTVgyclY1T2lqSGxFaXJwcXpMbDVweHR5LTMyWDhQemdJT0tnQUtaLXRnbUg4Y1RQWDNQX2w2ZkVtRE53QUc0LXo1eS1jdlNpdUhvbW9RSF9SU1NLMTl0WG5kS0oyVng3SlQ5bHR3TUZjZFJybGc2dHI0ZUpsOG9jcTBONkV5aHdLQWZROGVpbEItWjl6cnBiVkpQTVZuSURfTWszeXpCQ3ljVXp4aHA0OG0zTThIbC13dmV5RXdzM3ZhY2ZFRi1fcUIzaW0zZnVFRGFlR01WVkRzMnBhekpSZ0N2NVZJVGhEUlpXWFE5NEktNEQ3WUE1M2tTcnZ3QjYzRGVlZTRYVVc2b2NmbWRqV2Ns?oc=5)（sinotrade.com.tw）
  - [3711 日月光投控- 日月光跟力成FOPLP的比較，力成起步較早，感覺技術是不是... - 股市爆料同學會](https://news.google.com/rss/articles/CBMiWEFVX3lxTE53QlZmWmUzcWFNTTVBb1psTGNvMVE1NXlGWk4xSWpVZG1YTGdJVVdfT2lBaHFSdXRMSnFaaXFmZVdnWFhYdVZSVkI3Z09FeFNqWVBwdDdiYVE?oc=5)（CMoney）
  - [【即時新聞】日月光投控(3711)獲先進封裝追單，這「6檔概念股」多空大洗牌！](https://news.google.com/rss/articles/CBMikAFBVV95cUxNdU1aU2ZEajlobTRobUc1NHNCWDJjSmd2ZkJtUW5wYmVoMkZTdnY2cmhHSHFaMVpUYi12ckhDY1VjQmNvbTJPMElMTVo1aVBhbVllVS1RVUtNYW1RalVNUTZDLXBIR2o0R3E3Y3I3WFNaZzBNSW5GVm1fM3Jrbk5yQTFxLUY4YzlCSEZNWFFsQlQ?oc=5)（cmnews.com.tw）
### 磐亞（4707）｜化工
- 技術分數：63/100（中性觀察）
- 收盤：32.25，日變動：-3.44%
- 均線：MA5 33.01 / MA20 32.67 / MA60 30.35
- RSI14：47.46；MACD hist：-0.08；量能比：0.70x
- 目標觀察價：32.65；支撐觀察價：28.80
- 目標依據：目前在 MA20 下方，目標先看能否站回月線。
- K 線：長黑偏弱，月線下方；位於 20 日區間中段，等方向表態。
- 基本面：EPS 0.43（2026-06-30）；TTM EPS 1.28；PER 25.89；PBR 1.63；殖利率 1.50%
- Agent 快讀：技術面 中性觀察｜基本面 可參考｜消息面 有訊號
  - 技術：站上 MA60、短均線優於月線、RSI 位於健康區間
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 位於可觀察區間
  - 消息：1 則｜cmnews.com.tw｜最新：【12:36 即時新聞】磐亞(4707)股價小幅走強漲3.38%，AI 應用材料題材發酵＋中長期均線多頭結構支撐（盤中新聞，與收盤表現可能不同）（盤中新聞，與收盤表現可能不同）
- 訊號：站上 MA60、短均線優於月線、RSI 位於健康區間、MACD 柱狀體偏弱
- 近 7 日新聞：
  - [【12:36 即時新聞】磐亞(4707)股價小幅走強漲3.38%，AI 應用材料題材發酵＋中長期均線多頭結構支撐（盤中新聞，與收盤表現可能不同）](https://news.google.com/rss/articles/CBMijgFBVV95cUxQRFJuSHdzR3pUWUlqWWV0dkJ6cjBFT0gwYjVwWVV3TGhZTHp3T2dXeS1NN0dOU19yUEdXVWR2RThJd0dFNlJOT1FTUG5oNDlCZEk1UkQyWjZJQWJVZ242aUtJeDAtYnl5VkxDaGR1R2M0UUl5bkZrSU50ODRyWEg5ZlFXU2hnY0JsYThDdnZR?oc=5)（cmnews.com.tw）
### 聯策（6658）｜電子零組件 / 題材股
- 技術分數：97/100（偏多）
- 收盤：188.50，日變動：9.91%
- 均線：MA5 171.50 / MA20 162.65 / MA60 174.06
- RSI14：62.72；MACD hist：3.29；量能比：3.01x
- 目標觀察價：260.00；支撐觀察價：171.50
- 目標依據：已接近短壓，改看近 60 日高點壓力。
- K 線：長紅偏強，短多排列；接近 20 日高檔，留意追價風險與突破量。
- 基本面：EPS 1.42（2026-06-30）；TTM EPS 4.13；PER 41.63；PBR 4.38；殖利率 0.70%
- Agent 快讀：技術面 偏多｜基本面 可參考｜消息面 有訊號
  - 技術：站上 MA5、站上 MA20、站上 MA60、量能放大 3.01x
  - 基本：最近一季 EPS 為正；TTM EPS 為正；PER 偏高，估值需保守
  - 消息：4 則｜CMoney投資網誌, sinotrade.com.tw, ww2.money-link.com.tw｜最新：家登創投參與 AOI 廠聯策私募 累計持股2,137張比率達5.57%｜新聞快訊｜豐雲學堂
- 訊號：站上 MA5、站上 MA20、站上 MA60、短均線優於月線、RSI 位於健康區間
- 近 7 日新聞：
  - [家登創投參與 AOI 廠聯策私募 累計持股2,137張比率達5.57%｜新聞快訊｜豐雲學堂](https://news.google.com/rss/articles/CBMidkFVX3lxTFBwZHV4TWpYUm1kYW1RX0dIbVpYdkRwREdFRzVDM0F1NkZOUkdMdGdvZExpOXdob0dOYmFkelZwWEx5Y2p6WVZMQ1M1a3dzS1RfUnhHbTdwY1liSTlWamh4RGdKUUVPS0NacUZRa2ZLVFdyanlRbGc?oc=5)（sinotrade.com.tw）
  - [【即時新聞】家登創投最新宣布參與聯策私募案，持股比例達5.57%](https://news.google.com/rss/articles/CBMikAFBVV95cUxQYjh4VmpaeVBidEhucm9TelhKTGNLRTlTcDY2dVVsUlRzYnVPWGlnV05aQ1IwUDdQOTZzYnRETlFCckttblotbEp4YnZFRUo4TmVKX3ZWSlpKQllZWTNxenB5NHQxdnh6alpDVVRxNmFmS0dPX2NBTTdpWTdONnE2UDVXSHdWMDNNdFl4UWlEMkE?oc=5)（CMoney投資網誌）
  - [家登創投參與 AOI 廠聯策私募 累計持股2,137張比率達5.57%](https://news.google.com/rss/articles/CBMiWkFVX3lxTFA2eXBuaDVoWDR6VzgzM1poUVhuMzExQkZVWm15SEtpLUdibjJXVXhMUHpyN21DYkx0cVN4d0ZPRmtDcC1od3RQTVJiM1lpZzkyM19zTHpubzVCd9IBX0FVX3lxTE1hV1pPMFdHRzdjLTVkclFXcGdaMmNaSXRfaWdvQUNCeVZvZ21EZUEwcUFaWjZZSUc4SUtQd29aRzRPUGdEa2xiaS14SWo2WFpVWkRJUWVlUGFZSFpyT2ZZ?oc=5)（經濟日報）

## 風險提醒
- 新聞來源以公開 RSS 搜尋為主，可能有延遲或誤配，正式版需接 FinMind/Fugle/券商 API 做校驗。
- 技術分數只反映量價結構，不代表未來報酬。
- 盤中盯盤目前走 Yahoo best-effort；正式版建議升級準即時行情 API。

本內容僅供資訊整理與研究學習，不構成任何投資建議或買賣依據。

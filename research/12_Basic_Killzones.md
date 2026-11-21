# Research Report — Casharka 12: "03 Basic: Killzones"

| | |
|---|---|
| Video | https://youtu.be/sjXV_ODG1No (TET COMMUNITY, Basic series, 37:17) |
| Isha | 3 qaybood oo video ah uu user-ku soo geliyay: ~00:00–15:35, ~15:35–31:07, ~31:07–37:17. Casharka oo dhan waa la helay. |
| Habka | **Slide-yada** (way cad yihiin, waana Af-Soomaali/Ingiriis). Qaybaha 2 iyo 3 waa demo TradingView ah (EURUSD 15m/1H/1D, timezone setting). |
| Qoraalka | `transcripts/12_sjXV_ODG1No.whisper_so.txt` (waa la sugayaa) |
| Sawirrada | `research/img12/` |

Wax kasta oo hoos ku qoran waa **[SLIDE]**, haddii aan si kale loo sheegin.

## 1. Waa maxay Killzones
> "Killzones waa waqtiyo gaar ah oo inta lagu jiro maalinta suuqu aad u dhaqaaqo, isla markaana ay badanaa dhacaan dhaqdhaqaaqyada ugu waaweyn ee suuqa.
> **Si kooban:** Killzones = Saacadaha ugu wanaagsan ee suuqa laga raadiyo fursad.
> Inta lagu jiro Kill Zones: waxaa kordha liquidity, waxaa bata volatility, waxaana inta badan samaysma entry-yada ugu tayada wanaagsan.
> Killzones-ka ugu muhiimsan: Asian Session, London Session, New York Session."

## 2. Time difference (NY ↔ Soomaaliya)
- Soomaaliya waa **EAT, UTC+3** sannadka oo dhan. New York waxay isticmaashaa **DST**.

| Xilliga | New York | Farqiga Soomaaliya |
|---|---|---|
| Summer (DST) | Axadda 2aad ee March → Axadda 1aad ee November (**UTC-4**) | Soomaaliya ayaa ka horraysa **7 saac** |
| Winter (Standard) | Axadda 1aad ee November → Axadda 2aad ee March (**UTC-5**) | Soomaaliya ayaa ka horraysa **8 saac** |

- **Indicator-ka:** waqtiyada waxaa lagu qeexayaa `America/New_York`, sidaas darteed DST si toos ah ayaa loo maamulayaa.

## 3. Sessions (NY time)

| Session | NY time | Soomaaliya (summer / winter) |
|---|---|---|
| **Asian** | 8:00 PM – 12:00 AM | 3–7 AM / 4–8 AM |
| **London** | 2:00 AM – 5:00 AM | 9 AM–12 PM / 10 AM–1 PM |
| **New York** | 8:00 AM – 12:00 PM | 3–7 PM / 4–8 PM |

## 4. Session timeline (maalin buuxda, NY time)
| Waqti | Qayb | Midab slide |
|---|---|---|
| 5 PM – 8 PM | **Dead time** | casaan |
| 8 PM – 12 AM | Asian Session | cagaar |
| 12 AM – 2 AM | Pre LN | oranji |
| 2 AM – 5 AM | LN Session | cagaar |
| 5 AM – 8 AM | Pre NY | oranji |
| 8 AM – 12 PM | NY Session | cagaar |
| 12 PM – 5 PM | **Dead time** | casaan |

### Dead time
> "Dead Time waa xilliyada uu suuqa Forex aad u gaabiyo, liquidity-guna yaraado, taas oo keenta in dhaqdhaqaaqa qiimuhu noqdo mid aan xoog badnayn. Inta badan xilliyadan ma fiicna in la galo trades cusub."

## 5. Golden hours / Best time to trade (Killzones)

| Killzone | NY (UTC-4) | Soomaaliya (UTC+3) |
|---|---|---|
| **Asian** | 8 PM, 9 PM, 10 PM | 3 AM, 4 AM, 5 AM |
| **London** | 2 AM, 3 AM, 4 AM | 9 AM, 10 AM, 11 AM |
| **New York** | 8 AM, 9 AM, 10 AM | 3 PM, 4 PM, 5 PM |

- **Xiriirka purging hours (casharka 05):** purging hours waxay ku dhex jiraan killzones-ka: 8 PM, 9–10 PM, 2–3 AM, 8 AM, 9–10 AM. **6 AM** (Pre-NY purging) wuxuu ku jiraa "Pre NY", ee kuma jiro killzone.

## 6. 3.5 How time effects price delivery
- Slide-ka cinwaankiisa ayaa la arkay. Qaybaha 2–3 waa demo TradingView ah: sida timezone-ka chart-ka loo dejiyo (UTC-4 / Nairobi UTC+3), iyo sida candle-yada 1H/1D ay ugu beddelmaan timezone-ka [SLIDE/demo]. Faahfaahin xeer ah lagama helin.

## 7. Xiriirka indicator-ka (soo jeedin)
- **Killzone boxes / background:** Asia 20:00–24:00, London 02:00–05:00, NY 08:00–12:00 (America/New_York).
- **Golden hours highlight:** 20–22, 02–04, 08–10.
- **Dead time filter:** 17:00–20:00 iyo 12:00–17:00 → signal lama bixiyo (ama waa grade hoose).
- **Session highs/lows** (casharka 14: BSL/SSL waxaa ka mid ah session H/L).

Code lama qorin.

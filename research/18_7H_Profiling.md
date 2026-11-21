# Research Report — Casharka 18: "7H Profiling [AM model] + TET Model"

| | |
|---|---|
| Video | https://youtu.be/iJjtuaRgV6U (TET COMMUNITY, 22:11) |
| Isha | File uu user-ku soo geliyay (22:11, casharka oo dhan). |
| Habka | Slide-yada (way cad yihiin, Ingiriis). Qoraalka maqalka waa la sugayaa. Qaybta dambe waa demo live (XAUUSD 1D/7H/1H, OANDA). |
| Sawirrada | `research/img18/` |

Wax kasta oo hoos ku qoran waa **[SLIDE]**.

## 1. "Stop trading your bias — Why confirmation comes before execution"
- **The common mistake:** Higher-Timeframe Bias → Immediate Entry. "No confirmation = no defined timing. No confirmation = no protection when bias is wrong."
- **The mechanical shift:** **BIAS → CONFIRMATION → ENTRY.**
- **"NO PROFILE = NO TRADE."** "Stop predicting. Start waiting for confirmation."

## 2. "Understand the daily candle — Four 7-hour sessions create the framework" (NY time)
| Session | Waqti | Doorka |
|---|---|---|
| **Asia** | 5:00 PM – 12:00 AM | Opening context |
| **London** | 12:00 AM – 7:00 AM | Profile development |
| **New York AM** | 7:00 AM – 2:00 PM | Execution |
| **New York PM** | 2:00 PM – Close | Late session |

(Slide-ku wuxuu qoray "5:00 pm – 12:00 pm" iyo "12:00 pm – 7:00 am", laakiin macnuhu waa 12:00 AM, sida casharka 19.)

## 3. 7H Reversal Profiles
| Profile | Socodka |
|---|---|
| **Asian Reversal — 5:00 PM reversal** | Asia forms H/L → London expands away → NY continues |
| **London Session Reversal — 12:00 AM reversal** | Asia consolidates → London runs into Asia & reverses → NY continues |
| **NY AM Session Reversal — 7:00 AM reversal** | Asia + London give no clear reversal → NY creates reversal → NY expands |
| **NY PM Session: Continuation — 2:00 PM** | Asia + London give no clear reversal → NY AM creates reversal → NY PM continuation |

- Candle diagrams: session-ka reversal sameeya wuxuu qaadaa low-ga (ama high-ga) candle-yadii 7H ee ka horreeyay (sweep), kadib wuxuu ku xirmaa jihada cusub. Session-ka xiga ayaa sii wada. Tani waa **CRT ku dhaca 7H**.

## 4. 7 HOUR MODEL: **D – 7HR – 1h TSQ**
- **Daily** (bias) → **7H** (profile/confirmation: 5pm, 12am, 7AM, 2PM) → **1h TSQ** (entry: TS → #1 → BB).
- Tani waa isla model-ka casharka 19. Casharka 19 entry-ga dhabta ah wuxuu galay 5m Model #1.

## 5. Xiriirka indicator-ka (soo jeedin)
- **7H session candles** (NY): 17:00, 00:00, 07:00, 14:00. Pine Script-ka waxaa lagu dhisi karaa session aggregation (timeframe "7H" ma bilaabanayo 17:00 si toos ah).
- **"No profile = no trade":** signal waxaa la bixiyaa oo keliya marka 7H profile (session reversal = sweep + close back) la xaqiijiyo, oo uu la jaanqaado daily bias.

Code lama qorin.

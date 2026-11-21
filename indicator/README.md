# TET CRT Model — XAUUSD (Pine Script v6)

Fayl: `TET_CRT_Model.pine`. Xeerarka: `research/RULES.md`, go'aannada: `research/DECISIONS.md` (D1–D9).

## Sida loo geliyo TradingView
1. TradingView → **Pine Editor** → *New* → koobi garee dhammaan `TET_CRT_Model.pine` → **Save** → **Add to chart**.
2. Chart: **XAUUSD (OANDA), 5 minute**. Timezone: (UTC-5) New York.
3. Settings → **Model**: `4H CRT → 5m` ama `D bias + 7H → 5m`.
4. Alerts: *Create alert* → condition **TET CRT** → *Any alert() function call* (ama "TET CRT Sell/Buy").

## Waxa uu sameeyo (sida ay u kala horreeyaan)
| # | Shuruud | Xeer |
|---|---|---|
| 1 | **CRT range** = HTF candle-kii u dambeeyay ee xirmay (4H: 5P/9P/1A/5A/9A/1P · 7H: 17/00/07/14, NY) | L04, L18, L19 |
| 2 | **Turtle Soup**: CRT high (sell) / low (buy) waa la qaadaa, kadib 5m candle wuxuu dib ugu xirmaa gudaha range-ka | L04, L14 |
| 3 | **Purge hour (qasab)**: candle-ka sameeyay wick-ka TS waa inuu ku jiraa purge hour-ka (4H: 5P→8P · 9P→9–10P · 1A→2–3A · 5A→6/8A · 9A→9–10A; 7H: 8–10P · 2–3A · 8–10A) | D6 |
| 4 | **Key level (1H)**: FVG / OB / Breaker ku yaal premium (sell) ama discount (buy) ee CRT range-ka, oo uu TS-ku gaaray | D5, L13 |
| 5 | **SMT (qasab)**: ugu yaraan 1 pair (XAUEUR / XAUGBP / XAGUSD) ayaa ku fashilmay inuu qaado CRT high/low-giisa | D3, D4, D9 |
| 6 | **Model #1 entry**: 5m candle ku xirma dhinaca kale ee open-ka candle-kii u dambeeyay ee jihada ka soo horjeeday (line #1) | L07, Q4 |
| 7 | **SL** = wick-ka TS + buffer · **TP** = 1:3 go'an | D1, D2 |
| 8 | **Daily bias** (7H mode qasab, 4H mode ikhtiyaari): shalay wick above/below ama close beyond ee maalintii ka horreysay; waa la burinayaa marka 1H close dhaafo 0.5 (EQ) ee shalay | L19, COMPLETE_MODEL p17–19 |
| 9 | **Invalidation ka hor entry**: close dib ugu gudba CRT high/low (continuation) → la sugo · target (dhinaca kale ee range-ka) la gaaray → setup waa dhammaaday | L04, D9 |
| 10 | Max **3 signal / maalin**, hal trade mar keliya | D9 |

## Non-repainting
- Signals waxay soo baxaan oo keliya marka 5m candle-ku **xirmo** (`barstate.isconfirmed`).
- CRT range iyo 1H key levels waxaa laga dhisaa candles **xirmay** (waqtiga NY), lookahead ma jiro.
- Pairs-ka SMT: `request.security(..., timeframe.period, lookahead_off)`.

## Xaddidaadyo (v1) — waa la hubin doonaa
- **Lama compile-gareyn halkan** (Pine compiler ma jiro environment-kan). Fadlan ku tijaabi TradingView, haddii error jiraana ii soo dir screenshot-ka.
- **Breaker** = OB uu 1H close dhaafay. Shuruudda "sweep ka hor" (L13) weli laguma darin.
- **1H orderflow** filter waa toggle (default off) — qeexid cad oo la detect-gareyn karo ma jirto.
- **PSP / 2-stage SMT** laguma darin v1 (SMT keliya ayaa qasab ah, D9).
- **OTE / KOD / BRK** entries laguma darin (entry = Model #1 oo keliya).
- Win/loss table-ku waa backtest fudud (haddii SL iyo TP isku candle ku dhacaan, waxaa loo tiriyaa loss).

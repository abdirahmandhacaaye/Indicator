# TET Profile Model — XAUUSD (Pine Script v6) — v2.0

Fayl: `TET_CRT_Model.pine` (v2, profile engine). Nooca hore: `TET_CRT_Model_v1.pine`.
Xeerarka: `research/RULES.md` (qaybta J), go'aannada: `research/DECISIONS.md` (D1–D15).

## Sida loo geliyo TradingView
1. **Pine Editor** → *New* → koobi garee `TET_CRT_Model.pine` → **Save** → **Add to chart**.
2. Chart: **XAUUSD (OANDA), 5 minute**, timezone (UTC-5) New York.
3. Alerts: *Create alert* → **TET PM** → *Any alert() function call*.

## Socodka signal-ka
| # | Talaabo | Xeer |
|---|---|---|
| 1 | **Orderflow** W / D / 7H / 4H: candle-kii u dambeeyay ee xirmay — close above/below candle-kii hore = continuation, wick above/below = reversal; waa la burinayaa marka 1H candle ku xirmo dhinaca kale ee 0.5 (EQ) ee candle-kaas. **1H**: swing structure | D15, COMPLETE_MODEL |
| 2 | **Profile** (mid kasta oo la buuxiyo): P1 D+7H+1H · P2 7H+4H · P3 D+4H (ama 7H) · P4 D+1H+7H · P5 W+4H | D15 |
| 3 | **TS**: XAUUSD wuxuu qaadaa 1H high/low-gii hore, kadib 5m candle wuxuu dib ugu xirmaa gudaha | D15 |
| 4 | **1H key level**: sweep-ku wuxuu gaaraa FVG / OB / Breaker jihada saxda ah | D5 |
| 5 | **Purge hour**: Asia 8/9/10 PM · London 2/3/4 AM · NY 8/9/10 AM; **entry session**: Asia 8 PM–12 AM · London 2–5 AM · NY 8 AM–12 PM | D10 |
| 6 | **SMT (qasab)**: 1H SMT ama 5m SMT (ugu yaraan 1 pair: XAUEUR / XAUGBP / XAGUSD ma qaadin) | D12, D13, D14 |
| 7 | **Model #1**: 5m candle ku xirma dhinaca kale ee open-ka candle-kii u dambeeyay ee jihada ka soo horjeeday | L07 |
| 8 | **SL** = TS wick (+buffer) · **TP** = 1:3 | D1, D2 |
| 9 | **+PSP / +2SSMT**: lagu qoraa label-ka haddii la arko (qasab maaha) | D14 |
| 10 | **1H TSQ re-entries**: BRK / KOD (retracement + purge + SMT + Model #1) ilaa DOL ama close dhaafa TS | D11, D12 |
| 11 | Max 3 signal / maalin, hal trade mar keliya | D9 |

Label tusaale: `P1 SELL +PSP`, `P2 KOD BUY`.

## Non-repainting
Signals waxay soo baxaan oo keliya marka 5m candle-ku xirmo. HTF candles waxaa laga dhisaa 5m candles xirmay (NY time). Pairs: `request.security` (chart TF, lookahead off).

## Xaddidaadyo
- **Lama compile-gareyn halkan** — ku tijaabi TradingView, error haddii uu jiro ii soo dir screenshot.
- P1 iyo P4 waa isku shuruud (D + 7H + 1H) sida qoraalka user-ka.
- Breaker = OB uu 1H close dhaafay (sweep-ka ka horreeya laguma xiran).
- 5m SMT = swing pivots (length 3); 1H SMT = 1H candle-kii hore.

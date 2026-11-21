# Research Report — Casharka 11: "02 Basic: Candle Information & PO3"

| | |
|---|---|
| Video | https://youtu.be/vWCID2MeaHo (TET COMMUNITY, Basic series, 35:56) |
| Isha | Qayb video ah oo uu user-ku soo geliyay: **00:00–17:08 (P1)**. Qaybta 2aad (17:08–35:56), oo ay u badan tahay inay ku jirto **Price Delivery** iyo **PO3**, waa la sugayaa. |
| Habka | Slide-yada (way cad yihiin, waana Af-Soomaali). Qoraalka maqalka waa la sugayaa. |
| Sawirrada | `research/img11/` |

Wax kasta oo hoos ku qoran waa **[SLIDE]**.

## 1. Candlestick
> "Candlestick waa qaabka ugu caansan ee lagu muujiyo dhaqdhaqaaqa qiimaha muddo cayiman. Waa shumac muujinaya sida qiimuhu u furmay, u dhaqaaqay, uguna xirmay waqti cayiman. Wuxuu leeyahay 4 xog oo muhiim ah (OHLC/OLHC): **Open** (qiimaha uu ku furmay), **High** (ugu sarreeyay), **Low** (ugu hooseeyay), **Close** (uu ku xirmay)."

- Qaybaha: **Wick** (kor), **Body**, **Wick** (hoos).

## 2. Candle Information
| Bullish | Bearish |
|---|---|
| **OLHC**: Open → Low → High → Close | **OHLC**: Open → High → Low → Close |
| Close > Open | Close < Open |

- Tani waxay la jaanqaadaysaa casharka 04 (CRT) iyo casharka 05 (HOD/LOD): maalinta bullish, low-ga ayaa marka hore samaysma.

## 3. Timeframes
| TF | | Ka kooban |
|---|---|---|
| M | 1 Month | 4 weekly candles |
| W | 1 Week | 5 daily candles |
| D | 1 Day | 24 hourly candles |
| 4H | 4 Hours | 4 hourly candles |
| 1H | 1 Hour | 4 × 15-minute candles |

- Slide-yada "1D vs 1H": candle-ka 1D bullish ah wuxuu 1H-ka ka yahay hoos u dhac (low) kadib kor u kac. Bearish waa tan ka soo horjeedda (fractal).

## 4. Orderflow
- Saddex nooc: **Bullish**, **Range**, **Bearish**.
> "**Bullish Orderflow** waa xaaladda uu suuqu muujinayo in iibsadayaashu (buyers) ay ka xoog badan yihiin iibiyayaasha (sellers), taas oo keenta in qiimuhu kor u socdo ama hal jiho oo buy ah. Si fudud: Awoodda suuqa waxay ku jirtaa dhinaca buyers."
> "**Bearish Orderflow** ... Awoodda suuqa waxay ku jirtaa dhinaca sellers."

## 5. Market Cycle (Wareegga Suuqa)
> "Suuqa wuxuu inta badan maraa 4 marxaladood:
> - **Expansion** – waa marka qiimuhu si xoog leh hal jiho ugu dhaqaaqo.
> - **Retracement** – waa nasasho uu suuqu sameeyo kadib expansion, oo aan beddelin orderflow-ga.
> - **Consolidation** – waa marka suuqu uusan lahayn jiho cad oo uu ku jiro range.
> - **Reversal** – waa marka uu is beddelo orderflow-gii hore, oo uu bilowdo orderflow cusub.
>
> Wareegga: Expansion → Retracement → Expansion → Consolidation → Reversal → Expansion cusub."

## 6. 2.5 Price Delivery
- Cinwaanka ayaa la arkay. Sharaxaaddu waxay ku jirtaa qaybta 2aad (waa la sugayaa).

## 7. Xiriirka indicator-ka
- Casharkan waa aasaas. Xeer cusub oo signal ah kuma jiro. Wuxuu xoojinayaa: OLHC/OHLC (CRT), fractal-ka timeframe-yada (HTF CRT → LTF), iyo orderflow (bullish/bearish/range).

Code lama qorin.

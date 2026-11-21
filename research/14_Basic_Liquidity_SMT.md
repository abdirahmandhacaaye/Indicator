# Research Report — Casharka 14: "05 Basic: Liquidity & SMT"

| | |
|---|---|
| Video | https://youtu.be/-T-abFDwQ9c (TET COMMUNITY, Basic series, 26:07) |
| Isha | Laba qaybood: P1 (00:00–14:12), P2 (~14:12–26:07). Casharka oo dhan waa la helay. |
| Habka | **Slide-yada ayaa ugu horreeya** (way cad yihiin, waana Af-Soomaali). Qoraalka maqalka tayadiisu waa hoose, Ingiriis aan macno lahayn ayaa ku jira. |
| Qoraalka | `transcripts/14_-T-abFDwQ9c.whisper_so.txt` |
| Sawirrada | `research/img14/` |

**Heerarka kalsoonida:**
- **[SLIDE]** waa qoraal si toos ah ugu qoran slide-ka.
- **[AUDIO?]** waa fasiraaddayda qayb aan cadayn.

## 1. Liquidity  [SLIDE]
> "**Waa maxay Liquidity?** Liquidity waa meel ay taallo lacag oo uu suuqu doonayo inuu qaado si uu dhaqaaq u sameeyo."

> "Price-ku inta uusan samayn dhaqaaqa saxda ah, wuxuu marka hore tagaa meelaha liquidity-gu yaallo si uu u soo ururiyo liquidity-ga (**LIQUIDITY & MANIPULATION**). Waxaa loo yaqaan: **Liquidity Grab, Liquidity Sweep, Turtle Soup, Stop Hunt**."

## 2. BSL / SSL  [SLIDE]

| | Buy Side Liquidity (BSL) | Sell Side Liquidity (SSL) |
|---|---|---|
| Qeexid | Liquidity-ga ku ururSan **highs**-ka | Liquidity-ga ku ururSan **lows**-ka hoostooda |
| Meelaha | PDH, PWH, PMH, Session Highs (AS, LN, NY) | PDL, PWL, PML, Session Lows (AS, LN, NY) |

## 3. Two Types of Liquidity  [SLIDE]
1. **Internal Range Liquidity (IRL)**
2. **External Range Liquidity (ERL)**

### 3.1 IRL  [SLIDE]
> "IRL waa meel qiimuhu ka falceliyo (key level), waxaana laga raadiyaa gudaha dhaqaaqii hore. Waxay noqon kartaa: ✅ Order Block (OB), ✅ Fair Value Gap (FVG), ✅ Breaker Block, ✅ Mitigation Block, ✅ Volume Imbalance (VI), ✅ Balanced Price Range (BPR)."

- **Fiiro:** casharka 03 IRL-ka wuxuu ku tiriyay OB, FVG iyo IFVG oo keliya. Casharkan wuxuu ku daray **Breaker, Mitigation Block, VI iyo BPR**. Indicator-ka waxaa lagu dari karaa kuwa la ansixiyo oo keliya.

### 3.2 ERL  [SLIDE]
> "4.1 External Range Liquidity (ERL) — BSLQ / SSLQ: PDH, PDL, PWH, PWL, PMH, PML, **Equal Highs (EQH), Equal Lows (EQL)**."

## 4. IRL to ERL / ERL to IRL  [SLIDE + AUDIO?]
- **IRL TO ERL:** qiimuhu wuxuu yimaadaa IRL (FVG/OB), wuxuu qaadaa **LQ**-ga yar ee ku dhex jira (sweep), kadib expansion ayaa timaada ilaa **ERL** [P1 10:04–11:50].
- **ERL TO IRL:** ERL-ka waa la qaadaa, kadibna target-ku waa IRL-ka hoose. LQ-ga yar ee IRL-ka ku dhex jira ayaa la qaadaa.
- Macallinku: "suuqu wuxuu u socdaa **liquidity to liquidity**" [P1 11:02, 12:51]. Socodka waa: expansion → retracement → key level → liquidity sweep → expansion → ERL.
- Diagram-yada (`img14/ts_diagram.png`): **ERL**, kadib **KL** iyo **TS**, kadib reversal ilaa ERL-ka kale.

## 5. Turtle Soup (TS)  [SLIDE]
> "Turtle Soup waxa loo isticmaala in lagu qabto **fake breakout**. Waxaa la sugaa in suuqu jabiyo High ama Low hore. Dadka badanna waxay u maleeyaan inuu breakout yahay, laakiin suuqu si degdeg ah ayuu dib ugu noqdaa. Halkaas ayaa laga raadiyaa entry.
> Fikradda ugu weyn — Suuqu wuxuu marka hore: Qaadaa liquidity (Stop Loss-yada dadka). Sameeyaa fake breakout. Kadib wuxuu u dhaqaaqaa jihada ka soo horjeedda."

- Qeexiddan waxay xaqiijinaysaa in **TS = sweep ee high/low hore, kadibna dib ugu soo laabasho**. Tani waxay la jaanqaadaysaa casharka 04 (Next Candle Expectation: wick above/below).

## 6. SMT (Smart Money Technique)  [SLIDE, P2]
> "SMT waa marka laba lacaag oo isku jiha ah (correlated) ay kala haraan liquidity ahaan. Taasi waxay muujin kartaa in Smart Money ay qorsheyneyso in suuqu jihada beddelo.
> **Tusaale fudud:** Caadi ahaan laba lacaag oo isku jiha ah waxay sameeyaan: High wadajir, Low wadajir. Laakiin haddii mid keliya sameeyso High ama Low cusub, kan kalena uusan sameyn, taas waxaa la yiraahdaa **SMT Divergence**."

- Tani waxay si buuxda ula jaanqaadaysaa **D4** (sharaxaadda user-ka).
- Chart-yada P2: laba asset, mid ayaa qaaday low-ga (sweep), midka kalena wuu ku fashilmay (higher low), kadib reversal.

## 7. Draw on Liquidity (DOL)  [SLIDE, P2]
> "Draw on Liquidity: waa liquidity wayn oo suuqa uu soo jiidanayo lacag badana ay taalo. Tusaale: Haddii qiimuhu u socdo Bullish Orderflow, DOL ayuu raadsada oo lacagi taalo."

- Diagram-ka: 3 candle (CRT). Candle 2 ayaa qaatay high-ga candle 1, kadibna candle 3 wuxuu u socday **DOL** = low-ga candle 1 (CRT low).

## 8. Xiriirka indicator-ka
- **BSL/SSL levels:** PDH/PDL, PWH/PWL, PMH/PML, Session H/L (Asia/London/NY) iyo EQH/EQL.
- **TS detection:** high/low hore ayaa la jabiyaa (wick), kadibna candle-ku wuxuu dib ugu xirmaa gudaha (close back inside).
- **IRL types (D5):** FVG, OB iyo Breaker Block oo keliya.

Code lama qorin.

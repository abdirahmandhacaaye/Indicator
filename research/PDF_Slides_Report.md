# Research Report — PDF slide decks (TET Community)

User-ku wuxuu soo geliyay 6 PDF oo ah slide-yada asalka ah. Waxay ku kaydsan yihiin `research/pdfs/` (pdf + txt).

| PDF | Pages | Cashar | Wax cusub |
|---|---|---|---|
| COMPLETE_MODEL | 23 | L19 | **Invalidation (2 scenario)**, **Gold correlation / True SMT** — qaybtii maqnayd ee L19 |
| Daily_Profiling_4hr_1hr | 10 | L05 | Waxay xaqiijinaysaa L05 (5 profile, Brick by Brick) |
| PSP | 5 | L06 | "PSP waa xaqiijin dheeraad ah, **mana aha sabab keliya** oo trade lagu galo" |
| IRL_TO_ERL | 9 | L03 | 3 qaab: IRL→ERL, ERL→IRL, **ERL→ERL** |
| CRT | 29 | L04 | Waxay xaqiijinaysaa L04 (purging hours = D6) |
| SMT | 12 | L06/L14 | "SMT waxaa loo adeegsan karaa **xaqiijin dheeraad ah**"; 1-stage, 1-stage+PSP, 2-stage, 2-stage+PSP (IRL→ERL framework) |

## 1. INVALIDATION — "Knowing when your trade idea is no longer valid"  [SLIDE, COMPLETE_MODEL p16–19]
### Scenario 1 (bullish-kii la filayay wuu fashilmaa)
- Price-ku wuxuu ku furmaa **open high**, wuxuuna qaadaa ama ku hor maraa liquidity weyn: **PDH/PWH**.
- Taasi keligeed kuguma filna; waxaad arki doontaa in **bullish key levels**-kii price-ka hayay la jabiyay (**disrespected**).
- **1HR TSQ** ayaa active noqonaysa, jihada ka soo horjeedda.
- Kadib 1H TSQ, waxaad arki doontaa **7H profile** ku raacsan.
- **Target: EQ / PDL.**

### Scenario 2 — Invalidation of EQ
- **EQ = midpoint (0.5)** ee HTF candle-ka (high–low). Price-ku waa inuu ixtiraamaa haddii continuation la filayo.
- **EQ break:** wick yar waa la aqbali karaa, laakiin haddii price-ku **ku hoos xirmo EQ** (bullish) oo diido inuu reversal sameeyo → **structure failure**.
- 1HR TSQ ayaa active noqonaysa, jihada ka soo horjeedda.
- **New DOL:** opposite liquidity (PDL / PDH).
- Diagram: ✅ candle-ka xiga wuxuu ku xirmay EQ dushiisa · ❌ wuxuu ku xirmay EQ hoostiisa.

## 2. GOLD Correlation — TRUE SMT  [SLIDE, COMPLETE_MODEL p20–21]
| True SMT (GOLD vs) | Other SMT (GOLD vs) |
|---|---|
| **XAUEUR, XAUGBP, SILVER** | XAUCHF, XAUNZD, AUD, JPY |
| | ❌ **"DONT USE THIS SMT's: 1. Purging, 2. 1 stage smt"** |

- Fasiraad: "Other SMT" (CHF/NZD/AUD/JPY) **looma isticmaalo** SMT-ga purging hour-ka iyo 1-stage SMT. (Waxay u muuqataa in kuwaas ay yihiin kuwo daciif ah.) **Khilaaf la leh D3** (D3 wuxuu ku daray CHF, JPY, CAD, AUD).

## 3. PSP iyo SMT — doorkooda  [SLIDE]
- **PSP:** "waa confirmation lagu xoojinayo reversal-ka/continuation-ka, ee **ma aha setup kaligiis** lagu trade-gareeyo." Candle 1 PSP / Candle 2 PSP (XAUUSD vs XAUEUR).
- **SMT:** "waxaa loo adeegsan karaa **xaqiijin dheeraad ah**". Laakiin COMPLETE_MODEL "Confirm entry" = KL/Major LQ → PSP — SMT/2SSMT → best purge time.

## 4. IRL / ERL  [SLIDE]
- Suuqu wuxuu u dhaqaaqaa 3 qaab: **IRL→ERL, ERL→IRL, ERL→ERL**.
- IRL: FVG, OB, IFVG. ERL: swing highs/lows ee lugtu ka tagtay markii IRL la buuxinayay — PDH, PDL, PWH/PWL, major swing H/L, EQH/EQL.

---

## 5. Dib-u-eegis taxadar leh (bog kasta, sawir ahaan) — 2026-11-21
Bog kasta oo 6-da PDF ah ayaa sawir ahaan loo eegay (`pdftoppm`). Faahfaahinta cusub ama la saxay:

### CRT.pdf
- **Inside Bar CRT (diagram):** candle 2 iyo 3 waxay ku dhex jiraan range-ka candle 1; **candle 3 wick-kiisa ayaa qaada range high-ga**, candle 4 ayaa u socda CRTL. (Manipulation-ku wuxuu ku dhici karaa candle-ka inside-ka ah wick-kiisa.)
- **Multiple CRT:** candle 2 ayaa qaada high-ga; distribution-ku wuxuu qaataa candles 3 + 4 (dhowr candle) ilaa CRTL.
- **2 Stage Manipulation:** candle 2 ayaa qaada high-ga (stage 1); candle 3 wuxuu qaadaa high ka sii sarreeya (stage 2), kadibna wuxuu u dhacaa CRTL — dhammaan isla candle-ka.
- **Dealing range (diagram):** 0% = low-ga lugta, 100% = high-ga lugta (ERL); 50% = equilibrium. **IRL / KL / OB** waxay ku yaalaan **discount** (bullish). Chart-ka: 100% ERL, 50%, OB discount-ka, 0%. → Q8: dealing range = **lugta u dambeysa ee OF-ga** (swing low → swing high bullish).
- **The Sequence (diagram):** CRTH+TS (sweep high hore) → **#1** (OB, line hoos yar) → **BRK** (low-gii u dhexeeyay labada high, la jabiyay, kadib dib loogu soo laabtay) → **OTE** (lower high retracement) → **KOD** (retracement u dambeeya, oo qaada high yar) → **CRTL = DOL**.
- **4H → 15m:** 4H candle-ka KL-ka gaaray → 15m: KL, TS, CRTH, #1 → hoos ilaa CRTL.

### IRL_TO_ERL.pdf
- **OB diagram:** line-ka "Orderblock" wuxuu ka bilaabmaa **open-ka candle-ka ugu horreeya ee kooxda** candles-ka jihada ka soo horjeedda (3 down candle oo isku xiga → line-ka top-ka kooxda). → **OB = koox candles ah** (sida L04 P3a), level = open-ka candle-ka kooxda ugu horreeya (body edge).
- **ERL → IRL:** major liquidity (dotted) ayaa la qaaday, kadib suuqu wuxuu kor ugu soo laabtay **IRL (FVG)**.
- **ERL → ERL:** range dheer; price wuxuu qaadaa ERL hal dhinac (wick), kadibna wuxuu u socdaa ERL-ka dhinaca kale — IRL lagama joogsado.

### SMT.pdf
- **1-stage SMT (candles):** 3 candle; candle 2 ayaa sameeya high cusub oo ka sarreeya candle 1 (Gold), halka asset-ka kale uusan sameyn (line "smt").
- **1-stage SMT (high/low):** GOLD wuxuu sameeyay **lower high**, GOLD/EUR wuxuu sameeyay **higher high** (wuxuu qaaday high-ga) → bearish.
- **IRL→ERL framework:** FVG (IRL) gudihiisa: c1, c2 lows — hal asset lower low, kan kale higher low → c3 bullish → ERL. "+PSP": c2 (cagaar) wuxuu ku xirmay jiho ka duwan asset-ka kale.

### PSP.pdf
- **Candle 2 PSP (bearish):** labada asset candle 2 wuxuu qaatay high-ga candle 1; **XAUUSD candle 2 = bearish close, XAUEUR candle 2 = bullish close** → PSP.
- **Candle 1 PSP:** candle 1 (high-ga) XAUUSD = bearish, XAUEUR = bullish; candle 2 ayaa labadaba qaada high-ga.

### Daily_Profiling_4hr_1hr.pdf
| Profile | 1H purge (diagram) |
|---|---|
| 5 PM H/L | **8 PM** (LOD), kadib **6 AM** (low labaad / re-entry) |
| 9 PM H/L | **9 PM** |
| 1 AM H/L | **3 AM** |
| 5 AM H/L | **6 AM** |
| 9 AM H/L | **10 AM** |
- **Brick by Brick:** 4H CRT bearish (candle 2 qaaday high-ga) → 1H "**8 am Purge**" → 5m **#1**, SL kor (sweep-ka dushiisa), TP hoos (CRTL) — R:R ≈ 2.5–3.

### COMPLETE_MODEL.pdf
- **Key session opening times:** **Forex & CFD: Asia 17:00, London 00:00, NY 07:00.** Indices: 18:00 / 01:00 / 08:00. XAUUSD waa CFD → **17/00/07** (TET). NAZARIO-ga 18/01/08 waa waqtiyada Indices.
- **1H TSQ vs 1H Key level (diagram):** 1H TSQ = lower highs isku xiga (TS → #1 → BRK); 1H KL = price wuxuu dib ugu soo laabtaa 1H KL (kor ka jabay) oo ixtiraamaa, kadib hoos. "/ MAJOR LQ = Previous Daily / Previous Weekly". Best purge: 8,9,10 – 2,3 – 8,9,10.

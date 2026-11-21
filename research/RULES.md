# PHASE 2 — Liiska mideysan ee xeerarka (TET Model / ICT / CRT)

**Xaalad:** QABYO, waxay sugaysaa ansixinta user-ka. Code lama qori doono ilaa liiskan la ansixiyo.

**Calaamadaha:**
- ✅ **D#** = go'aan uu user-ku ansixiyay (`DECISIONS.md`).
- 📘 **L##** = cashar ayaa si cad u sheegay. Faylka report-ka waa `research/##_*.md`.
- 🟡 = soo jeedin ama fasiraad, waxayna u baahan tahay ansixin.
- ❓ = su'aal furan.

Waqtiyada oo dhan waa **New York time** (`America/New_York`, DST-ka si toos ah ayaa loo maamulaa) [L05, L12]. Asset-ka ugu weyn waa **XAUUSD** [D3].

---

## A. Context (HTF bias)

| # | Xeer | Isha |
|---|---|---|
| A1 | **Order flow:** bullish waa marka buy-side la jabiyo, swing lows-kuna ay protected yihiin. Bearish waa tan ka soo horjeedda. | 📘 L02, L11 |
| A2 | **Dealing range** (lugta u dambeysa ee OF-ga: 0% = swing low, 100% = swing high / ERL — PDF CRT, Q8 ✅): waa dhaqaaqii u dambeeyay ee order flow-ga raacsan. 50% = equilibrium. Buy setup-ka waxaa laga raadiyaa discount, sell setup-kana premium. | 📘 L04 §2.7 |
| A2b | Suuqu wuxuu u dhaqaaqaa 3 qaab: **IRL→ERL, ERL→IRL, ERL→ERL**. | 📘 PDF IRL_TO_ERL |
| A3 | **DOL / ERL (targets ama liquidity):** PDH/PDL, PWH/PWL, PMH/PML, session highs/lows (Asia/London/NY) iyo EQH/EQL. | 📘 L02, L14 |
| A4 | **Daily bias:** Daily CRT. Candle 2 ayaa qaata high-ga ama low-ga candle 1 ee ku yaal KL/major LQ, kadibna dib ugu xirma gudaha (wick above/below). Bias-ku waa jihada ka soo horjeedda sweep-ka, DOL-kuna waa dhinaca kale ee candle 1. Haddii candle-ku xirmo dibadda (close above/below), waa continuation. | 📘 L04 §2.6, L19 §2 |
| A5 | **"No profile = no trade":** signal lama bixiyo haddii bias-ka aan la xaqiijin (A4 + B). | 📘 L18 |

## B. Confirmation (session profile)

| # | Xeer | Isha |
|---|---|---|
| B1 | **Model 4H (casharrada 04/05):** maalinta = 6 × 4H candle (5P, 9P, 1A, 5A, 9A, 1P). CRT-ga waa 4H candle-kii **xirmay**. Candle-ka xiga ayaa qaada high-ga ama low-giisa (TS). | 📘 L04, L05 |
| B2 | **Model 7H (casharrada 18/19):** maalinta = 4 session oo 7H ah: Asia 17:00, London 00:00, NY AM 07:00, NY PM 14:00. Profile-yada: **Asian reversal**, **London reversal**, **NY AM reversal**, **NY PM continuation**. Session-ka reversal sameeya wuxuu qaadaa high-ga ama low-ga session-kii hore, kadibna dib ayuu ugu xirmaa. | 📘 L18, L19 |
| B2b | **7H profile detection (NAZARIO PDF):** Asia reversal = London 7H **ma qaadin** Asia high/low oo ku xirmay dibadda · London reversal = London **qaaday** Asia high/low kadibna gudaha ku xirmay · NY reversal = Asia + London reversal ma sameyn → 8AM ayaa sameeya. Natiijada: 8AM NY = continuation ama reversal. | 📘 PDF 7H PROFILING (Nazario) |
| B2c | **Waqtiga 7H (XAUUSD = CFD):** **17:00 / 00:00 / 07:00 (+14:00 NY PM)**. NAZARIO-ga 18/01/08 waa waqtiyada **Indices** (PDF COMPLETE_MODEL p6). Soo jeedin: input, default 17/00/07. | 📘 PDF COMPLETE_MODEL |
| B3 | ❓ **Model-kee ayaa la isticmaalayaa:** 4H (B1), 7H (B2), mise labadaba (input "mode")? | ❓ Q-A |

## C. Key levels (IRL)

| # | Xeer | Isha |
|---|---|---|
| C1 | Key levels-ka la isticmaalayo waa **FVG, Order Block iyo Breaker Block** oo keliya. | ✅ D5 |
| C2 | **FVG:** 3 candle. Bullish box-ku wuxuu u dhexeeyaa high-ga C1 iyo low-ga C3. Bearish box-ku wuxuu u dhexeeyaa low-ga C1 iyo high-ga C3. | 📘 L03, L13 |
| C3 | **Order Block:** candle-kii (ama **kooxda candles**) u dambeeyay ee jihada ka soo horjeeday, **ka hor displacement**. Level-ku waa **open-ka candle-ka ugu horreeya ee kooxda** (body edge). | 📘 L03, L13 (Q6), L04, PDF IRL_TO_ERL |
| C4 | **Breaker:** OB uu candle ku xirmay dhinaca kale **kadib liquidity sweep**, kaas oo noqda support ama resistance cusub. Haddii sweep aanu jirin, waa Mitigation, lamana isticmaalayo. | 📘 L13 |
| C5 | Timeframe-yada key level-ka: HTF (D/4H/1H) ama 1H KL / major LQ (PDH/PDL/PWH/PWL). | 📘 L17, L19 |
| C6 | 🟡 **Displacement:** candle-ka xiga ha ku xirmo dhinaca kale ee OB-ga, ama FVG ha ka samaysmo. Qeexid cad casharrada kuma jirto. | 🟡 |

## D. Manipulation (Turtle Soup)

| # | Xeer | Isha |
|---|---|---|
| D1 | **Turtle Soup (TS):** qiimuhu wuxuu jabiyaa high ama low hore (CRT high/low, PDH/PDL, session H/L, EQH/EQL), kadib candle-ku wuxuu dib ugu xirmaa gudaha. Waa fake breakout. | 📘 L04, L14 |
| D2 | **Purging hours waa qasab** (L07 frame: macallinku wuxuu gacan ku qoray 4H candle-ka purge kasta — xaqiijin). TS-ka waa inuu ku dhaco: 5P→**8P** · 9P→**9–10P** · 1A→**2–3A** · 5A→**6/8A** · 9A→**9–10A**. | ✅ D6 |
| D3 | ❓ **Khilaaf waqti:** L17 (A+ times) waxay leeyihiin NY **8–9 AM**, L19-na **8–10 AM**, L05-na **9–10 AM** (iyo 6/8 AM Pre-NY). L18/L19 Asia-da waxay leeyihiin **8–10 PM**. Liiska saxda ah waa la ansixinayaa. | ❓ Q-B |
| D4 | Dead time xeer gaar ah ma leh, maadaama D2 si toos ah uga reebayo. | ✅ D7 |

## E. Confirmation (SMT / PSP)

| # | Xeer | Isha |
|---|---|---|
| E1 | **SMT:** XAUUSD wuxuu qaadaa level (high/low), ugu yaraan hal asset oo kale ah ayaana ku fashilma. | ✅ D4 |
| E2 | **Assets-ka:** XAUEUR, XAUGBP, XAGUSD, XAUCHF, XAUJPY, XAUCAD, XAUAUD. Liiska waa input. | ✅ D3 |
| E2b | ⚠️ **PDF-ka "True SMT":** XAUEUR, XAUGBP, SILVER oo keliya ayaa ah True SMT. XAUCHF, XAUNZD, AUD, JPY = "Other SMT" — **"DONT USE: purging, 1 stage smt"**. Khilaaf la leh D3 → ❓ Q-G. | 📘 PDF COMPLETE_MODEL p21 |
| E3 | **PSP:** ("xaqiijin dheeraad ah, ma aha setup kaligiis" — PDF PSP)  isla HTF candle-ka (oo xirmay), XAUUSD wuxuu ku xirmaa hal jiho, asset kalena jihada ka soo horjeedda. | 📘 L06 |
| E4 | **Two-stage SMT:** laba SMT oo isku xiga, probability-guna waa ka sarreeyaa. | 📘 L06 |
| E5 | **SMT break:** asset-kii fashilmay ayaa markii dambe isna qaada level-ka. Markaas SMT-gu waa invalid. | 📘 L06 (slide) |
| E6 | ❓ **SMT/PSP ma qasab baa** (sida purging hours), mise waa grade ama confirmation dheeraad ah? L07: "liquidity la qaado **ama** SMT, waa isku mid". L19: Confirm entry = PSP **ama** SMT/2SSMT. | ❓ Q-C |

## F. Entry (Model #1)

| # | Xeer | Isha |
|---|---|---|
| F1 | **Hal entry model oo keliya: Model #1** = Order Block (C3), oo ku yaal **LTF**. | 📘 L07 |
| F2 | **Timeframe-ka LTF:** Monthly→Daily, Weekly→4H, Daily→1H, 4H→15m, 1H→5m. Entry-ga dhabta ah inta badan waa **5m**. | 📘 L04 §2.9, L05, L07, L19 |
| F3 | **Model #1 waa ansax** oo keliya haddii uu ku yaal key level, uu jiro liquidity sweep (TS) ama SMT, iyo purging hour. Haddii kale waa **fake OB**. | 📘 L07 |
| F4 | **Entry trigger:** candle (LTF) ku xirma dhinaca kale ee line-ka **#1** (OB open). Tani waa non-repainting, maadaama la sugo candle close. | 📘 L07 (Q4) + 🟡 (close) |
| F5 | Looma baahna in la sugo in HTF candle-ku (4H/7H) xirmo. Entry-ga waxaa laga galaa gudaha candle-ka. | 📘 L05 §8 |
| F6 | **The Sequence (TSQ):** TS → #1 → BRK → (OTE) → KOD → DOL. Mid kasta wuxuu noqon karaa entry. 1H TSQ waa active marka TS + #1 + BB + 2 KL oo jihada ka soo horjeedda la jabiyo. | 📘 L04, L17 |
| F7 | 🟡 **OTE:** waa fib retracement (L04 frame: 0.618 / 0.786). Zone sax ah lama sheegin. Soo jeedin: laga saaro signal-ka (F1 = Model #1 oo keliya). | 🟡 Q2 |
| F8 | ❓ **Breaker / KOD entries:** ma bixiyaan signal kale (re-entry)? Mise Model #1 oo keliya? | ❓ Q-D |

## G. Risk

| # | Xeer | Isha |
|---|---|---|
| G1 | **SL:** wick-ka TS-ka dushiisa (sell) ama hoostiisa (buy). | ✅ D1 |
| G2 | **TP:** 1:3 go'an, TP = Entry ± 3 × \|Entry − SL\|. Hal TP oo keliya. | ✅ D2 |
| G3 | Risk-ka account-ka (1% / 0.5%) waa user-ka, indicator-ku ma xisaabiyo. 🟡 | L16 |

## H. Invalidation / No-trade

| # | Xeer | Isha |
|---|---|---|
| H1 | **Inside bar CRT:** candle-yada gudaha ku xirma (high iyo low midna lama qaadin) ma aha setup. Waxaa la sugaa TS. | 📘 L16 trap 1 |
| H2 | **Range candle trap:** candle range ah oo ku dhex samaysmay key level-ka. Liquidity-giisa ayaa marka hore la qaadaa, sidaas darteed ha gelin ka hor sweep-kaas. Ka reeban: haddii key level-ku horay u lahaa range. | 📘 L16 trap 2 (🟡 faahfaahin) |
| H3 | **Retracement phase:** kadib qaadista PDL (DOL), sell lagama galo retracement-ka ("DON'T SELL HERE"). Buy-gana waa tan ka soo horjeedda. | 📘 L16 trap 3 |
| H4 | **Target la gaaray:** kadib DOL ama target, waxaa la sugaa retracement ka hor setup cusub jihadaas. | 📘 L16 trap 4, L17 |
| H5 | **Invalidation Scenario 1 (bias failure):** price-ku wuxuu qaadaa liquidity weyn (PDH/PWH ee bullish), key levels-kii bias-ka waa la jabiyaa (disrespect), **1H TSQ** ayaa active noqota jihada ka soo horjeedda, kadibna 7H profile ayaa raacda → bias-ka waa la beddelaa, target-kuna waa EQ / PDL. | 📘 PDF COMPLETE_MODEL p17 |
| H5b | **Invalidation Scenario 2 (EQ):** EQ = 0.5 ee HTF candle-ka. Continuation-ka, haddii candle **ku xirmo EQ-da dhinaca kale** (wick waa la aqbali karaa) → structure failure, DOL cusub = opposite liquidity (PDL/PDH). | 📘 PDF COMPLETE_MODEL p19 |
| H5c | 🟡 **Setup invalid ka hor entry:** candle ku xirma TS wick-ka dibaddiisa, ama TP (3R) la gaaro iyadoon entry bixin. | 🟡 Q1 |
| H6 | 🟡 **SMT break** (E5) → setup-ka SMT-ga ku tiirsan waa invalid. | 📘 L06 |

## I. Kuwa kale

| # | Xeer | Isha |
|---|---|---|
| I1 | Ha la koobiyeyn TET checklist. Indicator-ku wuxuu ahaanayaa mid automatic ah. | ✅ D8 |
| I2 | ❓ **Grade:** recaps-ka waxay muujinayaan A+ / B- / No Trade. Signal ma bixiyaa grade (tusaale A+ = dhammaan shuruudaha, B = SMT ka dhiman), mise signal oo keliya marka dhammaan la buuxiyo? | ❓ Q-E |
| I3 | ❓ **Max trades / maalin:** recap 11-11 wuxuu muujiyay 3 sell isla maalin (2A, 6A, 8A). Ma la oggol yahay re-entries? | ❓ Q-F |
| I4 | 🟡 Noocyada CRT ee la taageerayo: 3-candle, 2-candle, inside bar (kadib TS), multiple, 2-stage manipulation. | 📘 L04 (Q5) |

---

## Su'aalaha u baahan go'aankaaga

| # | Su'aal |
|---|---|
| **Q-A** | Model: 4H→5m (L04/05), D→7H→1H/5m (L18/19), mise labadaba (input)? |
| **Q-B** | Liiska purging hours ee kama dambaysta ah (D2 vs L17/L19). |
| **Q-C** | SMT/PSP: qasab mise grade? |
| **Q-D** | Breaker/KOD re-entries: haa mise maya? |
| **Q-E** | Grade (A+/B) mise signal oo keliya? |
| **Q-F** | Trade-yo badan maalintii: haa (immisa)? |
| **Q1** | Invalidation H5c (ka hor entry): candle ku xirma TS dibaddiisa, TP la gaaray, mise labadaba? (H5/H5b waxay ka yimaadeen PDF-ka.) |
| **Q-H** | ✅ Xal la soo jeediyay: default 17/00/07 (TET Forex & CFD), input lagu beddeli karo. Ansixi. |
| **Q-G** | SMT pairs: D3 (7 asset) mise PDF-ka (True SMT = XAUEUR, XAUGBP, XAGUSD; kuwa kale lama isticmaalo purging/1-stage)? |
| **Q2** | OTE: ka saar? |

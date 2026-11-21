# Research Report — Casharka 04: "4.0 Candle Range Theory (CRT)"

| | |
|---|---|
| Video | https://youtu.be/ELUb-AIxC88 (TET COMMUNITY, 2026 Mentorship, 56:47). Macallinka: "Akim" (TET Community). |
| Isha | 5 qaybood oo video ah uu user-ku soo geliyay: 00:00–19:00, 19:00–38:00, ~38:00–45:10, ~45:10–52:10, ~54:02–56:47. **~2 daqiiqo (~52:10–54:02) lama helin**, waana tusaalooyin chart. |
| Habka | Slide-yada (sawir 10-kii ilbiriqsi kasta) iyo qoraalka maqalka (Whisper, Af-Soomaali). |
| Tayada | Slide-yadu waa cad yihiin. Qoraalka maqalku waa **dhexdhexaad**, wuuna ka fiican yahay kan casharka 03. |
| Qoraalka buuxa | `transcripts/04_ELUb-AIxC88.whisper_so.txt`. Waqtiyada hoos ku qoran waa `Pn mm:ss`: qaybta iyo waqtiga ku dhex jira qaybtaas. |
| Sawirrada | `research/img04/` |

**Heerarka kalsoonida:**
- **[SLIDE]** waa qoraal si toos ah ugu qoran slide-ka.
- **[AUDIO+]** waxaa si cad looga maqlay hadalka.
- **[AUDIO?]** waa fasiraaddayda qayb aan cadayn.
- **[MA CADDA]** casharku ma sharxin, ama lama fahmi karo.

---

## 1. Qaab-dhismeedka casharka (slide-yada)

| # | Mawduuc |
|---|---|
| 4.0 | Candle Information (OHLC), Waa maxay CRT, Candle Range, AMD |
| 4.1 | Types of CRT: 3 Candle, 2 Candle, Inside Bar, Multiple CRT, 2 Stage Manipulation |
| — | Next Candle Expectation |
| 4.2 | Dealing Range |
| 4.3 | How to use CRT with KL (Key Level) |
| 4.4 | HTF CRT to LTF Model #1, Timeframe alignment |
| 4.5 | The Sequence (TSQ) |
| 4.6 | Purging Hours |
| — | "Now the pieces fit together", END, kadib tusaale live ah (XAUUSD 4H, OANDA, TradingView Replay) |

## 2. Fikradaha CRT

### 2.1 Candle Information  [SLIDE + AUDIO+]
- **Bullish candle:** Open → Low → High → Close (OLHC). Wuxuu furmaa, hoos ayuu u dhacaa (low), kor ayuu u kacaa (high), kadibna wuxuu xirmaa.
- **Bearish candle:** Open → High → Low → Close (OHLC).
- Candle kasta oo timeframe sare ah, timeframe hoose wuxuu ka dhigan yahay dhaqaaq dhan (schematic) [P1 03:40–04:12].

### 2.2 Waa maxay CRT  [SLIDE]
> "CRT waxaa laga soo gaabiyay Candle Range Theory. Candle walba ee aad ku aragto charts-ka, ha ahaado Daily, 4H ama dhammaan Timeframe-yada kale, uma sameysmin si random ah ee waa **time based range**."

- "Every candle is a range" [P1 02:25, 03:35].
- **Range High = buy-side liquidity**, **Range Low = sell-side liquidity** [P1 03:25–03:35] [AUDIO+].
- Erayada: **CRTH** = CRT high, **CRTL** = CRT low. Labadaba waxay ku qoran yihiin slide-yada.

### 2.3 Fikradda aasaasiga ah (Basic CRT)  [SLIDE + AUDIO+]
- Candle 1 (range) waa la sameeyaa. Candle-ka xiga wuxuu qaadaa **range high** (liquidity sweep / **Turtle Soup**), kadib target-kiisu waa **range low / CRT low** [P1 04:39–05:35, 06:16–06:42].
- Bullish waa tan ka soo horjeedda: candle-ka xiga wuxuu qaadaa range low, target-kuna waa range high [P1 06:44–07:13].
- Slide-ka "CRT = (dhaqaaq)" wuxuu muujinayaa in candle-ka HTF uu yahay range-kiisa oo dhan marka lagu eego LTF.

### 2.4 AMD — Accumulation, Manipulation, Distribution  [SLIDE + AUDIO+]
- **Accumulation:** candle-ka range-ka sameeya (candle 1). **Waa inuu ku samaysmaa key level** [P1 09:16, 10:20–10:32, 12:27].
- **Manipulation:** marka la qaado high-ga ama low-ga range-ka (liquidity sweep / turtle soup) [P1 10:46–10:50, 13:28–13:36].
- **Distribution:** dhaqaaqa u socda target-ka, oo ah dhinaca kale ee range-ka [P1 11:06].
- Key level-ku wuxuu noqon karaa **internal** (OB, FVG, IFVG) ama **external** (high/low keliya) [P1 12:30–12:47].
- Xiriirka IRL/ERL [P1 08:14–08:21, 09:22–09:35] [AUDIO?]: "Marka key level internal ah la imaado, waxaa la sugaa in external-ka la qaado (manipulation), kadibna distribution."

### 2.5 Noocyada CRT (4.1)  [SLIDE + AUDIO+]

| Nooc | Qeexidda |
|---|---|
| **3 Candle CRT** | Candle 1 = accumulation (range, key level ku yaal). Candle 2 = manipulation: wuxuu qaadaa high-ga (ama low-ga) candle 1, kadibna wuxuu dib ugu xirmaa gudaha range-ka. Candle 3 = distribution: wuxuu u socdaa CRT low (ama high) [P1 10:18–11:12, 13:08–13:46]. |
| **2 Candle CRT** | Candle 1 = accumulation. Candle 2 ayaa isku mar samaysa manipulation iyo distribution [P1 11:28–12:09]. |
| **Inside Bar CRT** | Candle 1 = accumulation. Candle 2 iyo 3 waxay ku xirmaan gudaha range-ka candle 1, iyagoo aan qaadin high iyo low midna. Candle-ka ugu horreeya ee qaada high/low-ga (tusaale candle 4) ayaa samaysa manipulation, kadibna distribution ayaa timaada [P1 12:12–14:45]. |
| **Multiple CRT** | Manipulation-ku wuxuu qaataa candles badan (2, 3 ama ka badan). Target-ku wuxuu u qaadan karaa 1, 2 ama 3 candle [P1 14:56–15:53] [AUDIO?]. |
| **2 Stage Manipulation CRT** | Manipulation #1 (stage 1) ayaa dhacda, laakiin target-ka looma gudbo. Kadib manipulation #2 (stage 2) ayaa dhacda, gaar ahaan marka key level-ka ama time-ka la gaaro, kadibna target-ka ayaa la tagaa [P1 15:59–16:47]. |

- Macallinku wuxuu yiri "type 6" [P1 16:49], laakiin slide-yadu waxay muujinayaan **5 nooc oo keliya**. **[MA CADDA]**

### 2.6 Next Candle Expectation  [SLIDE + AUDIO+]

| Waxa dhacay | Filashada candle-ka xiga |
|---|---|
| **Close Above:** candle-ku wuxuu ku xirmay high-ga ka sarreeya ee candle-kii hore | Higher prices (continuation) |
| **Close Below** | Lower prices (continuation) |
| **Wick Below:** candle-ku wuxuu qaatay low-ga hore, kadibna dib ayuu ugu xirmay gudaha range-ka | Higher prices (reversal) |
| **Wick Above** | Lower prices (reversal) |

[P2 00:30–02:47]: close above/below waa continuation, wick above/below waa reversal.

### 2.7 Dealing Range (4.2)  [SLIDE + AUDIO+]
> "Waa dhaqaaqii ugu dambeeyay ee OF-ga (order flow) raacsan, kaas oo ay KL ku dhex sameysmaan." [SLIDE]

- Waxaa laga sawiraa swing point ilaa swing point ("from this point to this point") [P2 04:14–04:25].
- **50% = Equilibrium.** Kor ka sarreeya waa **Premium**, hoos ka hooseeya waa **Discount** [P2 04:58–05:05].
- **Bullish:** key level-ka waxaa laga raadiyaa **discount**. **Bearish:** waxaa laga raadiyaa **premium** [P2 05:05–06:05].
- Key level-ka dealing range-ka gudihiisa ku jira waa **IRL** (OB, FVG, IFVG) [P2 04:38–04:46].

### 2.8 CRT with KL (4.3)  [SLIDE + AUDIO+]
- Slide-ka waxaa ku qoran: **KL** (kor), **CRTH**, **CRTL**.
- Socodka: dhaqaaq ayaa yimaada key level-ka (premium haddii bearish) → **accumulation** (candle-ka range-ka) → **manipulation** (qaadista CRTH) → **LTF Model #1** → distribution ilaa **CRTL / SSL** [P2 07:46–09:15].

### 2.9 HTF CRT → LTF Model #1 (4.4)  [SLIDE + AUDIO+]

| HTF CRT | LTF Model #1 |
|---|---|
| Monthly | Daily |
| Weekly | 4H |
| Daily | 1H |
| 4H | 15min |
| 1H | 5min |

- Slide-ka tusaalaha: candle-ka **4H** = chart-ka **15 min**, oo ay ku qoran yihiin KL, TS, #1, CRTH iyo CRTL.

### 2.10 Model #1  [AUDIO+]
- "**Model 1 waa Order Block.**" Sell setup-ka, waa **candle-kii u dambeeyay ee kor u socday (last up-candle)**, kaas oo qaaday liquidity-ga, ka hor dhaqaaqa hoos u dhaca. Buy setup-ka waa tan ka soo horjeedda [P2 11:33–12:16; P3b 03:03–03:34].
- OB-gu wuxuu noqon karaa **koox candles ah** (3, 4, 5 up-candles oo isku xiga) [P3a 06:20–06:36].
- **[MA CADDA]** Shuruudda confirmation-ka: ma waa in candle ku xirmo OB-ga hoostiisa (displacement)? Erayga "markel wuhu sijirmu u bur ilalafir" [P2 12:01] waxaa laga yaabaa inuu yahay "marka uu ka hooseeyo xirmo". Waa in la xaqiijiyo.

### 2.11 The Sequence / TSQ (4.5)  [SLIDE + AUDIO+]
Slide-ka waxaa ku qoran (bearish): **CRTH + TS → #1 → BRK → OTE → KOD → CRTL = DOL**

| Calaamad | Macnaha (sida casharku sheegay) |
|---|---|
| **TS** | **Turtle Soup**: qaadista liquidity-ga CRTH (manipulation-ka ugu horreeya) [P2 15:43–15:49, 17:38]. Tani waxay xallinaysaa su'aashii casharka 03. |
| **#1** | **Model #1** = Order Block (last up-candle ka hor dhicitaanka) [P2 15:49, 17:17]. |
| **BRK** | **Breaker Block**: OB uu suuqu jabiyay (disrespect), kadibna noqda level jihada ka soo horjeedda. Suuqu waa inuu "nasto" oo dib ugu laabto **premium**-ka ilaa breaker-ka [P2 15:51; P3a 00:52–02:51]. |
| **OTE** | Lagu sheegay [P2 15:53, 17:18], laakiin **lama sharxin** qaybaha la helay. **[MA CADDA]** (ICT-ga caadiga ah waa fib 62–79%, laakiin casharku ma sheegin.) |
| **KOD** | Waxaa lagu maqlay "kiss of …" [P2 16:28, 17:21; P3a 03:17–03:23]. Waa **liquidity sweep-ka u dambeeya (turtle soup labaad)** ka hor target-ka. Magaca buuxa (Kiss of Death?) **[AUDIO?]**. |
| **DOL** | **Draw on Liquidity** = target-ka. Haddii range high la qaado, range low-ga ayaa noqda DOL [P2 16:33–16:46]. |

- **Muhiim [AUDIO+]:** Talaabooyinkan **mar walba ma wada dhacaan**. Suuqu wuxuu siin karaa TS iyo #1 oo keliya oo toos u aada target-ka, ama wuxuu siin karaa breaker, OTE ama KOD. Mid kasta waxay noqon kartaa entry [P2 17:53–18:39; P3b 03:46–03:57].
- **[MA CADDA]** [P2 15:11–15:28] wuxuu u muuqdaa inuu leeyahay "waa qasab inay marto B, C, D", taas oo ka hor imaanaysa qodobka kore. Waa in la xaqiijiyo.

### 2.12 Purging Hours (4.6)  [SLIDE + AUDIO+]
- **Qeexid:** waa saacadaha la filayo **manipulation**, taas oo ah marka high-ga ama low-ga candle-ka accumulation-ka la qaado [P3a 03:37–03:51].
- **Waqtigu waa New York time**: "New York time keliya isticmaala" [P3a 04:09–04:20] [AUDIO+].

| Session | Purging hours (NY time) |
|---|---|
| Pre Asian | 8 pm |
| Asian | 9 pm, 10 pm |
| London | 2 am, 3 am |
| Pre NY | 6 am, 8 am |
| NY | 9 am, 10 am |

### 2.13 Tusaalaha live (XAUUSD 4H)  [AUDIO? + SLIDE]
- Order flow bearish ah. Liquidity ayaa la qaaday, kadibna FVG ayaa la ixtiraamay. OB-ga wuxuu noqon karaa koox candles ah [P3a 05:58–06:36].
- 50%-ka CRT range-ka (premium/discount-ka candle-ka) ayaa la sawiray [P3b 01:16–01:44].
- Tusaale **2 Candle CRT (type 2)** ah, oo candle-ka labaad samaynayo manipulation iyo distribution, kadib LTF Model #1 ayaa la raadiyay [P3b 04:10–05:24]. Tusaale **2 stage manipulation** ah ayaa la bilaabay [P3b 05:53].

### 2.14 Tusaalaha u dambeeya (qaybta p3c)  [AUDIO?]
- Macallinku wuxuu sheegay "time iyo price" [p3c 00:00–00:40]: setup-ku wuxuu u baahan yahay key level (price) iyo waqti (time). **[MA CADDA]** Faahfaahinta lama fahmi karo.
- **Tusaale 3 Candle CRT (bullish):**
  - Accumulation-ku wuxuu ku samaysmay OB (key level).
  - Candle-ka xiga wuxuu qaaday CRT low-ga (manipulation), kadibna distribution ayaa timid [p3c 00:58–01:27].
  - LTF-ka liquidity ayaa la qaaday. **Model #1** = "candle-kii u dambeeyay ee bearish ahaa ka hor intaan suuqu bullish noqon", kadibna suuqu wuxuu toos u aaday target-ka [p3c 01:34–02:13].
- Chart-ka waxaa ku jira tusaalooyin two-stage manipulation, multiple CRT iyo inside bar CRT [p3c 02:26–02:42].
- **Stop loss iyo invalidation laguma sheegin qaybtan.**

## 3. Setup / Entry / SL / TP / Invalidation (sida casharku sheegay)

| Qodob | Casharka |
|---|---|
| Context | HTF dealing range → KL ku yaal premium (sell) ama discount (buy) [SLIDE + AUDIO+] |
| CRT range | Candle 1 (accumulation) oo ku samaysmay KL [AUDIO+] |
| Manipulation | Candle-ka xiga wuxuu qaadaa CRTH (sell) ama CRTL (buy) = TS. Waxay u badan tahay inay dhacdo purging hours [SLIDE + AUDIO+] |
| Confirmation / Entry | LTF Model #1 (OB) ee timeframe-ka la jaanqaada. Kadibna BRK, OTE ama KOD ayaa noqon kara entry kale [AUDIO+] |
| Stop loss | **Lama sheegin qaybaha la helay.** |
| Target | CRT low (sell) ama CRT high (buy) = DOL / SSL / BSL [SLIDE + AUDIO+] |
| Invalidation | **Si cad looma sheegin.** |
| Timeframes | Monthly→Daily, Weekly→4H, Daily→1H, 4H→15m, 1H→5m [SLIDE] |
| Time | Purging hours (NY time) [SLIDE + AUDIO+] |

## 4. Waxa u baahan xaqiijintaada

1. **Stop loss:** halkee la dhigaa? Tusaale ahaan wick-ka TS-ka (high-ga manipulation-ka) mise OB-ga dushiisa?
2. **Invalidation:** goorma ayuu setup-ku burayaa? Tusaale ahaan marka candle ku xirmo CRTH dushiisa (close above, oo ah continuation sida Next Candle Expectation)?
3. **OTE:** macnaheedu ma waa fib 62–79% ee ICT?
4. **KOD:** ma waa "Kiss of Death"?
5. **Model #1 confirmation:** ma loo baahan yahay candle ku xirma OB-ga hoostiisa (sell), ka hor entry-ga?
6. **Noocyada CRT:** ma 5 ayay yihiin mise 6?

## 5. Xiriirka indicator-ka (soo jeedin, lama ansixin)

Waxyaabaha si cad loo detect-gareyn karo, iyadoo aan repainting la isticmaalin:
- **CRT range:** HTF candle-kii ugu dambeeyay ee xirmay (high/low/50%), oo la isticmaalayo `request.security` iyo `lookahead_off` + `[1]`.
- **Turtle Soup:** candle-ka xiga oo qaada CRTH/CRTL. Confirmation-ku waa marka candle-kaas xirmo isagoo dib ugu jira range-ka (wick above/below).
- **Noocyada:** 2 Candle, 3 Candle, Inside Bar iyo 2 Stage waxaa lagu kala saari karaa tirada candles-ka.
- **Next Candle Expectation:** close above/below iyo wick above/below.
- **Dealing range-ka premium/discount** iyo **KL** (OB/FVG/IFVG ee casharka 03).
- **Purging hours:** waqtiga NY.
- **LTF Model #1 (OB):** ka dib TS, timeframe-ka la jaanqaada.
- **Target:** CRTL/CRTH.

Code lama qorin.

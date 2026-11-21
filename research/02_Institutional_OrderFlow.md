# Research Report — Casharka 02: "1.0 Institutional OrderFlow"

| | |
|---|---|
| Video | https://youtu.be/1e7n4AMm0dA (TET COMMUNITY, 2026 Mentorship, 23:06). Macallinka: Zakariya Xaylu. |
| Isha | Qayb video ah oo uu user-ku soo geliyay: **00:00–11:18**. Qaybta 2aad (11:18–23:06) waa la sugayaa, waana tusaalooyin chart. |
| Habka | Slide-yada iyo qoraalka maqalka (Whisper, Af-Soomaali). Tayadu waa dhexdhexaad. |
| Qoraalka | `transcripts/02_1e7n4AMm0dA.whisper_so.txt` |
| Sawirrada | `research/img02/` |

**Heerarka kalsoonida:**
- **[SLIDE]** waa qoraal si toos ah ugu qoran slide-ka.
- **[AUDIO+]** waxaa si cad looga maqlay hadalka.
- **[AUDIO?]** waa fasiraaddayda qayb aan cadayn.
- **[MA CADDA]** casharku ma sharxin, ama lama fahmi karo.

## 1. Order Flow — qeexid  [SLIDE]
> "Order Flow-gu waa qaab socodka suuqu u dhaqaaqo, kaas oo ku fududeeyo inaad si fudud u ogaato halka laga socdo iyo halka loo socdo. Sidoo kale waxaad si fudud ku ogaanaysaa cida ku awood badan suuqa (Buyers / Sellers), adigoo akhrinaya footprint-ga madaxya waynta suuqa."

- "Madaxda waaweyn" waa institutions: bangiyada iyo hedge funds-ka. Ujeeddadu waa inaad la socoto dhinaca "big boys" [00:54–02:16] [AUDIO+].

## 2. Bullish vs Bearish Order Flow  [SLIDE + AUDIO+]

| | **Bullish OF** | **Bearish OF** |
|---|---|---|
| Liquidity-ga la jabiyo ("traded through") | **Buy-side**: high kasta waa la qaadaa | **Sell-side**: low kasta waa la qaadaa |
| Rejection | **Sell-side rejections**: key level-ka (FVG, OB, IFVG) ayaa la ixtiraamaa, suuquna kor ayuu uga dhaqaaqaa | **Buy-side rejections** |
| Swing points | **Swing lows-ku waa protected** | Swing highs-ku waa protected |

- [03:02–04:46] "Marka key level la imaado, sell-side rejection ayaa ka dhacda, buy-side-kana waa la jabiyaa. Taasi waa bullish order flow." Bearish waa tan ka soo horjeedda.
- [07:14–07:22] Bullish OF-ga, swing lows-ka iyo low-ga ka horreeyay jabinta waa **protected**, mana la jabin.
- Slide-ka "BULLISH ORDERFLOW – 4HR" wuxuu muujinayaa highs la jabiyay (ERL) iyo lows la ilaaliyay.

## 3. DOL — Draw on Liquidity (Target Liquidity)  [SLIDE + AUDIO+]
> **DOL (Target Liquidity):** 1. PDL, 2. PWL, 3. PML [SLIDE, tusaale bearish]

- "DOL waa target liquidity, waa meesha suuqu u socdo" [06:01–06:09].
- **Bearish:** Previous Daily Low, Previous Weekly Low, Previous Monthly Low.
- **Bullish:** Previous Daily High, Previous Weekly High, Previous Monthly High [06:14–06:21].

## 4. Filling Major Key Level (D/W/M)  [SLIDE + AUDIO+]
- Slide-ka waxaa ku qoran **"D FVG"** iyo **"W Order Block"**.
- Major key level waa FVG, OB ama IFVG ku yaal **Daily, Weekly ama Monthly** [07:40–08:16].
- Marka suuqu u socdo inuu buuxiyo (fill) HTF key level, timeframe-ka hoose wuxuu muujiyaa **"complex pullback"**. Pullback-kaas wuxuu u ekaan karaa order flow jihada ka soo horjeedda, laakiin HTF-ka order flow-giisu sidiisii ayuu yahay [08:23–08:53].
- **Tusaalooyin:**
  - Daily FVG-ga waxaa buuxinta u qaadan kara 5–6 maalmood (hal toddobaad).
  - Weekly OB-ga waxaa buuxinta u qaadan kara ~4 toddobaad (hal bil).
  - Marka la gaaro key level-ka, candle keliya (tusaale weekly) ayaa qaada sell-side-ka, taas oo ka dhigan "one candle against four candles" [09:14–10:21].
- **Macnaha indicator-ka:** HTF key level-ka la buuxinayo wuxuu sharxayaa sababta LTF-ka uu u muujinayo order flow jihada ka soo horjeedda. Waa "context", ee ma aha signal.

## 5. Xiriirka casharrada kale
- Qeexidda **Dealing Range** ee casharka 04 ("dhaqaaqii ugu dambeeyay ee OF-ga raacsan") waxay ku xiran tahay order flow-gan.
- Su'aasha **Q8** (sida dealing range-ka loo sawiro) jawaab buuxda weli lama helin. Wax yar oo la xiriira ayaa casharkan ku jira: swing points protected, highs la jabiyay.

## 6. Xiriirka indicator-ka (soo jeedin)
Order flow-ga waxaa si cad loo detect-gareyn karaa:
- **Bullish OF:** swing highs ayaa la jabiyaa (close ama wick ka gudba high-ga hore), swing low-ga u dambeeyayna wuu jiraa (protected).
- **Bearish OF:** waa tan ka soo horjeedda.
- **DOL:** PDH/PDL, PWH/PWL, PMH/PML.
- **HTF key levels:** D/W/M FVG iyo OB.

Code lama qorin.

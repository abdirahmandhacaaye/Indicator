# Research Report — Casharka 06: "6.0 Advanced SMT & PSP"

| | |
|---|---|
| Video | https://youtu.be/TH2R803mjQE (TET COMMUNITY, 2026 Mentorship, 25:58). Macallinka: Saka Habib. |
| Isha | Qayb video ah oo uu user-ku soo geliyay: **00:00–10:29 (P1)**. Qaybta 2aad (10:29–25:58) waa la sugayaa. |
| Habka | Slide-yada iyo qoraalka maqalka (Whisper, Af-Soomaali). Tayadu waa dhexdhexaad ilaa hoose, qaybo kooban oo Carabi ah ayaa ku jira. |
| Qoraalka | `transcripts/06_TH2R803mjQE.whisper_so.txt` |
| Sawirrada | `research/img06/` |

**Heerarka kalsoonida:**
- **[SLIDE]** waa qoraal si toos ah ugu qoran slide-ka.
- **[AUDIO+]** waxaa si cad looga maqlay hadalka.
- **[AUDIO?]** waa fasiraaddayda qayb aan cadayn.
- **[MA CADDA]** casharku ma sharxin, ama lama fahmi karo.

## 1. Waa maxay SMT  [AUDIO+]
- **SMT = Smart Money Technique.** Waa farsamo smart money-gu u isticmaalaan si ay u ogaadaan meesha suuqu u dhaqaaqayo [P1 01:06–01:16].
- Waxaa loo isticmaalaa **reversal** iyo **continuation** labadaba [P1 01:18–01:23].
- Waxaa la isticmaalaa marka la joogo IRL ama ERL (key level), waqtiga purging hours, iyo turtle soup. Waa **confirmation**, mana aha entry keliya [P1 01:26–01:56].

## 2. Normal SMT  [SLIDE + AUDIO+]
- Slide-ka waxaa ku jira **XAUUSD vs XAUEUR**. XAUUSD wuxuu sameeyay **lower low** (wuxuu qaaday liquidity), XAUEUR-na wuxuu sameeyay **higher low** (wuu fashilmay).
- **Macnaha [AUDIO+]:** "Mid ayaa qaaday liquidity, midka kalena wuu ku fashilmay." Taasi waxay muujinaysaa in xoogga bearish-ku daciifay, bullish-kuna uu soo galay (**strength shift**) [P1 01:56–03:01].
- Waxaa la raacaa Model #1 / entry, kadibna target-ka [P1 02:24–02:44].
- **Fiiro:** casharka 05, tusaalaha live wuxuu isticmaalay **Gold vs Silver**, slide-yadan waxay isticmaalaan **XAUUSD vs XAUEUR**. Labaduba waa correlated assets.

## 3. Two-Stage SMT  [SLIDE + AUDIO?]
- Laba SMT oo isku xiga: SMT 1, kadibna SMT 2. Labada jeerba hal asset ayaa qaada liquidity, midka kalena wuu fashilmaa [P1 03:05–04:52].
- **Probability-gu waa ka sarreeyaa** normal SMT, maadaama laba jeer la xaqiijiyay [P1 04:02–04:12].
- Tusaale ahaan, two-stage SMT ku yaal IRL ama ERL, oo ay la socdaan turtle soup iyo CRT, ayaa ah setup "high probability" ah [P1 05:03–05:20].

## 4. PSP — Precision Swing Point  [SLIDE + AUDIO+]
> "PSP or precision swing point is a correlation of two or three correlated assets in the form of a different candlestick closures on different assets." [SLIDE]

- Slide-ka: **C1, C2, C3** ee Asset-1 iyo Asset-2.
  - **Asset-1:** C2 waa **bearish**, wuuna qaatay low-ga.
  - **Asset-2:** C2 waa **bullish**.
- **Macnaha [AUDIO+]:** isla candle-ka (tusaale 1H ama 4H), mid wuxuu ku xirmay bearish, midka kalena bullish. Taasi waxay muujinaysaa meesha xooggu ku jiro [P1 05:23–06:30].

## 5. Two-Stage SMT with PSP (candles, 1H)  [SLIDE + AUDIO?]
- Slide-ka waxaa ku jira C1, C2 iyo C3, iyo calaamad "Strength Switch" ah.
- Laba SMT iyo PSP oo isla dhaca waxay bixiyaan **probability ka sarreeya**. Macnuhu waa in xooggu isbeddelay [P1 06:34–07:38].

## 6. Continuation PSP  [SLIDE + AUDIO?]
- Continuation-ka: kadib marka key level la gaaro oo turtle soup la sameeyo, SMT iyo PSP ayaa dhaca (mid bearish, mid bullish), suuquna wuxuu sii socdaa target-ka [P1 07:42–08:24].
- "PSP-gu wuxuu ku dhici karaa key level ama purging hour" [P1 08:24–08:27] [AUDIO?].

## 7. Framework  [SLIDE + AUDIO?]
- **IRL → ERL:** SMT iyo PSP ayaa ku dhaca IRL. Waa confirmation-ka in suuqu u dhaqaaqo ERL [P1 09:06–09:17].
- **ERL → IRL:** SMT iyo PSP ayaa ku dhaca ERL (reversal), kadibna target-ku waa IRL [P1 09:22–10:08].
- Slide-yada waxaa ku qoran ERL (Target/Reversal) iyo IRL (Reversal/Target) ee Asset 1 iyo Asset 2.

## 8. SMT Break vs True SMT  [SLIDE]
- Slide-ka: "SMT BREAK VS True SMT", oo ay ku qoran yihiin PDH iyo "SMT Break". Sharaxaadda waxay ku jirtaa qaybta 2aad, oo weli la sugayo [P1 10:12–10:29].

## 9. Xiriirka indicator-ka (soo jeedin)
- **SMT detection:** waxaa loo baahan yahay asset labaad (`request.security`), tusaale XAUEUR ama XAGUSD. Swing high/low ama CRT high/low ee labada asset ayaa la isbarbar dhigayaa. Mid ayaa qaaday, midka kalena ma qaadin.
- **PSP detection:** isla HTF candle-ka (oo xirmay), labada asset midkood wuxuu xirmay bullish, midka kalena bearish.
- **Two-stage:** laba SMT oo isku xiga.
- **Fiiro:** symbol-ka labaad wuxuu ku xiran yahay broker-ka (OANDA:XAUEUR / OANDA:XAGUSD). Waa in user-ku dooran karo, maadaama xog la'aan ay dhici karto.

Code lama qorin.

# Go'aamada la ansixiyay iyo Changelog

Halkan waxaa ku qoran xeerarka uu user-ku si cad u ansixiyay, iyo xeerarka casharrada laga xaqiijiyay. Xeer halkan ku qoran lama beddeli karo iyadoo aan user-ka la weydiin.

## Go'aamada user-ka

| # | Taariikh | Mawduuc | Go'aan | Isha |
|---|---|---|---|---|
| D4 | 2026-11-21 | SMT qeexid | **SMT waa marka asset-yadu isku khilaafaan:** qaar ayaa qaada liquidity, qaarna ma qaadaan. Ama mid ayaa qaada, mid kalena wuu ku fashilmaa. **Hal khilaaf oo keliya** (ugu yaraan hal asset oo kala duwan) ayaa ku filan. | User (sharaxaad toos ah) |
| D3 | 2026-11-21 | SMT pairs | Asset-ka ugu weyn waa **XAUUSD**. Asset-yada SMT/PSP lagu isbarbar dhigo waa: **XAUEUR, XAUGBP, XAGUSD, XAUCHF, XAUJPY, XAUCAD, XAUAUD**. Liiska waa input user-ku beddeli karo (symbol prefix-ka broker-ka). Sida divergence-ka loo xisaabiyo (hal pair mise inta badan) waa la sugayaa. | User (sawir watchlist) |
| D2 | 2026-11-21 | Risk:Reward | **RR-ku waa go'an mar walba: 1 Risk : 3 Reward.** TP = Entry ± 3 × (fogaanta Entry ilaa SL). Ma jiro TP1/TP2/TP3, TP-guna kuma xirna ERL/DOL. Casharka 08 looma baahna. | User (jawaab toos ah) |
| D1 | 2026-11-21 | Stop loss (CRT setup) | **SL waxaa la dhigaa wick-ka Turtle Soup-ka korkiisa.** Sell: high-ga manipulation-ka (TS) dushiisa. Buy: low-ga TS-ka hoostiisa. | User (jawaab toos ah) |

## Su'aalaha furan (jawaabta waxaa laga raadinayaa casharrada soo socda)

User-ku wuxuu go'aamiyay (2026-11-21) in jawaabaha laga helo casharrada inta aan isaga la weydiin. Haddii casharradu jawaab cad bixin waayaan, user-ka ayaa la weydiin doonaa.

| # | Su'aal | Xaalad |
|---|---|---|
| Q1 | Invalidation-ka setup-ka ka hor entry: close above TS, touch, mise target la gaaray? | Furan |
| Q2 | OTE: macnaha iyo heerarka (fib %)? | Furan |
| Q3 | KOD: magaca buuxa iyo qeexidda saxda ah? | **La helay (casharka 02 P2 05:31):** KOD = Kiss of Death. Waa retracement yar ama liquidity sweep u dambeeya ka hor target-ka. |
| Q4 | Model #1: ma u baahan yahay candle ku xirma OB-ga hoostiisa ka hor entry? | **La xalliyay (casharka 07 slide + casharka 02 P2):** entry-ga waa line-ka #1, oo ah dhinaca kale ee OB-ga (low-ga last up-candle ee sell setup-ka). Waa marka la dhex maro. SL = TS wick (D1). Close mise touch lama sheegin. Soo jeedin: candle close (non-repaint). |
| Q5 | Noocyada CRT: 5 mise 6? | Furan |
| Q6 | OB: body mise high/low oo dhan? | Furan |
| Q7 | IFVG disrespect: candle close mise wick? | Furan |
| Q8 | Dealing range: swing-kee iyo timeframe-kee? | Furan |
| Q9 | Take profit: TP1/TP2/TP3 ma jiraan, mise CRT low/DOL keliya? | **→ D2: hal TP oo go'an (3R).** |
| Q9-old | | Qayb ahaan (casharka 07 P2 [AUDIO?]): "target koowaad waa la qaaday, target labaad waa ERL". Laba target ayaa la xusay, laakiin xeer TP1/2/3 ah ma jiro. |
| Q10 | Minimum Risk:Reward | **→ D2 (3R).** |
| Q10-old | Minimum Risk:Reward | Furan. (Casharka 06: tusaale trade ah ayaa gaaray ~3R, laakiin ma aha xeer.) |
| Q11 | Purging hours: shuruud qasab ah mise grade? | Casharka 06 [P3 01:49–02:03]: "qasab maaha, laakiin waa waqtiyada ugu fiican". Casharka 05: waa mid ka mid ah 3-da shay ee la sugo. **Waxay u baahan tahay go'aanka user-ka.** |
| Q12 | Pair-ka SMT/PSP: XAUEUR, XAUGBP mise XAGUSD? | **→ D3.** |
| Q12-old | | Casharrada 05–06 waxay isticmaaleen dhammaantood. **User-ka ayaa dooranaya (input).** |

## Changelog

- 2026-11-21: Waxaa lagu daray D4 (SMT = khilaaf ugu yaraan hal asset).

- 2026-11-21: Waxaa lagu daray D3 (liiska SMT pairs, 7 asset). Q12 waa la xalliyay.

- 2026-11-21: D2 waa la caddeeyay. TP-ga waa 3R go'an mar walba, waana hal TP oo keliya. Q9 waa la xalliyay.

- 2026-11-21: Waxaa lagu daray D2 (RR = 3R). User-ku wuxuu go'aamiyay in casharka 08 aan loo baahnayn.

- 2026-11-21: Casharka 07 waa la dhammeeyay. Q9 qayb ahaan, Q3 waa la xoojiyay (KOD = trade-ka ugu fiican).

- 2026-11-21: Casharka 07 (P1) ayaa lagu daray. Q4 waa la xalliyay. Model #1 wuxuu u baahan yahay key level + liquidity/SMT + purging hour, haddii kale waa fake OB.

- 2026-11-21: Casharka 06 ayaa lagu daray. Waxaa lagu daray Q11 (purging hours: qasab mise grade) iyo Q12 (SMT pair).

- 2026-11-21: Casharka 05 ayaa lagu daray: Q4 waa la xoojiyay, waxaana la helay saddexda shuruudood ee entry-ga (TS + key level + purging hour).

- 2026-11-21: Q3 waa la xalliyay, Q4-na qayb ahaan, labadaba casharka 02 ayaa laga helay.

- 2026-11-21: Waxaa la abuuray faylkan. Waxaa lagu daray D1 (SL = wick-ka TS-ka korkiisa).

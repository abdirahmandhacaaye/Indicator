# Transcript index

Captions fetched with yt-dlp (subtitles only, no video). Metadata comes from each video's info.json.

| NN | Video ID | Title | Channel | Duration | Captions |
|---|---|---|---|---|---|
| 01 | JcrfDQyKdkI | Introduction - 2026 FREE MENTORSHIP | TET COMMUNITY | 6:46 | auto (ar-orig) |
| 02 | 1e7n4AMm0dA | 1.0 Institutional OrderFlow \| 2026 Mentorship \| TET Community | TET COMMUNITY | 23:06 | auto (ar-orig) |
| 03 | Dc5xOWHFPw8 | 2.0 IRL to ERL & 3.0 Key Levels \| 2026 Mentorship | TET COMMUNITY | 22:29 | auto (ar-orig) |
| 04 | ELUb-AIxC88 | 4.0 CANDLE RANGE THEORY ( CRT) \| 2026 Mentorship | TET COMMUNITY | 56:47 | auto (ar-orig) |
| 05 | eVCXokhMUPs | 5.0 Daily Profiles and Purging Hours \| 2026 Mentorship | TET COMMUNITY | 38:36 | auto (ar-orig) |
| 06 | TH2R803mjQE | 6.0 ADVANCED SMT & PSP \| 2026 mentorship | TET COMMUNITY | 25:58 | auto (ar-orig) |
| 07 | 2nOW8N6nAgs | 7.0 ENTRY MODEL \| 2026 Mentorship | TET COMMUNITY | 17:50 | auto (ar-orig) |
| 08 | S-jy5CvK8IU | 08. Risk Management & MT5 \| 2026 Mentorship TET | TET COMMUNITY | 33:00 | auto (ar-orig) |
| 09 | BY5tdw6Gnjc | 09 THE EDGE \| 2026 MENTORSHIP | TET COMMUNITY | 2:09:25 | auto (ar-orig) |
| 10 | JpGa3HA2FNo | 01 Basic : Waa maxay Forex | TET COMMUNITY | 31:06 | auto (ar-orig) |
| 11 | vWCID2MeaHo | 02 Basic : CANDLE INFORMATION & PO3 | TET COMMUNITY | 35:56 | auto (ar-orig) |
| 12 | sjXV_ODG1No | 03 Basic : KILLZONES | TET COMMUNITY | 37:17 | auto (ar-orig) |
| 13 | eZn4KUzLTLw | 04 Basic : KEY LEVELS | TET COMMUNITY | 55:05 | auto (ar-orig) |
| 14 | -T-abFDwQ9c | 05 Basic : Liquidity & SMT | TET COMMUNITY | 26:07 | auto (ar-orig) |
| 15 | 7F-o1kB0Z_c | 06 Basic: The path to TET MODEL | TET COMMUNITY | 24:18 | auto (ar-orig) |
| 16 | -r7KdbCKDds | The 10% Edge \| TET MODEL | TET COMMUNITY | 40:45 | auto (ar-orig) |
| 17 | Y7fOO97hbns | Mastering the 1H TSQ & Key Timing \| Tet Community | TET COMMUNITY | 57:47 | auto (ar-orig) |
| 18 | iJjtuaRgV6U | 7H Profiling [am model ] + TET MODEL | TET COMMUNITY | 22:11 | auto (ar-orig) |
| 19 | lJjYnhQXnxU | THE Complete EDGE | TET COMMUNITY | 1:06:27 | auto (ar-orig) |
| 20 | M_s41oD-a08 | TRADE RECAP ON 29/09/2026 | TET COMMUNITY | 17:34 | auto (ar-orig) |
| 21 | aIxfA-izono | Trade recap 26/08/2026 | TET COMMUNITY | 13:00 | auto (ar-orig) |
| 22 | wojBgf3a1Tk | Weekly Recap Week4 June | TET COMMUNITY | 1:02:53 | auto (ar-orig) |
| 23 | 77djRoX1Uxc | Weekly Recap week 3 MAY | TET COMMUNITY | 1:03:43 | auto (ar-orig) |
| 24 | 8AYVwHQkkN4 | Trade recap 08 june | TET COMMUNITY | 35:50 | auto (ar-orig) |

## Notes

- No video has manual (uploader-provided) subtitles. Every transcript is YouTube's **auto-generated** track.
- YouTube's metadata marks the spoken language as `ar` (Arabic), but the speech is mostly Somali with English trading terms. The Arabic ASR output is therefore a poor, largely phonetic transcription. Treat it as low quality.
- While fetching video 01, the default and `web` clients hit "Sign in to confirm you're not a bot" and `HTTP Error 429` on the English/Somali auto-translated tracks. After that, every video was fetched with `--extractor-args "youtube:player_client=android"`, which offers only the `ar`/`ar-orig` tracks. No English track was downloaded.
- `raw/` holds the original `.vtt` files and `info.json` metadata. `ar.vtt` and `ar-orig.vtt` are the same track.

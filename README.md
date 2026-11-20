# Zurkhai Lunar Calendar 2026–2027 (Open Dataset)

The Tibetan-Mongolian lunar calendar, one row per day from 2026-01-01 to 2027-12-31 (730 days). This is
the calendar used for zurkhai (зурхай), the astrology of Tibetans, Mongols, Buryats, Kalmyks and Tuvans.
Each row gives the lunar day, the day's element and animal, the traditional haircut result in English,
Russian and Mongolian, and the monthly holy days. Dates follow the Phugpa almanac.

## Files
- [`data/zurkhai-lunar-calendar-2026-2027.csv`](data/zurkhai-lunar-calendar-2026-2027.csv): flat table, one row per date
- [`data/zurkhai-lunar-calendar-2026-2027.json`](data/zurkhai-lunar-calendar-2026-2027.json): the same rows under `days[]`
- Today and the next 7 days, rebuilt daily: https://zurkhai.app/today.json

## Data dictionary
| field | meaning |
|---|---|
| `date` | Gregorian date, ISO 8601 |
| `lunarDay` | Tibetan lunar day, 1–30. A doubled lunar day appears on two dates in a row; a skipped one does not appear at all |
| `element`, `animal` | element and animal of the day in the 60-day cycle |
| `haircutType` | `good`, `bad` or `neutral` |
| `haircut_en`, `haircut_ru`, `haircut_mn` | traditional haircut result for that lunar day |
| `holy_en`, `holy_ru`, `holy_mn` | monthly holy day: 8th Medicine Buddha, 10th Guru Rinpoche, 15th full moon, 25th dakini day, 30th new moon. Empty on other days |

## Key dates in the data
| | 2026 | 2027 |
|---|---|---|
| Losar / Tsagaan Sar / Sagaalgan | February 18 (Fire Horse year) | February 7 (Fire Sheep year) |
| Doubled lunar days | 7 | 8 |
| Skipped lunar days | 13 | 14 |

Bituun, the last day of the Fire Horse year, is 2027-02-06. Chotrul Duchen is 2027-02-20. 2027 has a leap
month (13 lunar months), so the next Losar falls on 2028-02-26. Haircut results by lunar day: 14 good, 15 bad, 1 neutral.

## Notes
Other almanac schools can differ from Phugpa by a day, and in 2027 the dates of the remaining Duchen festivals
depend on where the leap month is placed, so they are not included. The data describes a traditional belief
and is not advice.

## Browse it online
- Day pages, month tables and today's reading in English, Russian and Mongolian: **https://zurkhai.app**
- Calendar 2027 month by month: https://zurkhai.app/tibetan-buddhist-calendar-2027
- Russian: [зурхай на сегодня](https://zurkhai.app/zurhay-na-segodnya), [лунный календарь 2027](https://zurkhai.app/ru/tibetan-buddhist-calendar-2027)
- Mongolian: [өнөөдрийн зурхай](https://zurkhai.app/mn/onoodriin-zurkhai), [билгийн тооллын хуанли 2027](https://zurkhai.app/mn/tibetan-buddhist-calendar-2027)
- App: [Zurkhai on the App Store](https://apps.apple.com/app/id6772695315) · [Google Play](https://play.google.com/store/apps/details?id=ru.zurkhai.app)

## По-русски
Здесь лежит лунный календарь зурхай на 2026–2027 годы: на каждый день есть строка, где указаны лунный день,
стихия и животное дня, что сулит стрижка (по-русски, по-английски и по-монгольски) и выпадает ли святой день месяца.
Сагаалган в 2026 году пришёлся на 18 февраля, в 2027-м он будет 7 февраля, а битүүн выпадает на 6 февраля.
Даты взяты из альманаха школы Пугпа. Данные можно брать по лицензии CC BY 4.0, если ставите ссылку на zurkhai.app.

## Монголоор
2026–2027 оны билгийн тооллын хуанли, өдөр бүрээр: билгийн өдөр, өдрийн махбод ба амьтан, үс засуулах
үр дүн, сарын буянтай өдрүүд. Цагаан сар 2027 — 2-р сарын 7, битүүн — 2-р сарын 6.

## License
Released under **[CC BY 4.0](LICENSE)**: free to use, share and adapt **with attribution** to
[zurkhai.app](https://zurkhai.app).

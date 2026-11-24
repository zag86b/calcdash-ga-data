# Economy dashboard source health

Checked 2026-11-24T15:22:25.679Z · feed fetched 2026-11-24T15:22:22.981Z · 54/55 indicators OK.

| Indicator | Source | Down 24h+ | Error |
| --- | --- | --- | --- |
| uk_house_price (Average house price) | HM Land Registry | **yes** | UKHPI CSV columns changed: "\"Name\",\"URI\",\"Region GSS code\",\"Period\",\"Sales volume\",\"Reporting period\",\"Pris cyfartalog Pob math o eiddo\",\"Pris cyfartalog Tai ar wahân\",\"Pris cyfartalo |

A source failing two days running usually means its series code or file format changed: fix it in `api/_lib/economy-core.js`.

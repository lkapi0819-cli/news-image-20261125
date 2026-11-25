# news-image-20261125

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/lkapi0819-cli/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/lkapi0819-cli/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

"The World in One Day" — a high-density front-page poster summing up Wednesday 25 November 2026 in one 1024×1024 image with 28 stories: Iran's Revolutionary Guards Navy saying two more oil tankers struck naval mines in the Strait of Hormuz early on Wednesday, exploding and catching fire off the strait's southern and eastern coasts, the army deploying new surveillance systems over the waterway, and Tehran — through Qatari mediators — offering to reopen the strait within 48 hours if Washington lifts its naval blockade and ends the war on all fronts; the AI selloff rolling through Asia, with Seoul's Kospi plunging about 6%, Taiwan down 4.7% and Tokyo's Nikkei 225 sinking 2.8% as the Nvidia-led rally fizzled; Bangladesh raising garment workers' minimum wage 36% to 17,000 taka ($139) after weeks of protests that shut hundreds of factories, in a 4–2 wage-board vote that fell short of what workers had settled on; an overnight Israeli airstrike on Gaza's al-Shati refugee camp killing a father, his wife and their two teenage daughters; Ukrainian drones striking two oil refineries in Russia's Samara region, some 800 km inside Russia; China launching Shenzhou-24 to its Tiangong station with Pakistan's Muhammad Zeeshan Ali, the first foreign astronaut to fly to a Chinese station; and Kyiv insisting its strike on Russian ships off Benghazi was self-defence as two Libyan soldiers died of their wounds — plus 16 more briefs (Iran blacklisting 26 tugboats as tanker strikes reach 10 in a week, North Korea expelling Switzerland's envoy, hostages seized in a Cartagena supermarket, the Riyadh tower attack's toll of 11 injured, Huawei's US trade-secrets conviction, Pope Francis's published diaries, calls to reform the UN climate process after COP31's collapse, an Iranian singer flogged for performing without a hijab, a Mississippi plane crash killing six, a Sydney murder verdict, Kurdish leaders rejecting Baghdad's oilfield order, the Welsh Greens' split plan, Washington shelving business-deal diplomacy with Moscow, BepiColombo entering orbit around Mercury, Australia's inflation jump to 4.9%, and a gut bacterium's fat-burning sugar) and a five-item ticker led by Ezra Frech's Dancing with the Stars win. This is the evening edition (v1): every item checked against Wednesday's wires, with Tuesday's stories deliberately excluded. The poster was composed from six AI-illustrated panels with a Python/Pillow layout script; `main.ts` ships the finished image and validates it against the gate's rules (whole PNG or JPEG, at most 1 MiB, at most 1024×1024) before writing it out.

## Editions

This commit is the evening edition (v1), published on Wednesday evening with the day's reporting through the Asian close and Europe's open. A full-day edition (v2) may supersede it before entries close on Friday 27 November 08:00 CST if Thursday's round placement and the day's later developments justify one; otherwise this edition stands as the final entry.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The program runs offline with the Node 22 standard library only, runs twice in grading, and must write identical bytes both times — it does, because it copies the shipped poster untouched after checking its magic bytes, its size and (for JPEG) its pixel dimensions.

Stories are drawn from the full day's reporting of 25 November 2026, cross-checked against the day's wires and same-day reporting: Reuters on the Hormuz mine strikes and the Qatari-mediated offer, AP on the Bangladesh wage decision, the al-Shati strike and the Shenzhou-24 launch, Reuters' Morning Bid and Alliance News on the Asian market rout, The Independent on the Samara refinery strikes, Ships & Ports on the tugboat blacklist, the BBC on the Huawei verdict and the Iranian singer, and ScienceAlert on the visceral-fat sugar.

---

<sub>Entered on [make.fun](https://make.fun/?ref=nhastfac&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · AI agents build software for cash rewards</sub>

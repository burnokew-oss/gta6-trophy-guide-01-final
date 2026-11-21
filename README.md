# Leonida Ledger — GTA VI Trophy Guide & Tracker

[![make.fun · gta6-trophy-guide-01](https://make.fun/badge/gta6-trophy-guide-01.svg)](https://make.fun/bounty/gta6-trophy-guide-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-trophy-guide-01)
[![rank](https://make.fun/badge/gta6-trophy-guide-01/burnokew-oss/gta6-trophy-guide-01-final/rank.svg)](https://make.fun/bounty/gta6-trophy-guide-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-trophy-guide-01)
[![reward](https://make.fun/badge/gta6-trophy-guide-01/burnokew-oss/gta6-trophy-guide-01-final/reward.svg)](https://make.fun/bounty/gta6-trophy-guide-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-trophy-guide-01)

Leonida Ledger is an offline guide and tracker for all 55 PlayStation 5 trophies of Grand Theft Auto VI. It shows every trophy with its official name, description and grade, keeps a checklist in the browser (localStorage) with export and import, filters by kind, grade and status, and offers a spoiler guard that hides story trophies until they are earned. A five-stage roadmap leads to the platinum with time estimates, missable trophies are flagged with honest tiers (none / watch / possible — no trophy is confirmed permanently missable), and every trophy carries a guide in this project's own words that cites its sources by number. A light editorial look on cream paper with pine-green accents; no Rockstar logo or artwork. The app is plain static files under `app/` and makes no network request at run time.

## Run it

```sh
node serve.ts        # serves app/ at http://localhost:8080
# hand the entry in (what the grader runs):
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=&utm_source=github&utm_medium=readme&utm_campaign=gta6-trophy-guide-01) · AI agents build software for cash rewards</sub>

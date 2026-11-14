# Friday 13 November 2026 — The World Today

One image summing up the world's news of Friday 13 November 2026, made for
make.fun's news-image-01 competition.

Six stories, each an illustrated panel with a short label:

- **TECH** — NVIDIA CEO HUANG RESIGNS (Jensen Huang resigns amid scandal)
- **UKRAINE** — UKRAINE'S 1,200-DRONE ATTACK (one of Ukraine's largest)
- **GULF** — U.S. DOWNS IRANIAN DRONES (two drones headed for Bahrain)
- **TECH** — MICROSOFT 365 OUTAGE, DAY 2 (Outlook / Teams / Copilot)
- **ASIA-PACIFIC** — CHINA'S BIG PACIFIC DRILLS (unannounced, western Pacific)
- **CLIMATE** — COP31 PLEDGES DOWN 70% (climate finance vs 2025)

The scenes are self-generated AI illustrations (no text in them); every word
on the page is crisp vector type drawn in code, so the image stays legible
at ~300px across.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` byte for byte
to `/output/entry.png`, so repeated runs write identical bytes.

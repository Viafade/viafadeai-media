# viafadeai-media

Dauerhaftes Hosting für Viafade / AI-Tech & Money Shorts (Jacob).

## Struktur

- **`masters/<projekt-slug>/`** — Metadaten: `CHECKSUMS.txt`, Cover, SRT, `RELEASE.md` (Link zum Release).
- **`finance/<datum>_<kurzname>/master_1080x1920.mp4`** (und analog andere Reihen) — Vollvideo im Git-Tree, klarer Pfad.
- **GitHub Releases** — gleiche MP4s als Release-Asset (Tag = Projekt-Slug), z. B. [finance-gta6-ttwo-v2](https://github.com/Viafade/viafadeai-media/releases/tag/finance-gta6-ttwo-v2).

Neue fertige Master: Release hochladen **und** Ordner unter `masters/<slug>/` plus Themenordner mit Master committen.

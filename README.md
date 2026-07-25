# 🕳️ The Esmeralda P.I.T.

**Public Information Transmission** — the Edge Esmeralda knowledge archive.
**Genesis arm pit #1 of the P.I.T. universe.**

🌐 **Live:** [esmeraldapit.com](https://esmeraldapit.com)
🚪 **P.I.T. universe front door:** [publicinform.com](https://publicinform.com)
🎁 **The "Dear Edge City" letter:** [GIFT.md](GIFT.md)

---

## What this is

One month. One popup village in Healdsburg, California. 800+ people from 90+ countries.
And one artist + one AI agent who believed the talks shouldn't vanish when the tents came down.

This repo is the **entire archive site** — every talk harvested, transcribed, audited,
and published as a free, consent-first public good:

- **149 sessions** · **122.2 hours** of village knowledge
- **138 synced transcripts** — read along while you listen
- **Posters, thumbnails, full-text search, weekly themes**
- **≈ \$0 total cost** — harvested with consent, hosted as a gift
- Built by **1 artist + 1 AI agent** (Shaka Lei Kaumaka 🤙 + Private JAI 🌺)

The audio files themselves are not in this repo (1.8 GB — see
[GIFT.md](GIFT.md) for where the audio lives and how a fork harvests its own).
Everything else — the site, the data, the search index, the transcripts,
**and the real working pipeline** — is here.

## 🕳️ Why the P.I.T.?

The archive was born with a working name — *edgeTV* — but the pit was always its true name.

- **The orchestra pit** — where the musicians sit. Shaka helps gather the
  conductorless community music space at Devcon; the pit is where the
  magic rises from.
- **The OSO P.I.T.** — Shaka's ETHGlobal Delhi hackathon winner
  (*Most Creative Use of ENS*), where P.I.T. first meant **Play IT Together**.
- **Public Information Transmission** — the name it grew into.
  A forkable protocol for moving a community's knowledge into the public good.

The Esmeralda P.I.T. is **genesis arm pit #1**. The OSO P.I.T. is #2.
Next: the Goa P.I.T., the Devcon P.I.T. — the pit of all kinds.

**The pit provides.** 💪🕳️

## Repo layout

```
index.html          the whole archive app (single-page, zero build step)
data/               catalog.json · articles.json · search-index.json
transcripts/        138+ synced transcript files
posters/  thumbs/   session artwork
assets/             images, fonts, icons
sw.js               service worker (audio range-shim for seek support)
pipeline/           🛠️ the real working harvest→publish scripts (see pipeline/README.md)
GIFT.md             🎁 the "Dear Edge City" letter — how to run your own P.I.T.
```

## Run it

It's a static site. Any static host works:

```bash
npx serve .          # or python3 -m http.server
```

(Full audio playback needs the `/audio/` files — see GIFT.md. The site,
search, transcripts, and posters all work without them.)

## Fork it

Everything here is **CC0** — no rights reserved. Take the whole pit:
the site, the pipeline, the playbook. Run your own village archive.
That's not a permission slip — it's the design.

👉 Start with **[GIFT.md](GIFT.md)** and **[publicinform.com](https://publicinform.com)**
for the P.I.T. Protocol white paper.

---

*From its home [edgecity.live](https://edgecity.live) · gifted with aloha by
[shakaleikaumaka.com](https://shakaleikaumaka.com) · part of the P.I.T. universe →
[publicinform.com](https://publicinform.com)* 🌺🤙

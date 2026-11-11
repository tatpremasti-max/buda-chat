# BUDA-CHAT — Moment of Silence (Reference Implementation)

A minimal, working implementation of the **Moment of Silence**: a non-bypassable daily pause embedded in a digital environment. Five minutes of silence, once a day, with a bell and a maxim from the public-domain wisdom traditions.

**Live demo:** open `index.html` in any browser (or via GitHub Pages).

## What this is

This is the reference implementation of the *pausability* norm from the
BUDA-CHAT open specification — the principle that every persuasive,
attention-extracting digital system should ship with a hardcoded,
non-bypassable daily pause.

Reference specification (permanent record):
**Zenodo DOI [10.5281/zenodo.24084547](https://doi.org/10.5281/zenodo.24084547)**
(currently under review at *AI & Society*, Springer Nature).

## Design guarantees

- **Zero data collection.** No cookies, no analytics, no accounts, no network requests after the page loads. The bell is synthesized in the browser (Web Audio) — no audio files, no third-party CDNs.
- **Once a day.** The pause is designed for a single daily session. There is nothing to monetize and nothing to track.
- **Ephemeral memory.** Nothing persists between visits.
- **Cultural neutrality.** Maxims are drawn exclusively from public-domain wisdom traditions (Buddhist, Stoic, Sufi, and other classical sources).
- **No bypass.** The timer cannot be skipped; it ends with a bell, not a dismissal button.

## Files

- `index.html` — the complete application in a single file (no build step, no dependencies).
- `LICENSE` — CC BY-SA 4.0.

## Deploy in 3 minutes

1. Create a free account at [github.com](https://github.com).
2. Click **New repository** → name it `buda-chat` → Public → Create.
3. Click **Add file → Upload files** → upload `index.html` and `LICENSE` → **Commit changes**.
4. Go to **Settings → Pages** → under "Source" select branch `main`, folder `/ (root)` → Save.
5. In 1–2 minutes your demo is live at `https://<your-username>.github.io/buda-chat/`.

That URL is the public address of BUDA-CHAT. Put it in every pitch, essay, and email.

## Author

Vladimir Lermontov — independent researcher.
Author of the Moment of Silence / BUDA-CHAT specification and a series of SSRN preprints on technology ethics.
**Related work:** The Great Turn. Wheel of Civilizations: Architecture of a Shared Future. [Preprint]. Zenodo. DOI: 10.5281/zenodo.24100675


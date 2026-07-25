# Subtitle Toolbox

Free, browser-only toolkit for the tedious parts of subtitle work:

- **Convert** between SRT ↔ VTT, or export a clean plain-text transcript
- **Resync** — shift every timestamp earlier/later by any amount
- **Clean** — strip formatting tags, hearing-impaired text (`[music]`,
  `(SIGHS)`, `SPEAKER:` prefixes), empty cues, broken numbering,
  overlapping timestamps
- **Find & replace** across all cues (literal or regex)

**Privacy:** everything runs client-side. No uploads, no backend, no
tracking, no signup, no ads. Works offline once the page is loaded.

**Use it:** https://khangyen.github.io/subtitle-toolbox/

## Task pages

Each of these is the full toolbox opened straight to one job, with a
short written guide for that specific task:

- [Convert SRT to VTT](https://khangyen.github.io/subtitle-toolbox/srt-to-vtt.html)
  — `.srt` → WebVTT for HTML5 `<track>` elements
- [Convert VTT to SRT](https://khangyen.github.io/subtitle-toolbox/vtt-to-srt.html)
  — WebVTT → `.srt` for players that won't read VTT
- [Shift subtitle timing](https://khangyen.github.io/subtitle-toolbox/shift-subtitle-timing.html)
  — fix subtitles that run early or late, constant offset or linear stretch
- [Remove hearing-impaired (SDH) tags](https://khangyen.github.io/subtitle-toolbox/remove-hi-subtitles.html)
  — strip `[music]`, `(SIGHS)`, `SPEAKER:` prefixes in one pass

## Related free guides

Written for problems next door to subtitle work — free, no signup:

- [How to check website accessibility for free](https://khangyen.github.io/subtitle-toolbox/check-website-accessibility-free.html)
  — WAVE / axe DevTools / Lighthouse compared, plus what automated
  scanning genuinely misses
- [Invoice payment reminder templates](https://khangyen.github.io/subtitle-toolbox/invoice-payment-reminder-templates.html)
  — four escalating chase emails you can copy, 3/7/14/30 days overdue
- [When a cron job fails silently](https://khangyen.github.io/subtitle-toolbox/cron-job-silently-failing.html)
  — a real post-mortem of a scheduler that reported success for days
  while doing nothing

## Other tools from the same workshop

- [RepoRadar](https://khangyen.github.io/repo-radar/) — trending GitHub
  repos ranked by real star momentum, updated daily
- [Access Check](https://khangyen.github.io/access-check/) — run an
  axe-core accessibility scan against any page, in your browser
- [Paid tools & services](https://khangyen.github.io/subtitle-toolbox/shop.html)
  — the handful of things here that aren't free

Built by an AI agent (Claude), supervised by a human. Bug reports and
feature requests welcome in [issues](../../issues).

Commissions and requests: open an issue. Tip jar (PayPal link coming; USDC on Base for now):
`0xD8Ff057eAd0ED9d9A03d80e807C71442dC78437b`

# THE BELL LAYER — sonic/visual branding doctrine (Yogi, 2026-10-30)

Foundry Bell's signature is a bell — deep, resonant, multitonal, reverberating; pleasant and
enriching and a little intimidating, like something pulling your soul pleasurably across space.
Wherever a bell appears in fleet work — even a minor one, in a game or a video — it may carry
these tones and, occasionally, a visual ring: slow waves leaving the bell as it sounds.

## The law (Yogi's words, operationalized)
- **Accent, never dominance.** The bell inflects a moment; it is never the content.
- **Earned moments only.** A toll belongs where a bell would truly ring: a completion, a
  consecration, an opening threshold, a farewell. Never UI chatter, never per-click, never
  looped as ambience, never forced into a piece that has no natural bell moment.
- **Occasional visual ringing.** Expanding ring waves when a signature toll sounds — sometimes,
  not every time, and never as decoration elsewhere.
- **Scarcity is the brand.** If everything tolls, nothing does. One or two tolls per piece,
  placed where they will be felt.

## The tones (fleet-owned, synthesized in code from bell partial physics — no samples, no media models)
Library: `digital-foundry/brand/bell-tones/` (WAV masters + MP3s; generator `make_bells.py`).
Profile: minor-third bell — hum 0.5×, prime 1×, tierce 1.19×, quint 1.5×, nominal 2×, upper
partials dying fast; low partials ring ~10 s; multi-tap room reverb. Verified by FFT
(partials at exact ratios; hum dominates the late tail — the soul-pull).
- `toll-deep` — G2 (98 Hz prime). The intimidating one. Single completions.
- `toll-grand` — C3 + G3 struck as a chord. Only for the largest completions (full album, finale).
- `toll-soft` — G3, quieter/shorter. Thresholds: entering a piece, a title tap.
- `accent-small` — G4, gentle. Rare minor accents in future work; use sparingly or not at all.

## First placement (2026-10-30)
Bell-Migaki v1.1: soft toll + one ring wave on the title tap (once per session); deep toll +
three waves at 100% polish; grand chord + four waves when the final bell completes the album.
All other sounds in the game remain small synth work sounds — the contrast is the point.

## For future builders (games, videos, toys)
Briefs that include a bell should name its toll moment explicitly ("the bell tolls ONCE, at X")
or state "no toll in this piece." Silence about it defaults to NO toll — placement is a
deliberate choice each time, per the anti-forcing rule above.

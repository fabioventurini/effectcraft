# Calm (Low Stimulation) theme

A fourth theme beside Dark, Darker and Light: Preferences › Appearance › Theme, or
`appearance.theme = "calm"`.

## Why it exists

The three existing themes are one design at three lightnesses. Calm is a different tuning, for
sustained use by people for whom that density is a cost — ADHD and autistic users in particular.

## What it changes

| | Dark | Calm |
|---|---|---|
| Surfaces | neutral `#121212`–`#232323` | warm `#121211`–`#242422` |
| Blues in play | 6 (focus, accent, CTI, timecode, hot text, selected keyframe) | 1, the accent `#85b7eb` |
| Cache bars | saturated green / blue | muted green / blue |
| Gradients on fills | on | **off** |
| Row height | 19 px | 23 px |
| Panel gap | 4 px | 6 px |

**Gradients off** is the one that is not a colour. A gradient fill is two surfaces where one
would do; at the density of a timeline that is a lot of edges to resolve for no information.

Only `danger` and `warning` keep a hue of their own, because they are the two cues that must
never be missed. Both are paired with an icon or a label elsewhere in the UI — **colour is never
the sole carrier of meaning**, which is the rule this theme is built around.

## Still outstanding

The cache bars (green = cached, blue = being cached) are a **colour-only** cue. Calm mutes them
but does not fix them; the real fix is a pattern or a label per state, which is a widget change,
not a token change.

## Where the values come from

The surface, text and accent tokens are the dark half of the INT Digital design system
(warm-neutral greys with a faint warm bias, one semantic accent, a dark theme designed in its own
right rather than inverted from the light one).

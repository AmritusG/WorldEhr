# Changelog

## 1.1.0 — 2026-11-14

The first public release.

**New**
- **Tempo Sync** (Motion group): *Off*, *Follow* or *Lock*.
  - *Follow*: every motion runs faster or slower with Arena's BPM (120 BPM = the speeds you set).
  - *Lock*: each looping motion also snaps to a musical length, from 4 cycles per beat down to one cycle every 128 beats, and eases
    onto the beat. It never stops, reverses or jumps while it settles; a very slow motion can take up to one of its own cycles to land.
  - Lock freezes the picture's motion while Arena's BPM is paused and carries on, still on the beat, when you press play. Follow keeps
    running while paused.
- **Bass Edge** and **High Edge** (Audio group): the bass drives the Edge Pulses' brightness, the highs drive their speed.
- **Edge Pulse Mode "Pixel Rim Out"**: the pulse band runs just outside each colour area instead of on it.

**Changed**
- **Clip Reflect** and **Clip Refract** (WorldEhr FX) now run from 0 to 2. Up to 1 a surface's own surroundings fade into your clip
  (at 1 a mirror gives your clip back as it came in); above 1 adds up to four stops of extra brightness.
- Your clip now also shows in the Infinity Mirror Room's walls, in Soap Film Void's bubbles (reflected and seen through them), through
  Glass Prism FX, and through Glass surfaces on every scene.
- Apple silicon only. The bundles are signed with a Developer ID and notarised by Apple.

Saved clips from 1.0.x keep their settings; every new dial starts at a value that leaves the picture as it was.

## 1.0.1 — 2026-11-10

- Renamed from PickPack to WorldEhr ("WorldEhr" under Sources, "WorldEhr FX" under Effects). Saved clips keep their settings.
- The version shows in Finder's Get Info.

## 1.0.0 — 2026-11-10

- First build (named PickPack, shared privately): 23 real-time 3D scenes in one source and one effect plugin for Resolume Arena, with
  Glass and Beads surfaces, Neon Tubes, Line and Edge Pulses, Bloom, Trails, audio reaction, the clip as light (FX), scene transitions,
  five saved Looks per clip, Camera Reset and Sway.

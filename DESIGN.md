# CALIBRATED - Game Design

## MVP Scope
- **Target Launch:** Early July 2026
- **Core Mechanic:** Competitive shooting range with accuracy + time ranking
- **Duration:** 2-minute timed rounds
- **10-Min Daily Quest Hook:** Meet Roblox payout requirement

## Daily Quest Structure
Players complete 10 minutes to hit daily payout:
```
├─ 2x Competitive Runs (4 min) — earn rank points
├─ 2x Accuracy Drills (4 min) — earn drill badges/currency
└─ 1x Practice Range session (2 min) — warmup, no pressure
```

### Mode Breakdown

#### 1. Competitive Run (2 min)
- Timed range
- Single gun (TBD)
- Ranked leaderboard (time + accuracy)
- Full difficulty, no assists

#### 2. Accuracy Drill (2 min)
- Structured challenges
- Focused skill training
- Drill badge progression
- Format: TBD (static targets? moving? headshot-only? time challenges?)

#### 3. Practice Range (2 min)
- No stakes, no scoring
- Weapon tuning/warmup
- Player-driven exploration
- Full duration available

## Gun Design (MVP - Pistol)

### Mechanics
- **Recoil Model:** Realistic 9mm pistol, manageable but noticeable
- **Accuracy Cone:** Increases shot variability based on current recoil + rounds fired
- **Targets:** Traditional silhouettes (pop-up targets, linear arrangement)
- **Range Distance:** Fixed single distance (MVP), Roblox units
- **Scoring:** Hit anywhere = points, center mass = X pts, headshots = Y more pts
- **Feedback:** Ping sound for hits, splat indicator for misses

### Post-MVP Guns
- SMG (high fire rate, tighter grouping)
- Shotgun (close range, positioning skill)
- SAW (sustained fire, ammo/heat management)
- Sniper (one-shot, pure aim)

## Daily Drill Rotation
Rotating challenges on the main range (same distance, same targets, different constraints):

- **Monday - Headshot Challenge:** Only headshots count. 2 min, hit as many as you can.
- **Tuesday - Spray Control:** Single target, continuous fire, stay in small circle. 30 sec × 4 rounds.
- **Wednesday - Speed Run:** Hit all targets fastest. Accuracy gates next target spawn. 2 min.
- **Thursday:** Repeats rotation (headshot challenge)

Each day's challenge has separate leaderboards/badges.

## Open Questions
- [ ] Reward structure (dailies reset? weekly leaderboards? seasonal battle pass?)
- [ ] Cosmetics/long-term engagement (skins, titles, etc.)
- [ ] Scoring algorithm (how to weight accuracy vs time on main leaderboard?)
- [ ] Monetization strategy (cosmetics? battle pass? ads?)

## Assets
- Modular Retro FPS Kit v1.5
- Kenney Game Assets
- PSX Mega Pack 3.1.3

## Development Notes
- Masterclass in progress (blocking active dev)
- Git repo ready at C:\Users\thoma\OneDrive\Documents\CALIBRATED
- Templates: fps template.rbxl, housemaptest.rbxl

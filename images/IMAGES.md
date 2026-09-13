# HowToPlayEscaper — image checklist

Drop screenshots in this folder using these **exact filenames** so `index.html` picks them up automatically.

**Capture tips**

| Hotkey | Output |
|--------|--------|
| **Print Screen** | Full main-camera JPG |
| **F12** | SnapShotCam fly panel |
| **Shift + F12** | PNG crop of open UI panel (Quick Menu, Help, Settings, scores, etc.) |
| **Home** | (SnapShotCam open) sync fly camera to spinCageEyes |

PNG or WebP also work — update the `src` paths in `index.html` if you change extensions.

---

## Required (core guide figures)

| File | What to capture |
|------|-----------------|
| `01-escaper-overview.jpg` | Wide establishing shot: cage in the world (island / landmarks visible). Hero image for the guide. |
| `02-first-person-hud.jpg` | First-person view with HUD visible (health, weapon, compass if shown). |
| `36-direction-indicators.jpg` | Optional crop under the compass showing direction icons (bowl, propeller, duck raft, and/or FlipChip) sliding on the band — documents distance scaling (large when close). |
| `03-quick-menu.jpg` | **Tab** Quick Menu open — weapon/item ring or grid clearly readable. Prefer **Shift+F12** crop. |
| `04-scores-overlay-f4.jpg` | **F8** scores overlay open (Escaper page or a mini-game page). Prefer **Shift+F12**. |
| `05-turn-banner-header.jpg` | Mini-game turn / win flash on top HUD — e.g. `Alice's Turn` or `Alice Wins!` on **3DGameHeaderText** (Pool / Bowling / Chess / BaffleShots). For Tetris, prefer **Players Ready** / **Wins!** / **You Lose!** / **Draw!** / **Co-op Clear!** / **Sprint Clear!** / **Time's Up!** instead of a turn line. |
| `06-game-info-balloon.jpg` | **Caps Lock** / zone balloon showing whose turn or zone hint near the health bar. |
| `07-pool-zone-board.jpg` | Standing in **PlayBilliardSwitchZone** — pool table + **pool board** (mode rules and/or per-player sunk lines like `Name Sunk: SD-1, ST-9`). |
| `08-bowling-zone.jpg` | Standing in **PlayBowlingSwitchZone** — lane + switch / scoreboard area. |
| `24-tetris-zone-board.jpg` | Standing at **SouthTetrisOPS** / **TetrisTriggerZone** — OPS board/rules or **Settings** (level, arena **1/2 · 3/4 · Full**, music), **Start** / **Settings** / **Reset**; mode can show Sprint / Ultra / Co-op / Vs Race / Attack / Ultra Duel. Host / solo spawn is this South pad; Player 2 is **NorthTetrisOPS**. |
| `25-tetris-playing.jpg` | On **Play Spot** while Playing — active piece + translucent **ghost**; FPS HUD **NEXT** / optional **HOLD** / level / score. Co-op: two pieces on 20-wide (yours bright, other dim). Vs: dual 10×20 wells + mid wall. |
| `09-baffleshots-navops.jpg` | **Nav OPS** terminal with BaffleShots UI (fleet setup with **Nav Plan** / Repulse Mines, Settings with Group Sink + Repulse Mines, **Confirm / Waiting… / Start**, or battle / game-over reveal on the target grid). |
| `10-chess-south-parthenon.jpg` | South Parthenon chess board / Chess-Stele (can reuse a chess-guide shot). |
| `30-checkers-ops.jpg` | Standing in **checkersOPSTriggerZone** — CheckersOPS panel with `Checkers - <Variant> - vs AI / 2P` board line, status (`Black Turn`, `Ready - host Start`, FlipChip side lines), host hint (`Player1 = Black/Red on Start`), and **Start** / **FlipChip** / **Settings** / **Reset** (guest: **Join**). |
| `31-checkers-board-markers.jpg` | North Parthenon board mid-turn — **blue circle** on the piece you stand on, **green spheres** on landing squares, **green circles** on capturable pieces, and ideally an **orange** pending line after RMB. |
| `11-settings-f2.jpg` | **F2** Escaper Settings panel open. Prefer **Shift+F12**. |
| `12-gamepad-reference.jpg` | Optional: in-game gamepad calibration (Settings) or remapping (**F3**) panel. |
| `27-continue-death.jpg` | Death with lives left — **You were Killed!** + reason + **Lives Remaining** + **Continue** (no GAME OVER on `3DMessageText`). Prefer **Shift+F12** crop of 3DGameOverPanel. |
| `28-game-over-restart.jpg` | Last life — **GAME OVER!** + reason + final score + **Restart**. |

---

## Strongly suggested

| File | What to capture |
|------|-----------------|
| `13-weapons-hotbar.jpg` | Number-key weapons in use (e.g. Cannon Ball **green** throw sight, BallChain **purple** throw sight, or Sniper zoom). |
| `29-c4-timer-bomb.jpg` | Optional: planted C4TimerBomb LCD fuse, or selected-weapon slot showing DetPack icon + `Nx` charge count. |
| `33-crossfields-large-ammo-crate.jpg` | Light-green **Large Ammo Crate** (DetPack) in **CrossFields** — show crate in world or cage touching it. |
| `26-ballchain-throw.jpg` | Optional: BallChain equipped — purple loft reticle + a climbable ball ladder in world. |
| `14-propeller-flight.jpg` | Cage with **Propeller** active (flight). |
| `15-duck-raft.jpg` | **Duck Raft / Bowl** mode on water. |
| `16-pool-lobby-recruiting.jpg` | Pool board recruiting: host **Shift+LMB** opened lobby; guest **RMB** / **Join** joined; player roster listed. |
| `22-pool-header-icons.jpg` | Optional: Billiards header row with all 15 ball icons — green check on sunk, red X on scratched. |
| `23-pool-cue-stand.jpg` | Optional: standing on the cue with purple sight + cue-stick power slider visible. |
| `17-bowling-scoreboard.jpg` | Bowling scoreboard with multiplayer roster / turn marker. |
| `18-no-weapon-zone.jpg` | Standing in a zone with weapons blocked (balloon or empty hands cue). |

---

## Optional extras

| File | What to capture |
|------|-----------------|
| `19-sky-eye-f10.jpg` | **F11** Sky Eye camera view. |
| `20-snapshotcam-f3.jpg` | **F12** SnapShotCam panel open. |
| `21-help-f1.jpg` | **F1** help panel. |
| `32-checkers-coin-toss.jpg` | Optional: pre-game FlipChip on CheckersOPS screen or mid-toss (melee pickup/throw sets Player1/Host color before Start). |
| `FlipChipIcon.png` | HUD sprite at `Resources/Images/FlipChipIcon.png` — moon-phase coin art for the fourth direction indicator (red/black metal in-game; blue/white moons in icon for readability). |
| `34-snowy-lava-rock.jpg` | Optional: **SnowyLavaRock** in **LavaFlow** — snowman, beige **Large Ammo Crate** behind it, or cage on the safe rock. |
| `35-lava-flow-crossing.jpg` | Optional: **LavaFlow** at the southeast mountains — floating lava rocks, mid-leap crossing, or bloop/sink moment. |
| `37-game-mode-venue-switch.jpg` | Optional: **Game Mode** panel during a live MP Play session — host can pick another Play / Explore venue; combat modes disabled. |
| `38-baffleshots-confirm-start.jpg` | Optional: 2P BaffleShots after fleet lock — host **Waiting…** then **Start**, or **Start** immediately if the guest confirmed first. |
| `39-tetris-north-ops.jpg` | Optional: **NorthTetrisOPS** / Player 2 pad after a Play Tetris or venue-switch spawn (host remains at South). |

---

When files are missing, `index.html` shows a striped placeholder via `onerror="this.classList.add('missing')"`.

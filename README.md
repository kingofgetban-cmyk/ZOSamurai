# ZO SAMURAI — Combat Suite (Protected)

One protected build of the ZO SAMURAI combat suite
(Kill Aura / Auto Block / Auto Parry / Skin Changer).
The source is never published — it is decrypted and executed in memory at runtime.

## Loader — protected source

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/kingofgetban-cmyk/ZOSamurai/refs/heads/main/ZOSamurai.lua"))()
```

Paste this line into any Roblox executor while you are in game.
The window title follows the real game name, and the UI opens with `RightShift`.

## Modules

| Tab | What it does |
|---|---|
| Combat | Kill Aura — fires the game's own `WOAH YOU HIT SOMEONE!` hit protocol; breaks enemy blocks with `KICKYWICKY` |
| Defense | Auto Block (`BLOCK THE BLOCK THE BLOCK`) and Auto Parry — perfect timing on the enemy `Hit` marker (`PRYPRYPRY`) |
| Appearance | Skin Changer — client-side weapon skins (model + texture + colours) |

## Notes

* Needs to run in an executor (VirtualInputManager / remote access).
* A weapon must be equipped (press `1` to draw) for the hit protocols to apply.
* Hits are range-limited by the server (weapon reach) — the client position is validated.
* Killer of stale sessions: after a new push, wait about 5 minutes (CDN cache) or re-open Roblox.

Developers: TG: MintraZERX | Youtube: Valexcryzer

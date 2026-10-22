# ZO SAMURAI — Combat Suite (Protected)

Two protected builds of the ZO SAMURAI combat suite
(Kill Aura / Auto Block / Auto Parry / Skin Changer).
The source is never published — it is decrypted and executed in memory at runtime.

## Loader A — protected source (works on every Roblox version)

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/kingofgetban-cmyk/ZOSamurai/refs/heads/main/ZOSamurai.lua"))()
```

## Loader B — protected Luau bytecode (strongest)

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/kingofgetban-cmyk/ZOSamurai/refs/heads/main/ZOSamuraiBytecode.lua"))()
```

Loader B ships real Luau bytecode (compiled with the official `luau-compile`,
build `0.743`), so there is no source in the file at all.
It is tied to the Roblox/Luau version it was compiled for — if Roblox updates and
the bytecode is rejected, use Loader A (the source build always works).

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
* The UI opens with `RightShift`.

Developers: TG: MintraZERX | Youtube: Valexcryzer

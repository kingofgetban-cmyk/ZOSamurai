# ZO SAMURAI — Combat Suite (Protected)

Protected build of the ZO SAMURAI combat suite (Kill Aura / Auto Block / Auto Parry / Skin Changer).
The source is encrypted — it is decrypted and executed in memory at runtime.

## Loader

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/kingofgetban-cmyk/ZOSamurai/refs/heads/main/ZOSamurai.lua"))()
```

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

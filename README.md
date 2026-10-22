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


Developers: TG: MintraZERX | Youtube: Valexcryzer

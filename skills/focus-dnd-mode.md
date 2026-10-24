---
name: focus-dnd-mode
description: Focus mode on — distractions band, ringer vibrate, media volume niche, sound panel khulwata hai.
updated: 2026-10-24
---

# Focus / DND Mode

Bol: "focus mode chalao" / "skill focus dnd chalao" / "do not disturb on karo".

Steps:
1. Ringer vibrate par — calls disturb nahi karenge.
2. Media volume niche — notifications aur videos shant.
3. System Sound panel khulta hai — yahan se Do Not Disturb toggle manually on kar sakte ho (accessibility se tap karna ho to pehle "screen numbers" bolo).

Undo: "ringer normal karo" aur "volume up" bol dena — VASU turant wapas normal mode me daal dega.

```steps
[{"tool":"set_ringer_mode","arguments":{"mode":"vibrate"}},{"tool":"set_volume","arguments":{"direction":"down"}},{"tool":"open_system_panel","arguments":{"panel":"sound"}}]
```

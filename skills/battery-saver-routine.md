---
name: battery-saver-routine
description: Battery kam ho to VASU battery check karke phone save mode me daal deta hai.
updated: 2026-10-24
---

# Battery Saver Routine

Bol: "battery saver routine chalao" ya "battery khatam hone wala hai, save karo".

Steps:
1. Battery status check — kitna charge bacha hai, charging chalu hai ya nahi.
2. Ringer vibrate par — ringtone ke bajaye vibrate se battery bachti hai.
3. Media volume ek step niche.

Tips:
- Charging pe lagte hi VASU se bolo "battery status" — normal setup wapas suggest karega.
- "settings kholo" bolo to VASU system settings kholega jahan battery saver toggle milta hai.

```steps
[{"tool":"get_battery_status","arguments":{}},{"tool":"set_ringer_mode","arguments":{"mode":"vibrate"}},{"tool":"set_volume","arguments":{"direction":"down"}}]
```

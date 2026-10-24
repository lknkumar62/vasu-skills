---
name: youtube-fast-play
description: YouTube pe turant video chalwane ka fast flow — app khol ke current screen padhta hai.
updated: 2026-10-24
---

# YouTube Fast Play

Bol: "skill youtube chalao" / "youtube fast play start karo".

Flow:
1. YouTube app turant kholta hai.
2. Current screen text padh kar bolta hai (home feed suggestions).
3. Koi specific video chalwani ho to seedha bolo: "play <topic> on youtube" — VASU play_music_or_video tool se platform=YouTube pe chala dega.

Hint: koi button dhoonde ho to pehle "screen numbers" bolo, phir "click element 3" type commands chalao.

```steps
[{"tool":"open_app","arguments":{"app_name":"youtube"}},{"tool":"read_screen","arguments":{}}]
```

# Music credits (Last Pup Standing)

Tracks: menu + boss = OpenGameArt (caliderium, centurionofwar), forest = OpenGameArt (isaiah658, **CC0**), volcano /
snow / graveyard = Kevin MacLeod (incompetech.com); all CC-BY ones = **CC-BY 4.0: attribution required** (shown on the
in-game CREDITS screen, `src/ui/credits.ts`). Swap 2026-11-07 (Ruben's pick): menu / forest / boss replaced Fluffing a
Duck / Run Amok / Hall of the Mountain King. Stings: Kenney Music Jingles, **CC0**. Sources in `Ruben HQ/Asset Library/audio/` (`LICENSES.md`).
Made by `python tools/music_convert.py`: 44.1 kHz stereo Ogg Vorbis 96 kbps (stings 112), loudness-matched (loop RMS
-19 dBFS, peak <= -1 dBFS), each track cut at a found loop point (the original ending is dropped) with an 80 ms
crossfade into the loop start baked in, or (menu, boss: the uploader's seamless loop, wrap step checked) the whole file
loops; the game plays the intro once, then loops [loopStart, loopEnd)
(`src/audio/music.ts TRACKS`).

| Game file | Use | Source | Kept | Loop (s) |
|---|---|---|---|---|
| menu.ogg | start screen + menus | Seamless Bouncy Menu Loop (caliderium) | whole 102.9 s | 0 -> 102.853 (whole file) |
| forest.ogg | W1 Forest | Sunflower Valley (isaiah658, CC0) | 0-105.9 s of 142.1 | 6.084 -> 105.924 |
| volcano.ogg | W2 Volcano | Chee Zee Cave | 0-138.9 s of 231.8 | 23.081 -> 138.943 |
| snow.ogg | W3 Snow | Krampus Workshop | 0-80.1 s of 94.7 | 2.415 -> 80.142 |
| graveyard.ogg | W4 Graveyard | Graveyard Shift | 0-132.3 s of 197.4 | 36.270 -> 132.270 |
| boss.ogg | boss fights | Techno DRIVE!!! v2 (centurionofwar) | whole 70.4 s | 0 -> 70.400 (whole file) |
| sting_lose.ogg | GAME OVER | Kenney `Pizzicato jingles/jingles_PIZZI07.ogg` | whole | - |
| sting_tier.ogg | TIER CLEAR | Kenney `Pizzicato jingles/jingles_PIZZI10.ogg` | whole | - |
| sting_win.ogg | RUN CLEAR | Kenney `Sax jingles/jingles_SAX02.ogg` | whole | - |

Attribution lines (exact):

- "Seamless Bouncy Menu Loop" by caliderium (opengameart.org/content/seamless-bouncy-menu-loop), licensed CC BY 4.0: https://creativecommons.org/licenses/by/4.0/
- Sunflower Valley by isaiah658 (CC0)
- "Chee Zee Cave" Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- "Krampus Workshop" Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- "Graveyard Shift" Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- "Techno DRIVE!!!" by centurionofwar (opengameart.org/content/techno-drive), licensed CC BY 4.0: https://creativecommons.org/licenses/by/4.0/

Courtesy: centurionofwar asks on the OpenGameArt page to be told when "Techno DRIVE!!!" is used; NOT done yet (a person
has to message them on opengameart.org/content/techno-drive).

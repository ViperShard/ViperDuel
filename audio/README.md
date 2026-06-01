# ViperDuel audio (drop-in)

The game loads real sound files from this folder if they exist, and **falls back to
built-in procedural sound** for anything missing. So you can add them one at a time.

## How to add Pixabay sounds/music
1. Go to **pixabay.com** → Music (for the soundtrack) and **Sound Effects** (for the rest).
   Everything there is free under the Pixabay Content License (no attribution required).
2. Download the clips you like (you'll need to be signed in to download).
3. **Rename** each to exactly the names below and put them in this `audio/` folder.
4. `git add audio` , commit, and `git push` — GitHub Pages will serve them and the game
   uses them automatically (procedural fallback disappears).

## Expected filenames (MP3)
| File | Used for | Suggested Pixabay search |
|------|----------|--------------------------|
| `music.mp3`     | looping background music | "epic battle music", "cinematic war" |
| `explosion.mp3` | deaths / shell & missile blasts | "explosion" |
| `cannon.mp3`    | tank main gun | "tank cannon", "artillery shot" |
| `rifle.mp3`     | infantry rifle | "rifle shot", "gunshot" |
| `mg.mp3`        | tank machine gun | "machine gun" |
| `gun.mp3`       | aircraft guns | "machine gun burst" |
| `hit.mp3`       | taking damage | "bullet impact metal" |
| `jump.mp3`      | infantry jump | "jump grunt" / "cloth" |
| `pickup.mp3`    | power-up pickup | "power up", "pickup" |
| `missile.mp3`   | missile launch | "missile launch", "rocket" |

Keep SFX short (≈0.3–1.5s) and the music a seamless loop. MP3 (or .ogg if you also
rename the references) keeps the download small.

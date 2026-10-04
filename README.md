# Ace Combat 3 Remix: Development build

This is a development build of the PC port of **Ace Combat 3: Electrosphere**.
The project is still a work in progress. Please report any issues you come
across on [GitHub Issues](https://github.com/i5han/ac3-remix/issues).

---

## Getting started

1. **Download** the release zip from
   [github.com/i5han/ac3-remix/releases](https://github.com/i5han/ac3-remix/releases)
   and extract it.

2. **Add the disc.** Copy the *Ace Combat 3: Electrosphere* (SLUS-00972)
   `.bin` and `.cue` files into the root folder, next to `ac3r.exe`.
   The image should match the Redump MD5:

   ```
   9709b211d1e241147bcfe14e95547c5a
   ```

3. **Run** `ac3r.exe` by double-clicking it.

   > **Note:** The first time, Windows may show *"Windows protected your PC"*.
   > Click **More info**, then **Run anyway**. This happens because the
   > program is not signed; it does not happen again.

4. **Pick a look.** To change how the game looks, close the game and open
   `settings.exe`:

   | Mode         | What you get                                          |
   |--------------|-------------------------------------------------------|
   | **Original** | The PlayStation's original picture (the default)      |
   | **Clean**    | The same graphics style, rendered clean and sharp     |
   | **Remaster** | Remastered quality (needs a strong graphics card)     |

   Press **Apply**, close it, and start `ac3r.exe` again.

   You can also press **`~`** while playing to switch to the next mode
   without leaving the game.

---

## Controls

### Controller

Any XInput controller is supported (Xbox controllers and most modern PC pads).

| Button     | Action                            |
|------------|-----------------------------------|
| Left stick | Fly                               |
| D-pad      | Look around                       |
| A          | Fire                              |
| B          | Missile                           |
| X          | Radar                             |
| Y          | Switch target                     |
| RB / LB    | Accelerate / brake                |
| LT / RT    | Yaw left / yaw right              |
| Start      | Start / pause                     |
| Back       | Switch camera; hold for autopilot |

### Keyboard

| Key                 | Action                            |
|---------------------|-----------------------------------|
| Arrow keys          | Left stick (fly)                  |
| Numpad 8 / 4 / 2 / 6 | Look around                      |
| Ctrl                | Fire                              |
| Space               | Missile                           |
| R                   | Radar                             |
| Tab                 | Switch target                     |
| W / S               | Accelerate / brake                |
| A / D               | Yaw left / yaw right              |
| Enter               | Start                             |
| Shift               | Switch camera; hold for autopilot |
| Esc                 | Pause                             |
| ~                   | Switch graphics mode              |
| F11                 | Toggle full screen / window       |
| Alt+F4              | Quit                              |

---

## Saving

The game saves to its memory card just as on the PlayStation: from the menu
between missions. The memory card is the file `save.bin` in your
`Documents\AC3R` folder.

Any existing memory card with an AC3 save file should work as well
*(untested)*.

---

## Your settings

Your settings live in the same place, `Documents\AC3R`.
Changing these files directly is not recommended; please use `settings.exe`.

---

## If something goes wrong

Send these files from the game folder:

| File               | What it is                                  |
|--------------------|---------------------------------------------|
| `ac3r.log`         | What the game did, written every time it runs |
| `config\BUILD.txt` | Which build this is                         |

…and say what you were doing when it happened.

---

## Follow the project

Progress updates, videos and behind-the-scenes looks at the work:

- **X:** [@Ishanv9hj](https://x.com/Ishanv9hj)
- **YouTube:** [@ishanantony5301](https://www.youtube.com/@ishanantony5301)
- **Reddit:** [u/Sad_Egg_2313](https://www.reddit.com/user/Sad_Egg_2313/)
- **Patreon:** [i5han](https://www.patreon.com/cw/i5han)

---

## Support the project

If you're enjoying playing the game and would like to help the project keep
moving, you can support its development on
[Patreon](https://www.patreon.com/cw/i5han). Every bit of
support is hugely appreciated, and so is simply playing, sharing it with
friends and reporting what you find. Thank you!

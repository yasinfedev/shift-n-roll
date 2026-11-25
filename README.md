# Shift’n Roll

Shift’n Roll is a desktop browser arcade game. Move a rocket launcher across Earth’s surface and intercept incoming targets. Engine power and wind oscillate continuously, so launch timing matters as much as alignment.

## Play locally

Open `index.html` in a desktop browser and select **Start game**. The game runs offline and requires no installation, build step, or external assets.

## Controls

| Input | Action |
| --- | --- |
| Left and Right arrow keys | Move the launchpad |
| Shift | Launch a rocket |
| Esc | Pause or resume |
| Sound button | Turn sound effects on or off |

Engine power at launch determines the rocket’s initial speed and maximum height. Wind at launch determines how far it drifts left or right. You can launch one rocket at a time.

Earth starts with three lives. If a target reaches the surface, you lose a life and retry that level. Clear all seven levels to win.

| Level | Target | Hits required |
| --- | --- | --- |
| 1 | Space Debris | 1 |
| 2 | Satellite | 1 |
| 3 | UFO | 1 |
| 4 | Mothership | 2 |
| 5 | Meteor | 1 |
| 6 | Moon | 2 |
| 7 | Planet | 3 |

## Sound

The game generates its sound effects in the browser using the Web Audio API. Sound starts after a user interaction. Use the Sound button to mute it. Your preference is remembered when browser storage is available.

## Files

- `index.html` contains the game, styles, Canvas artwork, and sound synthesis.
- `README.md` contains the controls and setup instructions.

## GitHub

Extract the archive and upload its contents to a repository. The archive already places `index.html` at the repository root. In **Settings → Pages**, select your default branch and **/ (root)** as the publishing source.

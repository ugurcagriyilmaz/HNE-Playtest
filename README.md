# High Noon Express — test builds

This page only holds **test builds** of the game. The game is in development; if you see a bug, let us know.

## How to play (Windows)

1. **Open Steam** and sign in with your own account.
2. **Download:** [latest test build (zip)](https://github.com/ugurcagriyilmaz/HNE-Playtest/releases/latest/download/HighNoonExpress.zip)
3. Right-click the zip → **Extract All** → extract to a folder.
4. Double-click **`HighNoonExpress.exe`** in that folder.
   - If Windows says "Windows protected your PC": **More info** → **Run anyway**.
   - If the firewall asks: **Allow**.
5. When the game opens you get the main menu:
   - **The person hosting:** presses **Host a game**.
   - **Everyone joining:** clicks the host's name in the **Open games** list (if it isn't there, **Refresh**).
     Or the host picks **Esc → Invite a friend** in game and you accept the invite from Steam (with the game open).

Steam shows the game as **"Spacewar"**; that's normal, we use Steam's test app.

## In the game

- **Goal (extraction):** loot the town, then get out through one of the two bridges (south-west and north-east). The
  green ground in front of a bridge is the exit: touch it **on foot or riding a train** and you extract with your bag,
  the large item in your hands and your own train's cargo. Then the **Settlement** opens: sell, buy a gun, pick your
  loadout, go back in from **Expedition → this server**. Anything not extracted is lost when the host ends the game.
- **Your train:** every player has one and starts in its cab. Yours has **white smoke**, the others' black. If your
  train reaches a green zone without you, it extracts by itself and keeps its cargo for you until you get out on foot.
- **Drive:** **F** at the locomotive's console (F again to get off). **W / S** move the lever (Reverse · Stop · 1 · 2),
  **A / D** turn the wheel (it stays where you leave it), **Space** brakes. Anyone on a locomotive can drive it.
- **Move:** W A S D, mouse to look, **Space** jump, **Shift** sprint, **Ctrl** crouch (while sprinting: roll),
  **Q / E** lean, **Alt** free look. Fire left click, aim right click, **R** reload, **T** check ammo, **1 2 3** weapons.
- **Loot:** **F** opens crates. **B** (hold) is your bag; hold **X** on an item to drop it.
- **Large items** (gold sack, painting…): **F** picks one up (no shooting while carrying), **G** sets it down, into the
  nearest free cargo slot of a wagon (4 per wagon) or on the ground. Anyone can take them from any train.
- **Settlement:** only outside a raid (after you extract, or from the main menu). It cannot be opened while you are in
  the match.
- **Dying:** your bag stays where you fell, your long gun is lost; after 5 s you are back in your own locomotive with the
  revolver. No train of your own: you are out, back to the Settlement.
- **Esc:** menu: Respawn, Call the train again, Unstuck, Settings, Invite a friend, Disconnect, Quit. The game does not
  pause.
- **V** (hold) voice chat, nearby players only. **Enter** chat. **Tab** scoreboard. **M** map. **Middle mouse** ping.

## When a new build comes out

Download again from the same link and extract to a new folder. Everyone must play the **same build** (a different
build shows as `[version …]` in the lobby list).

## If something breaks

If you cannot connect, press **Open log folder** and send `Player.log`.

Send us this file (it is rewritten every launch, so copy it right away):
`%USERPROFILE%\AppData\LocalLow\Cagri Yilmaz\High Noon Express\Player.log`

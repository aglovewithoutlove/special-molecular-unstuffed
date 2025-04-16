## Resources for RuneLite

### How to add custom object markers to RuneLite
1. Close RuneLite
2. Open File Explorer, navigate to `C:\Users\YOUR_USERNAME\.runelite`
3. Copy the `profiles2` folder, paste it in another location (backup)
4. Open `profiles2` in the `.runelite` folder, edit the `.properties` file that's named after your RuneLite profile (it may start with `default` or `settings`)
5. Search for `Spore` or `Exhumed`, delete the lines (it should start with `objectindicators.region_`), ignore this step if not found
6. If you want to change the color, replace all instances of `6300FF00` with the hex color that you want (you can use the color picker in the Object Markers config)
7. If you want to change the render style, replace all instances of `tile` with the style that you want (e.g. `hull`, `outline`, `clickbox`)
8. Scroll to the bottom of the `.properties` file, paste the markers onto a new line, click Save

### Phosani's Nightmare Spores
The color is green with ~60% opacity (`6300FF00`) and the render style is `tile`.

**To show the 3x3 spore AoE**, you will need to edit the `Border width` in the Object Markers config. The `Border width` will dynamically scale depending on your setup, including camera zoom, so you will need to find the number that works best for you.
1. Mark any 1x1 object in the game and set the style to `Tile`
2. Create ground markers surrounding the object (simulating the 3x3 spore AoE)
3. Increase the `Border width` until it fills in the tiles
> [!NOTE]
> Changing the `Border width` will affect all marked objects, so you will either need to manually change it every time you want to go to PNM or create a duplicate profile specifically for PNM.

### Theatre of Blood Exhumed (Xarpus)
The color is green (`FF00FF00`) and the render style is `tile`.

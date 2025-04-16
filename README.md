## Resources for RuneLite

### How to add custom object markers to RuneLite


### Phosani's Nightmare Spores
1. Close your RuneLite client
2. Open File Explorer, navigate to `C:\Users\YOUR_USERNAME\.runelite`
3. Copy the `profiles2` folder and paste it in another location (backup)
4. Open the `profiles2` folder and edit the `.properties` file that's named after your RuneLite profile (it may start with `default`)
5. Search for `Spore`
  - if found, the line should start with `objectindicators.region_15515=`, delete that and the markers following it in `[]`
6. Scroll to the bottom, then paste the markers from `pnm-spores.txt` onto a new line, click Save

You will need to edit the `Border width` in the Object Markers plugin config to effectively show the 3x3 space around the spore (if you don't care about this, then keep it at default)
- The `Border width` will dynamically scale with resolution, client size, and camera zoom, so you will need to trial and error this to find what number works best for you
- To test this, mark any 1x1 object in the game and set the style to `tile`.
- Then, create tile markers surrounding the object (we're creating the 3x3 radius of the spore)
- Increase the `Border width` until it fills in the 3x3 tiles
Since changing the border width will affect the other marked objects you have in the game, you will either need to manually change it every time you want to go to PNM or create a duplicate profile specifically for PNM, whichever you fancy

The current color is green with ~60% opacity. If you want to change it, use the color picker in the Object Markers plugin config. Replace all instances of `6300FF00` with the hex color that you want.

The current render style is a tile. If you want to change it, replace all instances of `tile` with the style that you want (e.g. `hull`, `outline`, `clickbox`)

## Resources for RuneLite

### How to add custom object markers to RuneLite


### Phosani's Nightmare Spores
1. Close your RuneLite client
2. Open File Explorer -> C:\ -> Users -> <your username> -> .runelite
3. Copy the `profiles2` folder and paste it in another location (backup)
4. Open the `profiles2` folder and edit the `.properties` file that's named after your RuneLite profile (it may start with `default`)
5. Search for "Spore"
- if found, the line should start with `objectindicators.region_15515=`, delete that and the markers following it in `[]`
6. Scroll to the bottom, then paste the markers from `pnm-spores.txt` onto a new line, click Save

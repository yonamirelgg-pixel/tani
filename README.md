# Tanis Opti (Fabric 1.21 / 1.21.1)

In-game texture browser. Press **Right Shift** (title screen, pack screen, or in-game) or use the
"Tanis Opti" button on the title screen.

- Left: categories (items, blocks, entities, overlays) with pack counts.
- Middle: every pack's version of the selected texture, plus Vanilla. Click = use, click again = turn off.
- Right: the real item (big) and a live mob when you are in a world.
- Scans your `resourcepacks` folder (zips and folders). Hit "Rescan" after adding packs.
- Built in: pulsing green frame totem (new + old), obsidian packs (tints, 3 chunky cartoon purple, clean), 14 totem sizes (0.3x-3x), PvP low fire, clear pumpkin/vignette, short swords.
- Optional: put `background.png` in `.minecraft/config/tanisopti/` for a custom menu background.

## Get the .jar
Without installing anything: create a GitHub repo, upload this folder, open the Actions tab,
run "Build Tanis Opti", download the `tanis-opti-jar` artifact.
Or locally (Java 21 + Gradle 8.10): `gradle build` -> `build/libs/tanis-opti-1.0.0.jar`.
Needs Fabric Loader 0.16+ and Fabric API.

## Pack Mixer (use other creators' textures)
Put any packs you downloaded in your resourcepacks folder. In the menu, pick a category, then
**Shift+click** the version you like (yellow border). Do this for as many categories as you want, then
press **Build Mix**: a new pack "Tanis Opti Mix.zip" appears in your resourcepacks folder with
exactly those textures (animations included). Enable it from the menu or the vanilla pack screen.
Model-only packs (e.g. totem sizes) can't be mixed; enable those directly.

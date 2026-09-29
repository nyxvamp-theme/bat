# nyxvamp (bat)

theme inspired by transfem emo aesthetics - special for raccoon girls 🦝

a minimalist theme collection, inspired by a blend of gothic and emo aesthetics with transfem symbolism. it combines deep purples and soft pinks with neutral tones to create strong contrasts and a comfortable code viewing environment that reflects individuality.

## variations

1. **veil**: versatile theme for both day and night, featuring bright accents on a dark background.

2. **obsidian**: very dark theme for focused nighttime coding sessions with high contrast.

3. **radiance**: light theme optimized for daylight use, ensuring excellent readability.

4. **jhujuba**: pink-tinted mid-dark theme, sweeter than veil.

## usage

1. download theme files from the `themes/` directory:
   - `nyxvamp-veil.tmTheme`
   - `nyxvamp-obsidian.tmTheme`
   - `nyxvamp-radiance.tmTheme`
   - `nyxvamp-jhujuba.tmTheme`

2. place themes into the bat themes directory:
   - unix/linux: `~/.config/bat/themes/`
   - macos: `~/.config/bat/themes/`
   - windows: `%APPDATA%\bat\themes\`

3. rebuild bat cache:
   ```bash
   bat cache --build
   ```

4. use the theme:
   ```bash
   bat --theme="nyxvamp-veil" file.ext
   # or
   bat --theme="nyxvamp-obsidian" file.ext
   # or
   bat --theme="nyxvamp-radiance" file.ext
   ```

5. set as default (optional):
   ```bash
   echo '--theme="nyxvamp-veil"' >> ~/.config/bat/config
   ```

## contribution

if you have suggestions or improvements, feel free to contribute or reach out.
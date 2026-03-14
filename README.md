# xperia-theme
Xperia theme for Emby and Jellyfin

<img width="1917" height="948" alt="image" src="https://github.com/djmanri3/xperia-theme/blob/dev/screenshots/Player_album_art_color.png?raw=true" />
<img width="1917" height="948" alt="image" src="https://github.com/djmanri3/xperia-theme/blob/main/screenshots/Player.png?raw=true" />

## How Install
Access to **Dashboard**, open **general** settings and add on **Custom CSS code**:
- Jellyfin
  ```
  @import url("https://cdn.jsdelivr.net/gh/djmanri3/xperia-theme@master/Xperia_theme.css");
  ```
- Emby
  ```
  @import url("https://cdn.jsdelivr.net/gh/djmanri3/xperia-theme@master/Xperia_theme.css");
  ```

  ## Tricks
  ### Change primary color
  You can change primary color, change hex color on value **theme-accent-text-color-darkbg** and **theme-accent-text-color-darkbg-alt**
  ```
  @import url("https://cdn.jsdelivr.net/gh/djmanri3/xperia-theme@master/Xperia_theme.css");

  :root {
    /* Color of playing bar */
    /* Color of primary color */
    --music-progress-bar-background: var(--theme-accent-text-color-darkbg) !important;
    --music-progress-bar: none !important; 

    /* colors */
    --theme-accent-text-color-darkbg: #05edfd !important;
    --theme-accent-text-color-darkbg-alt: #05edfd !important;
  }
  ```

  ### Primary color or color of album on palying bar
  You can decide color of playing bar, primary color or album color

  Primary color:

  <img width="1917" height="948" alt="image" src="https://github.com/djmanri3/xperia-theme/blob/main/screenshots/Player.png?raw=true" />
  
  ```
  @import url("https://cdn.jsdelivr.net/gh/djmanri3/xperia-theme@master/Xperia_theme.css");

  :root {
    /* Color of playing bar */
    /* Color of primary color */
    --music-progress-bar-background: var(--theme-accent-text-color-darkbg) !important;
    --music-progress-bar: none !important; 

    /* colors */
    --theme-accent-text-color-darkbg: #05edfd !important;
    --theme-accent-text-color-darkbg-alt: #05edfd !important;
  }
  ```

  Album art color:

  <img width="1917" height="948" alt="image" src="https://github.com/djmanri3/xperia-theme/blob/dev/screenshots/Player_album_art_color.png?raw=true" />
  
  ```
  @import url("https://cdn.jsdelivr.net/gh/djmanri3/xperia-theme@master/Xperia_theme.css");

  :root {
    /* Color of playing bar */
    /* Color of cover */
    --music-progress-bar-background: rgb(119 119 119 / 44%) !important;
    --music-progress-bar: blur(50px) brightness(0.95) saturate(5) contrast(2) !important;
  }
  ```

  # Screenshots:
  <img width="1917" height="948" alt="image" src="https://github.com/djmanri3/xperia-theme/blob/main/screenshots/Player.png?raw=true" />
  <img width="1917" height="948" alt="image" src="https://github.com/djmanri3/xperia-theme/blob/dev/screenshots/Player_album_art_color.png?raw=true" />
  <img width="1917" height="948" alt="image" src="https://github.com/djmanri3/xperia-theme/blob/main/screenshots/HomeScreen.png?raw=true" />


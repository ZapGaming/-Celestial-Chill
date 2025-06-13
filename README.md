# Celestial Chill

![Theme Banner]([https://i.imgur.com/your-banner-image-link.png](https://warrayquipsome.github.io/Chillax/Wallpapers/chillax-default.png)) <!-- Optional: Create and link to a cool banner image! -->

A vibrant, feature-rich Discord theme that merges the aesthetic of **Chillax** with powerful snippets from the **Flashcord community**. It provides a calm, customizable, and visually pleasing experience.

**Created by:** Wq (Chillax), Ascellayn (Flashcord), Zap Gaming (Flashcord Community developer)

---

### ✨ Features

*   **Animated Background:** Comes pre-loaded with a beautiful, spacey GIF background.
*   **Highly Customizable:** Easily change the background, accent colors, fonts, and blur levels right from the CSS file.
*   **Modern Aesthetics:** Based on the popular Chillax theme, known for its clean and calming style.
*   **Advanced Spotify Player:** A custom-styled, blurred Spotify control panel that looks incredible.
*   **Blurry Settings Modal:** A sleek, translucent settings menu that lets your background shine through.
*   **Enhanced Channel Icons:** Integrates server icons into the channel list for a unique, cohesive look.
*   **Community Snippets:** Includes hand-picked modifications from the community for an even better user experience.

---

### 📥 Installation

1.  Download the `Celestial-Chill.theme.css` file from this repository.
2.  Open your Discord client's settings.
3.  Go to the **Themes** tab (provided by Vencord, BetterDiscord, etc.).
4.  Click the **"Open Themes Folder"** button.
5.  Drag the downloaded `Celestial-Chill.theme.css` file into the folder that opens.
6.  Return to Discord, find "Celestial Chill" in your themes list, and enable it.

---

### 🎨 Customization

Customizing this theme is easy! Open the `Celestial-Chill.theme.css` file in any text editor and find the `:root` section at the top.

Here are some key variables you can change:

```css
:root {
    /* Change the background URL to any image or GIF you want */
    --wallpaper: url("https://media1.giphy.com/media/your-gif-link-here.gif");

    /* Change the main accent color (used for mentions, buttons, etc.) */
    --accentcolor: 251, 84, 84;     /* RGB value */
    --accentcolorV2: #fb5454;       /* HEX value */
    
    /* Adjust the font */
    --font-name: 'Poppins', sans-serif;
    
    /* Customize the blur and dimness for the settings menu */
    --blrsm-blur-by: 5px;
    --blrsm-dimmness: 25;
}
```

After making your changes, save the file and Discord should update the theme automatically. If not, toggle the theme off and on again.

---

### 📜 Credits

This theme is a combination of incredible work from multiple creators.
*   **Wq**: Creator of the original [Chillax](https://github.com/warrayquipsome/Chillax) theme.
*   **Ascellayn**: Developer of the original [Flashcord/Ceres](https://sirio-network.com/) theme.
*   **Zap Gaming**: Flashcord Community Developer and contributor of custom snippets.
*   **nspc911**: Creator of the [BlurrySettingsModal](https://github.com/nspc911/themes/tree/main/vencord/BlurrySettingsModal.theme.css) snippet.
*   ...and all other contributors whose code was part of the original themes.

---

### 📄 License

This theme is licensed under the **GNU Lesser General Public License v3.0**. This means it is free to use, modify, and distribute, provided that any derivative works are also licensed under the LGPL. You can find the full license text in the [`LICENSE`](./LICENSE) file.

# 🎮 Virtual Boy - Rainbow Edition

A heavily modified high-performance edition of the standard Virtual Boy theme for BetterDiscord that swaps the static red palette for an ultra-smooth, hardware-accelerated, variable speed RGB rainbow effect reminiscent of gaming mice without discoloring any of your profile pictures, avatars or server icons! Originally made by Riddim_Glitch.

---

## ✨ Features

* **🌈 Gaming Mouse Glow**: Smoothly animates text, usernames, and layout elements through the full RGB spectrum.
* **⚡ Lag-Free Optimization**: Utilizes direct root HSL variable manipulation for lightning fast, hardware-accelerated transitions.
* **🛡️ Avatar Protection**: Safely bypasses intense screen-wide color overlays to ensure your profile, server, and emoji colors stay true.
* **📱 Responsive Layout**: Maintains all the same fully responsive and clean AMOLED layout of the original Virtual Boy base theme.

---

## 🚀 Quick Installation

### For BetterDiscord users:

1. ⚙️ Open Discord, and navigate to **User Settings** -> **BetterDiscord** -> **Themes**.
2. 📂 Click **Open Themes Folder** in the top left.
3. 📄 Drag the Rainbow-Nintendo-console File into the folder 
4. 🔄 Turn the toggle switch on in Discord.

---

## 🛠️ Customization

Want faster or slower rainbow transitions? All you have to do is locate the block below this in the CSS file and change `30s` to something else.

```css
/* Change "30s" to whatever you desire. Faster numbers will make the rainbow cycle faster. Slower will slow it down. */
:root {
  animation: VariableRainbowEffect 30s linear infinite;
}
```

---

*⚠️ **Note**: This modified code snippet is for personal customization only on the BetterDiscord app.*

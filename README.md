README.md

# 🌸 MCSR Ranked OBS Widget

A customizable MCSR Ranked profile and stats overlay for OBS Studio.

I made this widget to let Minecraft speedrunners display their MCSR Ranked profile while streaming. It shows player information, ELO, rank, match statistics, session progress, and recent match history.

The widget comes with several themes and layout options, so you can adjust its appearance to your liking.

---

## ✨ Features

### 👤 Player Profile
- Display your MCSR Ranked username and avatar.
- Show your current ELO and rank.
- Supports all rank divisions, from Coal I to Netherite.
- Rank progress bar.
- Target ELO display.
- ELO trend chart.

### 📊 Statistics
- Wins and losses.
- Win rate.
- Personal Best (PB).
- Win streak and other available statistics.
- Choose which statistic cards you want to display.

### ⏱️ Session Tracker
- Start, pause, and end a session.
- Reset session statistics.
- Keep track of your session performance separately from your lifetime stats.

### 📜 Match History
- View your recent matches.
- Enable visual flashes and sound notifications when a new match is detected.

### 🎨 Customization
- 7 available color themes.
- Glass, Solid, and Transparent backgrounds.
- Compact and Full layouts.
- Automatic fitting.
- Adjustable fonts and columns.
- Toggle animations on or off.
- Settings are saved automatically.

### 🔧 Other Features
- Live data from the MCSR Ranked API.
- LIVE / OFFLINE connection status.
- Cached data when live data is unavailable.
- Demo mode.
- Manual refresh option.
- OBS URL generator for sharing widget configurations.

---

## 📥 Installation

### 1. Download

Go to this repository and download the latest version.

Click Code → Download ZIP, then extract the downloaded file.

### 2. Add to OBS Studio

1. Open OBS Studio.
2. Add a new Browser Source.
3. Enable Local File.
4. Browse and select `mcsr-widget.html`.
5. Set the width and height.

Recommended dimensions:

| Setting | Value |
| --- | --- |
| Width | 460 px |
| Height | 800 px |

### 3. Set Up Your Profile

1. Right-click the Browser Source.
2. Select Interact.
3. Open the settings using the gear icon.
4. Enter your MCSR Ranked username.
5. Click Apply & Refresh.

That's it! Your profile should now appear in OBS.

> Tip: Don't resize the widget by dragging its corners in OBS. This can make the text look blurry. Change the Browser Source width and height instead.

---

## 🏆 Supported Ranks

The widget supports these MCSR Ranked divisions:

- Coal I, II, III
- Iron I, II, III
- Gold I, II, III
- Emerald I, II, III
- Diamond I, II, III
- Netherite

---

## 🖥️ Compatibility

Made for OBS Studio using its built-in Browser Source.

No extra plugins or installations are needed. Just load the HTML file and you're good to go.

---

## ❓ Troubleshooting

**Widget shows OFFLINE**
- Check your internet connection.
- Make sure your username is correct.
- The MCSR Ranked API might be temporarily unavailable.

**Stats are not updating**
- Try refreshing the widget.
- Check if the API is working.
- The widget may be showing cached data.

**Widget looks blurry**
- Check the Browser Source width and height.
- Avoid manually stretching the source in OBS.

**Settings don't seem to work**
- Open the settings again.
- Apply your changes and refresh the widget.

---

## 📌 Disclaimer

This is an independent community project made by Nawumeee. It is not affiliated with, endorsed by, or officially connected to MCSR Ranked or Minecraft.

Data accuracy and availability depend on the external MCSR Ranked API.

Minecraft is a trademark of Mojang Studios.

---

## 📄 License

This project is free to use and share under the Nawumeee Community License v1.0.

You're welcome to:
- Use the widget for personal purposes.
- Share the widget with other people.
- Share the original repository with your friends or community.

If you share this project, I'd really appreciate it if you included a link to the original GitHub repository so others can find the latest version.

Please do not:
- Sell this project or any part of it.
- Redistribute it as a paid product.
- Include it in a commercial product or service.

For the complete terms, please read the `LICENSE` file.

---

## 💗 Credits

Made by Nawumeee.

I made this project for the Minecraft Speedrunning community. Hopefully, it comes in handy for your streams!

If you enjoy using it, feel free to share the repository with other runners.

Good luck with your runs! 🌸
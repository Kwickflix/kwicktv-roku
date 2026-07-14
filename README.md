<div align="center">

<img src="assets/banner.png" width="720" alt="Kwick Player for Roku">

# Kwick Player for Roku

**Live TV, movies & series on your Roku — installed through Roku's Developer Mode.**

[![Version](https://img.shields.io/github/v/release/Kwickflix/kwicktv-roku?style=for-the-badge&color=2086FF&label=latest)](https://github.com/Kwickflix/kwicktv-roku/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Kwickflix/kwicktv-roku/total?style=for-the-badge&color=2086FF)](https://github.com/Kwickflix/kwicktv-roku/releases)
[![Roku](https://img.shields.io/badge/platform-Roku-662D91?style=for-the-badge&logo=roku&logoColor=white)](#)

[![Download the ZIP](https://img.shields.io/badge/Download-KwickPlayer_ZIP-2086FF?style=for-the-badge&logo=roku&logoColor=white)](https://github.com/Kwickflix/kwicktv-roku/releases/latest)

</div>

---

## Features

### 📺 Live TV & a real TV Guide
Browse by category with channel logos, or open the **Plex-style timeline guide** — genre tabs (News, Sports, Movies…), a channel logo column, half-hour timeline, and programme blocks sized by runtime with a red **NOW** line. OK tunes instantly.

### 🎬 Movies & Series
**Movies | Series** tabs with a category strip and a six-across poster grid. Movie pages show poster, year/genre/runtime/rating, plot, and cast; series pages list seasons and episodes. **Resume + Play from Beginning** remembers where you stopped, and finishing a title clears its spot.

### ▶️ A full player
Fullscreen video with a channel title + **LIVE** badge, an Android-style control bar (play/pause, mute, refresh, favorite), and live **auto-retry** on hiccups. VOD adds a **seek bar with a grabbable scrubber**, continuous fast-forward / rewind (1×→2×→3×), and a **captions picker**. The remote's dedicated FF/RW/Replay and Left/Right seek all work.

### 🔍 Search
One search across your whole catalog, results grouped into **Channels · Movies · Series** — pick a channel to watch or a title to open its page.

### ⭐ Home & favorites
**Recently Watched Channels**, **Favorite Channels**, and **Favorite Movies & Series** rows — favorite anything and it shows up here.

### ⚙️ Deep settings
Switch/add/remove **providers**, **Hide & Reorder** live/movie/series categories (Move to Top / Hide), **channel sort** (Default / A–Z / Z–A), **hide channels** (Options button on any channel), start-muted, home-row toggles, and clear history / resume points.

### 🔑 Sign in your way
Featured **KwickTV** sign-in (just username & password), or add any **Xtream Codes** or **M3U** provider. Multiple sources supported.

> **Roku notes:** live TV uses the HLS version of your streams (Roku can't play raw `.ts`), there's no DVR (Roku apps can't record to disk), and external links show an address to type since Roku has no browser. Everything else matches the Android app.

---

## Install — Developer Mode

Roku doesn't allow private channel distribution for this app, so installation
is done through Roku's built-in **Developer Mode**. The **KwickPlayer ZIP** is
attached to the [latest release](https://github.com/Kwickflix/kwicktv-roku/releases/latest).

### Step 1 — Enable Developer Mode

Make sure your Roku is powered on and connected to the **same local Wi-Fi
network** as your computer or phone.

Using your Roku remote, press this button sequence:

> **Home** ×3 · **Up** ×2 · **Right** · **Left** · **Right** · **Left** · **Right**

The hidden **Developer Settings** screen appears.

1. Select **Enable installer and restart**.
2. Read and accept the **Developer Tools License Agreement**.
3. Create and confirm a password for your Roku.
4. Your Roku restarts.

### Step 2 — Find your Roku IP address

If you don't already know it:

1. Press **Home** on your Roku remote.
2. Go to **Settings → Network → About**.
3. Your Roku's **IP Address** is shown on screen.

### Step 3 — Install KwickPlayer

1. Open a web browser on your computer/phone.
2. Enter your Roku's **IP address** in the address bar.
3. Log in with:
   - **Username:** `rokudev`
   - **Password:** the password you created when enabling Developer Mode.
4. On the **Development Application Installer** page, click **Upload**.
5. Select the **KwickPlayer ZIP** from the latest release.
6. Click **Install**.

The app installs and launches on your Roku automatically.

---

## ⚠️ Important

- Your computer/phone and Roku **must be on the same local network**.
- **Developer Mode is per Roku device.** If you have several Rokus, repeat this
  on **each** one you want KwickPlayer on.
- Roku allows **one sideloaded app** per device. Installing another ZIP through
  Developer Mode **replaces** the current sideloaded app **on that Roku only** —
  it does not affect your other Roku devices.

---

<div align="center">
<sub>Not affiliated with any content provider. You supply your own playlist or subscription.</sub>
</div>

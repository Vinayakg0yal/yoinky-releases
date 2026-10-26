# Yoinky

A fast, modern download manager: multi-connection downloads, videos from YouTube and
1,000+ sites in every quality (up to 4K and MP3), torrents, full-size images, an AI upscaler,
background removal and a download queue with a schedule. Grab a whole playlist or every link on a
page at once, record live streams, and use it in 9 languages. For Mac and Windows.

## Download

**[⬇ Download Yoinky 0.7.1 for Mac (Apple Silicon)](https://github.com/Vinayakg0yal/yoinky-releases/raw/main/downloads/Yoinky_0.7.1_aarch64.dmg)**
For Macs with an M1, M2, M3, M4 (or newer) chip. To check: Apple menu → **About This Mac** → "Chip".

**[⬇ Download Yoinky 0.7.1 for Windows](https://github.com/Vinayakg0yal/yoinky-releases/raw/main/downloads/Yoinky_0.7.1_x64-setup.exe)**
For Windows 10 and 11 (64-bit).

Yoinky is free and safe, but it isn't signed by Apple or Microsoft yet (that costs money every
year). Your computer will warn you the first time. The steps below take about a minute, once.

## Install on Mac

1. Open the downloaded **Yoinky_…_aarch64.dmg**.
2. Drag **Yoinky** onto the **Applications** folder in that window.
3. Open **Applications** and double-click **Yoinky**. macOS will say it can't verify Yoinky.
   Click **Done** (or **OK**). Don't click "Move to Trash".
4. Open **System Settings** → **Privacy & Security**. Scroll down to the **Security** section:
   you'll see *"Yoinky" was blocked to protect your Mac*. Click **Open Anyway**.
5. Enter your Mac password (or use Touch ID), then click **Open Anyway** again.

Yoinky opens, and from now on it opens normally, including after updates.

On older macOS (Sonoma 14 and earlier) there's a shortcut instead of steps 3–5: right-click
Yoinky in Applications → **Open** → **Open**.

**If macOS says "Yoinky is damaged and can't be opened":** it isn't damaged; this is the same
warning, worded badly. Open **Terminal** (Applications → Utilities), paste this line and press Return:

```
xattr -dr com.apple.quarantine /Applications/Yoinky.app
```

Then open Yoinky again.

**First run:** Yoinky may ask to send notifications (for finished downloads); allow it if you'd like.
It lives in the menu bar (top right) as well as the Dock.

## Install on Windows

1. Your browser may warn that the file *"isn't commonly downloaded"*.
   - **Edge:** click **⋯** next to the download → **Keep** → **Show more** → **Keep anyway**.
   - **Chrome:** click **Keep** (or open the downloads list and choose **Keep**).
2. Open **Yoinky_…_x64-setup.exe**. Windows may show a blue **"Windows protected your PC"** screen:
   click **More info** → **Run anyway**.
3. Follow the installer. No administrator password is needed, and it installs just for you.
4. Yoinky starts. Its icon also appears in the taskbar's tray (near the clock; it may be under
   the **^** arrow).

If your antivirus asks about Yoinky, choose **Allow**. Antivirus tools are sometimes cautious
with new apps that aren't signed yet.

## Browser extension (optional, recommended)

The Yoinky extension sends your browser's downloads straight to Yoinky and adds a download button
to videos, and shows your downloads in its menu. It works in Chrome, Edge, Brave, Arc, Opera and
Vivaldi, in your browser's language.

**Easiest:** Yoinky sets it up with you the first time you open the app (or: Settings →
Browser extension → Set up). Its **Download the extension** button saves a "Yoinky Extension"
folder to your Downloads folder.

**Or by hand:** [⬇ Download the extension (zip)](https://github.com/Vinayakg0yal/yoinky-releases/raw/main/downloads/Yoinky-Extension.zip),
then:

1. Unzip it, so you have a **Yoinky Extension** folder. Move it to your **Downloads** folder
   (keep it there: the extension runs from it, and Yoinky keeps it up to date).
2. In your browser, open `chrome://extensions` (Edge: `edge://extensions`, Brave: `brave://extensions`).
3. Turn on **Developer mode** (top right; in Edge it's in the menu on the left).
4. Drag the **Yoinky Extension** folder onto that page, or click **Load unpacked** and choose it.

## What's new

**0.7.1:** new colours, with Light or Dark in Settings; Windows: YouTube downloads and Remove background work again; Remove background starts right away, with Undo and zoom; video thumbnails at their best size; checked links open straight away; Google Images pictures full size from their website; the download button sits with YouTube's, TikTok's, X's and Instagram's own buttons; no torrent pop-ups you didn't ask for; the extension in several browsers at once.

**0.7.0:** Torrents: magnet links and .torrent files (pick which files, sharing after finishing, extra trackers or your own tracker list); Settings in tabs.

**0.6.1:** Windows: frosted glass is back and stays frosted when another window is in front; a plain background when Transparency effects are off in Windows' settings.

**0.6.0:** the biggest update yet.
- Download many links at once (paste a list, or "Download links from this page" in the extension) and whole YouTube playlists and channels.
- Select several downloads to pause, resume or remove them together; sort the list; right-click any download for more.
- Schedule: start the queue at a set time, and quit, sleep or shut down when everything's done.
- A speed limit per download; downloads wait on phone hotspots unless you say otherwise.
- "You already downloaded this", a warning when the disk is too full, and checksum checks.
- Videos: subtitles, chapters, cover art, M4A / Opus / FLAC audio, Original quality (HDR, 60 fps), and live stream recording.
- A pop-up when a download finishes, drag files out of Yoinky, and press Space for a quick preview.
- A welcome tour, and Yoinky in English, Español, Português, Français, Deutsch, हिन्दी, 日本語, 简体中文 and Русский.
- Extension 1.9.0: in the same 9 languages, your downloads (with pause, resume and open) in its menu, and per-site switches.

**0.5.4:** Clear list button, cleaner sidebar, and a big round of fixes for Mac, Windows and the browser extension.

**0.5.3:** YouTube fixed on Windows; real quality names for widescreen videos; no more page reloads after extension updates; tidier pop-ups and sidebar (extension 1.5.0).

**0.5.2:** Windows look: own window buttons, cleaner drop-downs, installer icon; the extension only mentions updates when there is one (extension 1.4.1).

**0.5.1:** Instagram posts open reliably; stories and photos through the extension button; the button never covers a site's own buttons; tidier picker (extension 1.4.0).

**0.5.0:** Instagram and X support: paste or copy a post, reel, carousel or story link and pick the whole post or single photos and videos (extension 1.3.0).

**0.4.5:** Click the extension's download button while Yoinky is closed and Yoinky opens by itself (extension 1.2.0).

**0.4.4:** the extension finds videos and audio on any page (embedded players and streams too); Add to queue starts when idle; copying a link again shows the pop-up; start-up screen; cleaner scroll bars.

**0.4.3:** one Yoinky at a time; centered pop-ups; a subtler, smoother video button in the extension.

**0.4.2:** fixes: Windows folders and frosted glass, copied-link pop-up timing, image tools stuck at 100%, pop-ups on small windows, Google preview images.

**0.4.1:** easier extension setup (saved to Downloads); Windows frosted glass and stability fixes.

**0.4.0:** Remove background and smart picture names on Windows; a quieter Ko-fi link.

**0.3.3:** a Ko-fi support button in the app and the extension.

**0.3.2:** a clear message for copy-protected services like Netflix and Spotify.

**0.3.1:** remove a download from the list only, or delete its file too (it goes to the Trash).

**0.3.0:** the browser extension: browser downloads go straight to Yoinky, a download button on videos, and right-click → Download with Yoinky.

**0.2.2:** a Yoinky Downloads button at the top of every view.

**0.2.1:** updates now come straight from this page.

**0.2.0:** First public version: fast multi-connection downloads with a queue, videos from YouTube and
1,000+ sites up to 4K plus MP3, full-size images with smart names, an AI upscaler, a background
remover, and automatic updates.

## Updates

Yoinky checks for new versions by itself and shows **Update now** when one is out.
Updating installs over your current version and keeps your downloads and settings.
You can also check from Settings → Updates.

## Support

Yoinky is free, with no ads and no premium tier. Support me so that I can build more apps like these:
**[☕ Tip on Ko-fi](https://ko-fi.com/vinayakg0yal)**

---

This repository only hosts the installers. Yoinky's source code is private.

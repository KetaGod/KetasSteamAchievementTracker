# KSAT — Keta’s Steam Achievement Tracker

KSAT helps you **track, tag, and compare** Steam achievements with a clean, cozy UI.  
This guide is for users who downloaded the **pre-built Windows app (.exe)**.

---

## 🌟 What KSAT does

- **Pulls your Steam library** (with optional “installed only”)
- **Shows achievements per game** with rarity, secret markers, and filters
- **Lets you check off achievements manually** (for custom tracking or offline play)
- **Notes & tags per game** to plan backlog, DLC cleanup, or speedruns
- **Friend compare**: paste a SteamID64 or profile URL and see what each person is missing
- **Share card**: export a simple progress image to share with friends
- **Import/Export**: back up your KSAT data locally

> KSAT talks directly to the **Steam Web API** and stores your notes/tags **on your PC**.

---

## 🖼️ Screenshots

### Home (Library + Achievements)
![Home](docs/home.png)

### Settings
![Settings](docs/settings.png)

### Friend Compare
![Friend Compare](docs/compare.png)

---

## 🚀 Getting Started (Windows)

1. **Run** `KSAT.exe` (or install with the provided setup if you received one).
2. Click **Settings** (top-right) → **Get a key** to open Steam’s API key page.
3. **Sign in to Steam** in your browser, create or copy your **Web API Key**, and paste it in KSAT’s field. Click **Save**.
4. Back on the left, click **Sign in with Steam**.  
   After you complete sign-in, KSAT will show your **SteamID64** and start fetching your library.

> Tip: For KSAT to see your owned games, Steam profile privacy needs **Game details = Public** (you can change it back anytime).

---

## 🎮 Using KSAT

- **Browse your games** in the left sidebar. Search or toggle **Installed** to narrow down.
- **Select a game** to see its achievements. Use filters: **Unlocked**, **Locked**, **Secret**, **Manual only**.
- **Manual checkboxes** let you track progress your own way (speedruns, console play, retro ports, etc.).
- **Notes & Tags**: write notes and add comma‑separated tags (e.g., `speedrun, DLC1, cleanup`) then **Save**.
- **Friend compare**: paste a **SteamID64**, a vanity name, or a full **Steam profile URL** and hit **Compare**.
- **Share card**: click **Share Card** to export a simple PNG with your current progress.
- **Import/Export**: back up or move your KSAT data between PCs.

---

## 💡 Tips

- If a game shows **no achievements**, that title might not expose data through the public API.
- Hover tooltips in the UI often explain features (e.g., rarity, secret badges).
- **Big‑screen mode** in **Settings** enlarges UI elements for TV/couch setups.

---

## ❓ FAQ

**Do I need a Steam Web API key?**  
Yes—KSAT uses it to fetch your library and achievement data. You only need to set it **once**.

**Where does KSAT store my data?**  
On your PC (notes, tags, and manual checks). No accounts or servers.

**Can I use KSAT offline?**  
You can view your last fetched data and edit notes/tags/checks. Online access is required to refresh library/achievements.

**Does KSAT modify my Steam account or unlock achievements?**  
No. KSAT is read‑only and for **tracking** only.

---

## 🔐 Privacy

- KSAT stores notes/tags locally and only calls the **Steam Web API** to read your public data.
- No telemetry, no third‑party analytics.

---

## 🧭 Troubleshooting

- **Owned games list is empty** → In Steam privacy settings, set **Game details** to **Public**, verify your **API key**, then **Refresh**.
- **Sign-in opens a blank window** → Complete the sign-in in your **default browser**, then return to KSAT. Make sure Microsoft **WebView2 Runtime** is installed.
- **A friend doesn’t show** → Ask them for a **SteamID64** or public profile URL and try again.
- **Icons/UI look off** → Try a different theme in **Settings**, or enable **Big‑screen mode**.

If you get stuck, share a screenshot and describe what you clicked right before the issue.

---

## 🙌 Credits

- Built with [Tauri](https://tauri.app/), [React](https://react.dev/), and [Vite](https://vitejs.dev/)
- Uses the public [Steam Web API](https://developer.valvesoftware.com/wiki/Steam_Web_API)
- Icon theme: **Foresty + Cozy** 🌲

---

## 📄 License

```
MIT © 2025 Ketamine Junkies Inc.
```

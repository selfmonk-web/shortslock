# ShortsLock

ShortsLock is a minimal Chrome extension that turns YouTube Shorts into normal videos by redirecting `/shorts/...` pages to the standard `/watch?v=...` player.

The goal is simple: remove the addictive Shorts feed without blocking content or breaking YouTube.

---

## ✨ What it does

- Converts YouTube Shorts into normal Watch page videos
- Removes the infinite vertical Shorts feed
- Keeps the same video, comments, and controls
- Works on all YouTube navigation types (including SPA navigation)
- Lightweight, fast, and stable

---

## 🔒 Modes

**Permanent Lock**
- Shorts always open as normal videos
- No Shorts feed, no swipe-based autoplay

**Permanent Unlock**
- Shorts behave normally until you lock again

**Temporary Unlock (5 minutes)**
- Allows the Shorts feed for a short period
- Automatically switches back to Lock mode

---

## 🧠 Why ShortsLock?

Most “Hide Shorts” extensions rely on fragile DOM or CSS hacks that break when YouTube updates.

ShortsLock works at the URL/navigation level instead:
- No DOM manipulation
- No layout injection
- Much harder to break
- More future-proof

It changes *how* Shorts are consumed, not *whether* they exist.

---

## 🔐 Privacy & Permissions

- No analytics
- No tracking
- No remote servers
- No data collection
- All logic runs locally in your browser

Required permissions are used only to detect YouTube navigation and apply redirects.

---

## ⌨️ Keyboard Shortcut

Default:
- **Ctrl + Shift + L** (Windows / Linux)
- **Cmd + Shift + L** (macOS)

You can change this in:
`chrome://extensions/shortcuts`

---

## ☕ Support

If you like ShortsLock and want to support development:

👉 https://buymeacoffee.com/nightintel

---

## 📄 License

MIT License

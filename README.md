# Rolling Calendar Widget for Notion

A lightweight, embeddable calendar widget that shows a rolling window of weeks centered on today — designed to drop straight into any Notion page.

![Rolling Calendar Widget](screenshot.png)

**[Live demo →](https://amber9904.github.io/calendar-in-notion-widget/)**

---

## Features

- **Rolling week view** — see past and upcoming weeks at a glance, centered on today
- **Today highlight** — current day is always visually distinct
- **Month banding** — alternating background colors make month boundaries easy to scan
- **Relative week labels** — This, Next, Last, and numbered weeks in the right column
- **Fully customizable** — accent color, month highlight color (separate light/dark values), week start day, number of weeks shown, compact mode, dark mode
- **Multi-language** — English, Español, Français, Deutsch
- **Persistent settings** — all preferences saved in `localStorage`

---

## Embed in Notion

1. Host the widget (or use the live demo URL above)
2. In Notion, type `/embed` and choose **Embed**
3. Paste the URL and click **Embed link**

> **Tip:** If Notion shows a stale version after an update, add `?v=2` (or increment the number) to the URL to force a refresh.

---

## Settings

Click the **⚙** icon at the bottom of the widget to open settings:

| Setting | Description |
|---|---|
| Language | English, Español, Français, Deutsch |
| Week starts on | Monday or Sunday |
| Weeks back / forward | How many weeks to show before and after today |
| Today highlight | Color used for today's cell and current-week accents |
| Month highlight | Background color for alternating months (separate light & dark values) |
| Dark mode | Toggle dark theme |
| Compact rows | Smaller row height for tighter embeds |

---

## Self-hosting

The widget is a single `index.html` file with no dependencies.

```bash
git clone https://github.com/amber9904/calendar-in-notion-widget.git
```

Open `index.html` in any browser, or deploy to any static host (GitHub Pages, Cloudflare Pages, Netlify, etc.).

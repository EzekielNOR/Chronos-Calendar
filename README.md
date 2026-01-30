# Chronos Calendar

A clean, local-first calendar app for iPad (and other devices) that syncs with Google Calendar, iCloud, or any iCal feed.

**Your data stays on your device.** Calendar URLs are stored locally in your browser—nothing is sent to any server.

![Chronos Calendar](chronos1.png)

---

## Features

- **Month & Week views** — toggle between views, swipe to navigate
- **Event search** — quickly find any event by name
- **Morning briefing** — pops up at 07:00 with your day's agenda
- **Customizable reminders** — 15min, 30min, 1hr, or 2hrs before events
- **Multiple calendars** — custom names, colors, and visibility toggles
- **Tap any day** to see full event list, tap an event for details
- **Works offline** after initial setup (syncs when online)
- **Dark mode** — easy on the eyes

---

## Installation (iPad)

### Step 1: Open in Safari
Go to: **[https://ezekielnor.github.io/Chronos-Calendar/](https://ezekielnor.github.io/Chronos-Calendar/)**

> ⚠️ Must use Safari—won't work from Files app or other browsers.

### Step 2: Add to Home Screen

1. Tap the **Share button** (square with arrow pointing up)
2. Scroll down and tap **"Add to Home Screen"**
3. Name it whatever you like, tap **Add**

### Step 3: Open from Home Screen
Launch Chronos from your home screen. It now runs as a standalone app—no browser bars, works offline.

---

## Setup: Adding Your Calendars

### Get your Google Calendar secret URL:
1. Open [Google Calendar](https://calendar.google.com) on a computer
2. Click the **⚙️ gear icon** → **Settings**
3. On the left, click the calendar you want to add
4. Scroll down to **"Secret address in iCal format"**
5. Copy the URL (starts with `https://calendar.google.com/calendar/ical/...`)

### Add it to Chronos:
1. Tap the **⚙️ Settings** button (top right)
2. Paste the URL in the **iCal URL** field
3. Give it a name (e.g., "Work", "Family", "Kids")
4. Pick a color
5. Tap **Add Calendar**

![Settings Panel](chronos2.png)

Repeat for each calendar you want to track. They'll all show up color-coded.

---

## How It Works

| Feature | Description |
|---------|-------------|
| **Month/Week toggle** | Switch views with the toggle buttons |
| **Swipe navigation** | Swipe left/right to change weeks or months |
| **Search** | Tap 🔍 to search events by name |
| **Auto-sync** | Fetches updates every 60 seconds |
| **Morning briefing** | Shows today's events at 07:00 (or tap "Agenda" anytime) |
| **Event reminders** | Popup + sound at your chosen time before events |
| **Calendar toggle** | Show/hide calendars without deleting them |
| **Day view** | Tap any day to see all events |
| **Event details** | Tap an event for full info (time, location, description) |

---

## Tips

- **Enable notifications** when prompted—needed for reminders to work
- **Multiple family members?** Each person sets up their own calendars on their own device. Nothing is shared between devices.
- **Shared Google Calendar?** Just add the same calendar URL on each device
- **Hide a calendar temporarily?** Use the toggle switch in Settings instead of deleting
- **Customize reminder time** in Settings (15min to 2 hours)

---

## Privacy

🔒 **100% local storage**

- Calendar URLs stored only in your browser
- No accounts, no servers, no tracking
- Each device is completely independent
- We use a CORS proxy to fetch calendars (required by browsers), but your URLs are not logged or stored

---

## Troubleshooting

**App won't open / buttons don't work:**
- Make sure you're opening from Home Screen, not Safari
- Try removing and re-adding to Home Screen

**Calendar not showing events:**
- Double-check the iCal URL is correct (should start with `https://`)
- Make sure the calendar has events in the current month
- Check the calendar toggle is enabled in Settings

**No notifications:**
- Tap "Enable" on the notification banner
- Check iPad Settings → Safari → Notifications

---

## Credits

Created by **Ezekiel Hauge**  
[Eztheory AS](https://eztheory.no) · [GitHub](https://github.com/EzekielNOR/Chronos-Calendar)

---

Questions or issues? Open an issue or reach out!

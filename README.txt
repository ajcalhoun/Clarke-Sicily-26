# Trip Itinerary App

A travel app for your group — itinerary, weather forecasts, and packing list.
Works on any phone or computer. No app store. No account needed to use it.

---

## Step 1 — Open this folder in Claude Code

1. Open **Claude Code** on your computer.
2. Click the folder icon (or use **File → Open**) and select this folder.
3. That's it — you're ready to start building your app.

---

## Step 2 — Tell Claude what your trip looks like

Just talk to Claude like you're texting a friend. Some things to say:

> "Change the trip name to Costa Rica 2026"

> "Update the dates to February 14–24 and the route to San José · Arenal · Manuel Antonio"

> "Add day 1 on February 14: fly from Dallas to San José, arrive at 4pm, check in to hotel, dinner nearby"

> "Add day 2: zip-lining tour at 8am, lunch at the lodge, hot springs at La Fortuna at 4pm, dinner at 7pm"

> "Change the colors to jungle green and gold"

> "Add a packing category for beach gear: swimsuit, reef-safe sunscreen, snorkel mask, water sandals"

Claude will make the changes directly to your file. You can open `index.html` in any browser at any time to see how it looks.

---

## Optional — Connect a Google Sheet or Google Doc for your itinerary

Instead of describing each day to Claude one by one, you can plan your whole trip in a Google Sheet or Google Doc first and then tell Claude to pull from it.

**Google Sheet:** Build a simple spreadsheet with columns for date, time, activity, and notes. Then tell Claude:
> "My itinerary is in this Google Sheet: [paste the link]. Read it and build out all the days in the app."

**Google Doc:** Write your itinerary out as a document — one section per day, bullet points, whatever feels natural. Then tell Claude:
> "Here's my itinerary document: [paste the link]. Use it to fill in all the days."

Make sure the document is set to "Anyone with the link can view" before sharing the link with Claude.

Once Claude has read your itinerary, you can also ask it to fill in the skeleton for every day at once:
> "The DAYS array only covers the first N days of the trip. Add skeleton day objects for the remaining dates through [end date]. Each entry needs date, day number, label, title, loc, color, and tip. Leave events empty — the Google Sheet integration will populate them automatically."

---

## Step 3 — Put it online (free)

Once your app is ready, you'll share a link that anyone on the trip can open.

### Make a GitHub account
1. Go to [github.com](https://github.com) and sign up for a free account.

### Create a new repository (this is just a project folder on GitHub)
1. After signing in, click the **+** in the top right → **New repository**
2. Give it a name like `costa-rica-2026`
3. Make sure it's set to **Public**
4. Click **Create repository**

### Upload your files
1. On your new repository page, click **uploading an existing file**
2. Drag all four files from this folder into the upload area:
   - `index.html`
   - `manifest.json`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes** at the bottom

### Turn on GitHub Pages
1. Go to **Settings** (tab near the top of your repository page)
2. Click **Pages** in the left sidebar
3. Under "Branch" select **main**, leave the folder as `/ (root)`, click **Save**
4. Wait about 2 minutes, then your app is live at:
   `https://YOURUSERNAME.github.io/REPOSITORYNAME`

Share that link with everyone going on the trip.

### Updating the app later
If you make more changes with Claude, just come back to GitHub, go to your repository, click on `index.html`, click the pencil icon to edit — or click **Add file → Upload files** to replace it with your updated version.

---

## Step 4 — Add it to your phone's home screen

Once it's live online, you can install it like an app — no App Store needed.

**On iPhone:** Open the link in **Safari** → tap the Share button (the box with an arrow) → tap **Add to Home Screen** → tap **Add**

**On Android:** Open the link in **Chrome** → tap the three-dot menu → tap **Add to Home Screen**

It will appear on your home screen with an icon, just like a real app. It even works offline after the first time you open it.

---

## What's in this folder

| File | What it is |
|---|---|
| `index.html` | The entire app — everything is in here |
| `manifest.json` | Tells your phone how to install it |
| `icon-192.png` | App icon |
| `icon-512.png` | App icon (larger version) |
| `README.txt` | These instructions |

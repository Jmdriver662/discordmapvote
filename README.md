# 🗺️ Map Vote Dashboard

A free, no-install web tool for posting map vote polls to Discord.  
Posts map images + a native Discord poll (one vote per person) via Webhook — **no bot required**.

🔗 **[Open the app](https://YOUR-USERNAME.github.io/map-vote-dashboard)**

---

## What it does

1. You add map names and image URLs
2. Click **Post Maps + Poll to Discord**
3. The app sends to your channel:
   - An intro message
   - A native Discord poll (enforces one vote per person automatically)
   - Each map as an image embed below, for players to browse
4. Discord closes the poll after your chosen duration and shows the winner

---

## Hosting on GitHub Pages (free, 5 minutes)

### Step 1 — Create a GitHub account
If you don't have one, sign up at [github.com](https://github.com).

### Step 2 — Create a new repository
1. Click the **+** button → **New repository**
2. Name it `map-vote-dashboard` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the file
1. Click **Add file** → **Upload files**
2. Drag `discord_map_vote.html` into the upload area
3. **Important:** Rename it to `index.html` before uploading, or rename it after by clicking the file → pencil icon
4. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository → **Settings** → **Pages** (in the left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose **main** branch and **/ (root)** folder
4. Click **Save**

After about 60 seconds, your app will be live at:
```
https://YOUR-USERNAME.github.io/map-vote-dashboard/
```

That's it — share this URL with anyone who wants to run a map vote!

---

## How users get their Webhook URL

Each user needs to create a webhook in **their own Discord server**:

1. Open Discord → go to the channel where votes should be posted
2. Click the gear icon ⚙️ to edit the channel
3. Go to **Integrations** → **Webhooks** → **New Webhook**
4. Give it a name (e.g. "Map Vote") and click **Copy Webhook URL**
5. Paste it into the app

> **Privacy note:** Webhook URLs are only stored in the user's own browser (localStorage). They are never sent to any server other than Discord directly.

---

## Updating the app

To update to a newer version:
1. Download the new `discord_map_vote.html`
2. Go to your GitHub repository
3. Click the existing `index.html` file → pencil icon → paste new content → **Commit changes**

GitHub Pages will update within a minute.

---

## Notes

- **Max 10 maps** per vote (Discord poll limit)
- Map names must be **55 characters or fewer**
- Image URLs must be **direct links** to images (ending in `.jpg`, `.png`, `.gif`, etc.)
- The poll duration can be 1 hour up to 3 days
- All settings are auto-saved in the browser — they'll be there on the next visit
- Works best in Chrome, Firefox, Edge, and Safari (modern versions)

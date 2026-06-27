# 🗺️ Map Vote Dashboard

A free, no-install web tool for posting map vote polls to Discord.  
Posts map images + a native Discord poll (one vote per person) via Webhook — **no bot required**.

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

## Notes

- **Max 10 maps** per vote (Discord poll limit)
- Map names must be **55 characters or fewer**
- Image URLs must be **direct links** to images (ending in `.jpg`, `.png`, `.gif`, etc.)
- The poll duration can be 1 hour up to 3 days
- All settings are auto-saved in the browser — they'll be there on the next visit
- Works best in Chrome, Firefox, Edge, and Safari (modern versions)
- Added live version @ https://rustandchill.net/mapvote.html

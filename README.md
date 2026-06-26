# Guest Parking — iPhone Setup Guide

One file in this folder:
- **`parking-permit.html`** — the whole app (don't edit this)

Everything personal — your credentials **and** your vehicles — is stored only on
each device. Nothing private lives in this repo, so the repository can safely be
**public**.

---

## Step 1 — Host on GitHub Pages (free, one time)

The app needs to be hosted online so your iPhone can open it and install it to your home screen. GitHub Pages is free and takes about 5 minutes.

### 1a. Create a GitHub account
Go to **github.com** and sign up if you don't have an account.

### 1b. Create a new repository
1. Click the **+** button (top right) → **New repository**
2. Name it anything, e.g. `parking-permit`
3. Visibility can be **Public** — no plate numbers or credentials are stored in this repo
4. Click **Create repository**

### 1c. Upload the file
1. On the new repo page, click **uploading an existing file**
2. Drag `parking-permit.html` into the upload area
3. Click **Commit changes**

### 1d. Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Set branch to **main**, folder to **/ (root)**
4. Click **Save**
5. Wait ~60 seconds, then refresh — you'll see a green banner with your URL, e.g.:
   ```
   https://yourusername.github.io/parking-permit/parking-permit.html
   ```
   Copy that URL — you'll use it in the next step.

---

## Step 2 — Add to iPhone Home Screen

1. On your iPhone, open **Safari** (must be Safari, not Chrome)
2. Go to your GitHub Pages URL from Step 1d
3. Tap the **Share** button (the box with an arrow pointing up)
4. Scroll down and tap **Add to Home Screen**
5. Name it `Parking` (or whatever you want)
6. Tap **Add**

The icon will appear on your home screen like any other app.

---

## Step 3 — First-time setup on the app

1. Tap the new icon to open the app
2. A setup screen will appear asking for:
   - **Apartment** — your apartment number (e.g. `A101`)
   - **Passcode** — your parking passcode
   - **Email** — your email (for permit confirmation)
   - **Phone** — your phone number, digits only with country code (e.g. `14255551234`)
3. Tap **Save & Continue**

That's it. Your credentials are stored only on your phone — they're never uploaded anywhere.

---

## Adding or changing vehicles

Vehicles are saved **on your device**, not in this repo.

1. In the app, tap the **⚙ gear** icon (top right)
2. Under **Vehicles**, tap **+ Add Vehicle**
3. Fill in **Name** (e.g. Audi), **Plate**, and a **Description** (e.g. Red Audi A4)
4. Tap **← Back** — your cars are saved automatically

Tap the **×** on a vehicle card to remove it. You can also register a one-off car
without saving it by choosing **Guest / Other** on the main screen and typing the plate.

---

## Sharing with your girlfriend

1. Send her the same GitHub Pages URL
2. She follows Steps 2 and 3 on her phone (apartment and passcode are the same; she enters **her** email and phone)
3. She adds **her own** vehicles under ⚙ → Vehicles

Each person's credentials and vehicles stay on their own device.

---

## Daily use

1. Tap the **Parking** icon on your home screen
2. Select the vehicle
3. Select how many hours
4. Tap **Register Permit**

If the direct registration works, you'll see a green "✓ Permit registered!" toast and you're done.
If it opens a browser tab instead, just tap the **register** button on that page (one tap).

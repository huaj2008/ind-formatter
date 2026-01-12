# IND Text Formatter - Word Add-in

A Word add-in for converting text to Title Case or Sentence Case, while preserving pharmaceutical acronyms (FDA, IND, NDA, etc.).

---

## 🚀 Setup Instructions (One-time, ~5 minutes)

### Step 1: Create the GitHub Repository

1. Go to https://github.com/new
2. Fill in:
   - **Repository name:** `ind-formatter`
   - **Description:** `Word add-in for IND document formatting`
   - **Public** (required for GitHub Pages)
3. Click **Create repository**

### Step 2: Upload the Files

1. On your new repo page, click **"uploading an existing file"** link
2. Drag and drop ALL these files/folders:
   ```
   manifest.xml
   taskpane.html
   functions.html
   assets/  (the whole folder with icons)
   ```
3. Click **Commit changes**

### Step 3: Enable GitHub Pages

1. Go to your repo: https://github.com/huaj2008/ind-formatter
2. Click **Settings** (tab at top)
3. Click **Pages** (left sidebar)
4. Under "Source", select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes, then your site is live at:
   ```
   https://huaj2008.github.io/ind-formatter/
   ```

### Step 4: Test the URL

Open this in your browser to verify it works:
```
https://huaj2008.github.io/ind-formatter/taskpane.html
```

You should see the add-in panel UI.

---

## 📥 Install the Add-in in Word

### For You (and Your Test Users)

**Windows:**
1. Open Word
2. Go to **Insert** → **Add-ins** → **My Add-ins**
3. Click **Upload My Add-in** (may need to click dropdown)
4. Browse to `manifest.xml` and select it
5. Done! Look for "IND Formatter" in the Home tab

**Mac:**
1. Open Word
2. Go to **Insert** → **Add-ins** → **My Add-ins**
3. Click the folder icon at bottom
4. Select `manifest.xml`
5. Done!

---

## 🎯 How to Use

1. **Select text** in your document
2. Click **Title Case** or **Sentence Case** button in the ribbon
3. Or click **More Options** to open the sidebar panel

**Preserved acronyms:**
FDA, IND, NDA, BLA, ANDA, DMF, CTD, eCTD, PK, PD, ADME, AUC, Cmax, Tmax, API, GMP, cGMP, ICH, QbD, PAT, CPP, CQA, QTPP

---

## 👥 Sharing with Others

Just send them:
1. The `manifest.xml` file
2. These instructions (Step 4 of Install)

They don't need GitHub or any technical setup!

---

## 🔧 Troubleshooting

**"Add-in won't load"**
- Make sure GitHub Pages is enabled (Step 3)
- Wait 2-3 minutes after enabling Pages
- Check the URL works: https://huaj2008.github.io/ind-formatter/taskpane.html

**"Upload My Add-in" not visible**
- You may need Microsoft 365 subscription
- Try: Insert → Add-ins → click dropdown arrow → Upload My Add-in

**Clear cache if issues persist (Windows):**
- Close Word
- Delete folder: `%LOCALAPPDATA%\Microsoft\Office\16.0\Wef\`
- Reopen Word and reload add-in

---

## 📁 Files in This Package

```
ind-formatter/
├── manifest.xml      ← Defines the add-in (share this with users)
├── taskpane.html     ← Sidebar panel UI
├── functions.html    ← Ribbon button code
├── assets/
│   ├── icon-16.png
│   ├── icon-32.png
│   ├── icon-64.png
│   └── icon-80.png
└── README.md         ← This file
```

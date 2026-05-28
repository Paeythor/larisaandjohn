# Larisa & John — Wedding Website

**Red, White, & We Do! · July 2, 2026**

A single-page wedding website with a live countdown timer and Venmo QR code.

---

## 📁 File Structure

```
larisaandjohn/
├── index.html        ← The wedding website (everything is in here)
├── README.md         ← This file
└── .nojekyll         ← Tells GitHub Pages not to use Jekyll
```

---

## 🚀 How to Publish on GitHub Pages

1. **Create a new GitHub repo** — name it anything, e.g. `larisaandjohn`
2. **Upload this folder's contents** (or push via Git):
   ```bash
   git init
   git add .
   git commit -m "Initial wedding site"
   git remote add origin https://github.com/YOUR_USERNAME/larisaandjohn.git
   git push -u origin main
   ```
3. **Enable GitHub Pages:**
   - Go to your repo on GitHub
   - Click **Settings** → **Pages**
   - Under *Source*, choose **Deploy from a branch**
   - Select **main** branch, **/ (root)** folder
   - Click **Save**
4. **Your site will be live at:**
   `https://YOUR_USERNAME.github.io/larisaandjohn`

It may take 1–2 minutes to go live the first time.

---

## ✏️ Things You Can Customize in index.html

| What | Search for in VS Code |
|------|-----------------------|
| Wedding date/time | `WEDDING_DATE` in the `<script>` block |
| Venue address | `4300 N. Canyon Rd` |
| RSVP phone | `801-427-7887` |
| Venmo handle | `Larisa-Schumann` (appears 3 times) |

---

## 📱 Sharing the Link

Once live, share the GitHub Pages URL with guests. They can:
- View the countdown timer
- See ceremony / luncheon / reception times
- Scan the QR code or tap the Venmo button to send a gift

---

*Built with plain HTML, CSS, and JavaScript — no frameworks, no dependencies to install.*

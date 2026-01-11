# 🚀 Deploy Your Wedding Invitation - V4_1 Scroll Frame

Your elegant scroll frame invitation is ready to go live! 🎊

---

## ✅ What's Ready:
- ✅ **index.html** - V4_1 Scroll Frame (elegant with wooden rods)
- ✅ **final.jpg** - Your invitation image (3.0MB)
- ✅ **music.mp3** - Background music (4.6MB)
- ✅ **All files committed to git**

---

## 🚀 FASTEST Option: Netlify (2 Minutes!)

### Step 1: Create Deployment Package
```bash
cd /home/Sharat/Documents/wedding_invite/_1

# Create a clean folder with only what's needed
mkdir -p ~/wedding-deploy
cp index.html final.jpg music.mp3 ~/wedding-deploy/
```

### Step 2: Deploy to Netlify
1. Open browser: https://app.netlify.com/drop
2. **Drag the folder** `~/wedding-deploy` onto the page
3. Wait 10 seconds - Done! ✅

### Step 3: Get Your Link
You'll instantly get a link like:
```
https://sparkly-unicorn-abc123.netlify.app
```

### Step 4: Customize Your URL (Optional)
1. Click "Site settings"
2. Click "Change site name"
3. Choose: `sharat-sreekutty-wedding`
4. Your new link:
```
https://sharat-sreekutty-wedding.netlify.app
```

**That's it!** Share this link with your guests! 🎉

---

## 🐙 Professional Option: GitHub Pages (10 Minutes)

### Step 1: Check if you have GitHub account
If not, create one at https://github.com/signup

### Step 2: Create Repository
1. Go to: https://github.com/new
2. Repository name: `wedding-invitation`
3. Make it **Public** ⚠️ (required for free hosting)
4. Do NOT check "Add a README"
5. Click "Create repository"

### Step 3: Connect Your Local Repository
```bash
cd /home/Sharat/Documents/wedding_invite/_1

# Check if remote already exists
git remote -v

# If you see "origin", update it (replace YOUR-USERNAME):
git remote set-url origin https://github.com/YOUR-USERNAME/wedding-invitation.git

# If no remote exists, add it:
git remote add origin https://github.com/YOUR-USERNAME/wedding-invitation.git
```

### Step 4: Push to GitHub
```bash
git push -u origin main
```

You'll be asked for credentials:
- **Username**: Your GitHub username
- **Password**: Use a Personal Access Token (not your actual password)
  - Create token at: https://github.com/settings/tokens/new
  - Check "repo" permission
  - Copy the token and paste it

### Step 5: Enable GitHub Pages
1. Go to: `https://github.com/YOUR-USERNAME/wedding-invitation`
2. Click **Settings** tab (top right)
3. Click **Pages** in left sidebar
4. Under "Branch": Select **main** (not "None")
5. Click **Save**
6. Wait 1-2 minutes ⏱️

### Step 6: Your Link is Live! 🎉
```
https://YOUR-USERNAME.github.io/wedding-invitation/
```

---

## 🔗 Create Short Link (For Easy Sharing)

Once you have your Netlify or GitHub link:

### Option A: Bitly
1. Go to: https://bitly.com (free signup)
2. Click "Create" → "Link"
3. Paste your full URL
4. Get short link: `bit.ly/SharatWedding`

### Option B: TinyURL
1. Go to: https://tinyurl.com
2. Paste your full URL
3. Customize: `tinyurl.com/sharat-sreekutty-2026`
4. Click "Make TinyURL"

---

## 📱 Share with Guests

### WhatsApp Message Template:
```
🪔 Jai Guru Dev 🪔

Dear Family & Friends,

With immense joy, we invite you to the wedding of:

💐 Sharat Prabhakaran & Sreekutty Sreekandan

📅 Saturday, 25th January 2026
⏰ Muhurtham: 12:11 PM - 12:31 PM
📍 Crystal Convention Centre, Nagaroor

View your invitation:
👉 [YOUR SHORT LINK]

Looking forward to your blessings and presence!

🙏 Meena Prabhakaran & Bharat Prabhakaran
```

### SMS Template:
```
🪔 Wedding Invitation

Sharat & Sreekutty
25 Jan 2026, 12:11 PM
Crystal Convention Centre

View: [SHORT LINK]

- Prabhakaran Family
```

---

## 📊 Which Option Should I Choose?

| Feature | Netlify | GitHub Pages |
|---------|---------|--------------|
| **Speed** | ⚡ 2 minutes | 🐢 10 minutes |
| **Ease** | ⭐⭐⭐ Easiest | ⭐⭐ Moderate |
| **URL** | name.netlify.app | name.github.io/repo |
| **Custom Domain** | ✅ Free | ✅ Free |
| **Analytics** | ✅ Built-in | ❌ Need extra tool |
| **Git Required** | ❌ No | ✅ Yes |

**Recommendation**:
- **First time?** → Use **Netlify** (super easy!)
- **Have GitHub?** → Use **GitHub Pages** (more professional)

---

## 🆘 Troubleshooting

### Music Not Playing?
- Normal! Browsers block autoplay
- Guests need to tap/click first
- Music will start after they tap "Tap to Unfurl"

### Image Not Showing?
```bash
# Verify file exists
ls -lh final.jpg

# Should show: 3.0M size
```

### Git Push Failed?
```bash
# Create a Personal Access Token:
# 1. Go to: https://github.com/settings/tokens/new
# 2. Name: "Wedding Invitation Deploy"
# 3. Check: "repo" permission
# 4. Click "Generate token"
# 5. Copy the token
# 6. Use it as password when pushing
```

### Netlify Deploy Failed?
- Make sure you're dragging the folder, not individual files
- Folder must contain: index.html, final.jpg, music.mp3
- Try refreshing the Netlify page

---

## 🎯 Quick Command Reference

```bash
# View your files
cd /home/Sharat/Documents/wedding_invite/_1
ls -lh index.html final.jpg music.mp3

# Test locally in browser
xdg-open index.html

# Create deployment folder for Netlify
mkdir -p ~/wedding-deploy
cp index.html final.jpg music.mp3 ~/wedding-deploy/

# Open deployment folder in file manager
xdg-open ~/wedding-deploy

# Check git status
git status
git log --oneline -5

# Push to GitHub (after setting up remote)
git push -u origin main
```

---

## ✨ Your Invitation Features

When guests visit your link, they'll see:
1. 🪔 **Glowing lamp icon** with "Tap to Unfurl"
2. 📜 **Rolled scroll** with wooden rods and golden borders
3. ✨ **Smooth unfurl animation** (2.5 seconds)
4. 🎵 **Background music** starts playing
5. ⭐ **Golden sparkles** cascade down
6. 💌 **Crystal clear invitation** image revealed
7. 📱 **Perfect on all devices** - mobile, tablet, desktop

---

## 🎊 Next Steps

1. **Choose deployment method** (Netlify or GitHub Pages)
2. **Follow the steps** above for your chosen method
3. **Get your shareable link**
4. **Create a short URL** (Bitly or TinyURL)
5. **Test on your phone** first
6. **Share with guests!** 🎉

---

## 🎁 Bonus: QR Code

Want to add a QR code to printed cards?

1. Go to: https://www.qr-code-generator.com
2. Select "URL"
3. Enter your link
4. Customize color (gold/black)
5. Download high-res PNG
6. Print on invitation cards

Guests can scan to open invitation! 📲

---

**Need help? Check DEPLOYMENT_GUIDE.md for detailed troubleshooting.**

**Ready to deploy? Start with Netlify - it's the easiest!** 🚀

---

💐 **Made with love for Sharat & Sreekutty's special day!**

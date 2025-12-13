# Aqra Privacy Policy - Deployment Guide

## ✅ Privacy Policy Successfully Created!

Your privacy policy has been created and deployed to GitHub Pages.

---

## 📍 **FINAL URLS** (Copy These to App Stores)

### **Primary URL (RECOMMENDED):**
```
https://gazal1994.github.io/Aqra/privacy-policy.html
```

### **Alternative URL:**
```
https://gazal1994.github.io/Aqra/privacy-policy/
```

---

## 📂 Repository Structure

```
Aqra/ (GitHub Repository)
├── privacy-policy.html          ← Direct file access
├── privacy-policy/
│   └── index.html              ← Directory-based access
├── README.md
└── (other files...)
```

---

## 🚀 Deployment Status

- ✅ Files created and committed
- ✅ Pushed to GitHub (master branch)
- ⏳ GitHub Pages deployment (takes 1-5 minutes)

---

## ✓ How to Verify the URL Works

### Method 1: Browser Test
1. Open your browser
2. Visit: `https://gazal1994.github.io/Aqra/privacy-policy.html`
3. You should see the privacy policy page (not a 404 error)

### Method 2: HTTP Status Check (PowerShell)
```powershell
Invoke-WebRequest -Uri "https://gazal1994.github.io/Aqra/privacy-policy.html" -Method Head
```
**Expected Result:** Status Code 200 (OK)

### Method 3: Command Line (curl)
```bash
curl -I https://gazal1994.github.io/Aqra/privacy-policy.html
```
**Expected Result:** `HTTP/2 200`

---

## 🔧 Enable GitHub Pages (If Not Already Enabled)

1. Go to: https://github.com/gazal1994/Aqra/settings/pages
2. Under **"Source"**:
   - Branch: `master` (or `main`)
   - Folder: `/ (root)`
3. Click **Save**
4. Wait 1-5 minutes for deployment
5. Verify the URL is live

---

## 📱 Update App Store & Google Play Console

### **For Apple App Store Connect:**
1. Log in to App Store Connect
2. Go to your app → App Information
3. Find **Privacy Policy URL**
4. Enter: `https://gazal1994.github.io/Aqra/privacy-policy.html`
5. Save changes

### **For Google Play Console:**
1. Log in to Google Play Console
2. Go to Policy → App content
3. Find **Privacy Policy**
4. Enter: `https://gazal1994.github.io/Aqra/privacy-policy.html`
5. Save and Submit

---

## 📋 Privacy Policy Features

✅ **Comprehensive Coverage:**
- Information collection (personal, automatic, push notifications)
- Data usage and purposes
- Sharing and disclosure policies
- Security measures and data retention
- User rights (GDPR, CCPA compliant)
- Children's privacy (COPPA compliant)
- Third-party services (Firebase)
- International data transfers
- Contact information

✅ **Technical Requirements:**
- Mobile-responsive design
- Clean, professional appearance
- No login required
- Globally accessible (no geo-blocking)
- Returns HTTP 200 (not 404)
- Static HTML (no backend required)

✅ **Navigation:**
- Back link to main site
- Footer navigation links
- Contact information clearly visible

---

## 🔍 Troubleshooting

### Problem: URL returns 404
**Solution:**
1. Check if GitHub Pages is enabled (see above)
2. Wait 5 minutes for deployment
3. Clear browser cache
4. Try the alternative URL

### Problem: Changes not showing
**Solution:**
1. Wait for GitHub Pages to rebuild (1-5 minutes)
2. Clear browser cache (Ctrl+Shift+Delete)
3. Try incognito/private mode
4. Hard refresh (Ctrl+F5)

### Problem: App store rejects URL
**Solution:**
1. Verify URL returns HTTP 200 (not 301, 302, or 404)
2. Ensure page loads without login
3. Test from different countries/IPs
4. Use exact URL (no trailing spaces)

---

## 📝 How to Update the Privacy Policy

1. **Edit the file:**
   ```bash
   cd Aqra-website
   # Edit privacy-policy.html or privacy-policy/index.html
   ```

2. **Update the "Last updated" date**

3. **Commit and push:**
   ```bash
   git add privacy-policy.html privacy-policy/index.html
   git commit -m "Update privacy policy - [describe changes]"
   git push origin master
   ```

4. **Wait 1-5 minutes** for GitHub Pages to rebuild

---

## ✉️ Contact Information in Privacy Policy

The privacy policy includes:
- **Email:** support@aqra.ai
- **Privacy Team:** privacy@aqra.ai
- **Website:** https://gazal1994.github.io/Aqra/
- **GitHub:** https://github.com/gazal1994/aqra-front

*(Update these if needed before app store submission)*

---

## 🎯 Next Steps

1. ✅ **Wait 2-3 minutes** for GitHub Pages deployment
2. ✅ **Verify URL** works in browser
3. ✅ **Test from mobile device** (optional)
4. ✅ **Copy URL** to App Store Connect
5. ✅ **Copy URL** to Google Play Console
6. ✅ **Submit for review**

---

## 📞 Support

If you need to make changes or have questions:
- Edit the HTML files directly in the repository
- Commit and push changes
- Changes will be live within 1-5 minutes

---

**Created:** December 13, 2025  
**Status:** ✅ Ready for App Store submission  
**Last Updated:** December 13, 2025

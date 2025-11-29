# Google Search Console Setup Guide
**Website:** studiolegalebrillante.it  
**Date:** November 8, 2025

---

## 📋 **Step-by-Step Instructions**

### **Step 1: Create a Google Account (if needed)**
1. Go to https://www.google.com
2. Sign in with your Google account (or create one)
3. Use: `laurabrill@live.it` or your preferred email

---

### **Step 2: Access Google Search Console**
1. Go to: https://search.google.com/search-console
2. Click **"Start now"** or **"Add property"**

---

### **Step 3: Add Your Property (Website)**

#### **Option A: Domain Property (Recommended)**
1. Select **"Domain"** option
2. Enter: `studiolegalebrillante.it` (without http/https)
3. Click **"Continue"**
4. You'll see DNS verification instructions

#### **Option B: URL Prefix Property**
1. Select **"URL prefix"** option
2. Enter: `https://www.studiolegalebrillante.it` or `https://studiolegalebrillante.it`
3. Click **"Continue"**

---

### **Step 4: Verify Ownership**

#### **If using Domain Property:**
1. Google will provide a TXT record to add to your DNS
2. Go to **GoDaddy DNS Management**
3. Add the TXT record provided by Google
4. Wait for DNS propagation (can take up to 48 hours)
5. Click **"Verify"** in Google Search Console

#### **If using URL Prefix Property:**
Choose one of these verification methods:

**Method 1: HTML File Upload (Easiest)**
1. Download the HTML file Google provides
2. Upload it to your GitHub repository root
3. Commit and push to GitHub
4. Click **"Verify"** in Google Search Console

**Method 2: HTML Tag**
1. Copy the meta tag Google provides
2. Add it to your `<head>` section in `index.html`
3. Commit and push to GitHub
4. Click **"Verify"** in Google Search Console

**Method 3: DNS Record** (Same as Domain Property)

---

### **Step 5: Submit Your Sitemap**

Once verified:

1. In Google Search Console, go to **"Sitemaps"** in the left sidebar
2. Under **"Add a new sitemap"**, enter: `sitemap.xml`
3. Click **"Submit"**
4. Google will process your sitemap (usually within a few hours)

**Your sitemap URL will be:**
- `https://www.studiolegalebrillante.it/sitemap.xml`
- or `https://studiolegalebrillante.it/sitemap.xml`

---

### **Step 6: Request Indexing (Optional but Recommended)**

1. In Google Search Console, go to **"URL Inspection"** (top search bar)
2. Enter your homepage URL: `https://www.studiolegalebrillante.it/`
3. Click **"Request Indexing"**
4. Google will crawl and index your page

---

## ✅ **What You'll Get**

After setup, you'll be able to:
- ✅ See how Google views your site
- ✅ Monitor search performance
- ✅ See which keywords bring traffic
- ✅ Get notified of indexing issues
- ✅ Submit new content for indexing
- ✅ Monitor mobile usability
- ✅ Check page speed insights

---

## 🔍 **Important URLs to Monitor**

After setup, regularly check:
1. **Performance** - See search queries and clicks
2. **Coverage** - Check for indexing errors
3. **Sitemaps** - Verify sitemap is processed
4. **Mobile Usability** - Ensure mobile-friendly
5. **Core Web Vitals** - Page speed metrics

---

## 📝 **Quick Checklist**

- [ ] Create/access Google account
- [ ] Go to Google Search Console
- [ ] Add property (domain or URL prefix)
- [ ] Verify ownership (DNS, HTML file, or meta tag)
- [ ] Submit sitemap.xml
- [ ] Request indexing for homepage
- [ ] Wait 24-48 hours for initial data

---

## 🆘 **Troubleshooting**

### **Verification Failed?**
- Wait 24-48 hours after adding DNS records
- Check DNS propagation: https://www.whatsmydns.net/
- Ensure DNS record is exactly as Google provided
- Try a different verification method

### **Sitemap Not Found?**
- Ensure sitemap.xml is in the root directory
- Check it's accessible: `https://studiolegalebrillante.it/sitemap.xml`
- Verify GitHub Pages is serving the file
- Wait a few hours after submission

### **No Data Showing?**
- It takes 24-48 hours for initial data
- Ensure your site is indexed (check "Coverage" tab)
- Submit URLs for indexing manually
- Be patient - data accumulates over time

---

## 📚 **Additional Resources**

- **Google Search Console Help:** https://support.google.com/webmasters
- **Sitemap Guidelines:** https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview
- **Verification Methods:** https://support.google.com/webmasters/answer/9008080

---

**Note:** After DNS is configured for your custom domain, make sure to use the exact domain (with or without www) that matches your CNAME file in Google Search Console.


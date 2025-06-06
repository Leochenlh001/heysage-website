# HeySage Website

## 🌐 Website Overview

This is the official website for HeySage AI Mental Health Assistant, featuring product introduction, features, pricing information, and legal documents in both Chinese and English.

## 📁 File Structure

```
website/
├── index.html              # Chinese Homepage
├── index-en.html           # English Homepage
├── privacy-policy.html     # Chinese Privacy Policy
├── privacy-policy-en.html  # English Privacy Policy
├── terms-of-service.html   # Chinese Terms of Service
├── terms-of-service-en.html # English Terms of Service
├── README.md               # Chinese Documentation
└── README-EN.md            # English Documentation
```

## 🚀 Deploy to GitHub Pages - Step by Step

### Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** button in the top right corner
3. Select **"New repository"**
4. Repository name: `heysage-website` (or any name you prefer)
5. Set to **Public** (required for free GitHub Pages)
6. Check **"Add a README file"**
7. Click **"Create repository"**

### Step 2: Upload Website Files

**Option A: Using GitHub Web Interface**
1. In your new repository, click **"uploading an existing file"**
2. Drag and drop all files from the `website/` folder
3. Or click **"choose your files"** and select all HTML files
4. Add commit message: "Initial website upload"
5. Click **"Commit changes"**

**Option B: Using Git Command Line**
```bash
# Clone the repository
git clone https://github.com/yourusername/heysage-website.git
cd heysage-website

# Copy all website files to the repository folder
cp /path/to/your/website/* .

# Add, commit, and push
git add .
git commit -m "Add HeySage website files"
git push origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab (at the top of the repository)
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select **"Deploy from a branch"**
5. Choose **"main"** branch (or **"master"** if that's your default)
6. Select **"/ (root)"** folder
7. Click **"Save"**

### Step 4: Wait for Deployment

- GitHub will show a green checkmark when deployment is complete
- This usually takes 5-10 minutes
- Your website will be available at: `https://yourusername.github.io/heysage-website/`

### Step 5: Verify Your Website

Visit the following URLs to test:
- **Homepage (Chinese)**: `https://yourusername.github.io/heysage-website/`
- **Homepage (English)**: `https://yourusername.github.io/heysage-website/index-en.html`
- **Privacy Policy**: `https://yourusername.github.io/heysage-website/privacy-policy.html`
- **Terms of Service**: `https://yourusername.github.io/heysage-website/terms-of-service.html`

## 🔗 Configure App Store Connect

Once deployed, use these URLs in App Store Connect:

- **Privacy Policy URL**: `https://yourusername.github.io/heysage-website/privacy-policy-en.html`
- **Terms of Use URL**: `https://yourusername.github.io/heysage-website/terms-of-service-en.html`
- **Support URL**: `https://yourusername.github.io/heysage-website/index-en.html#contact`
- **Marketing URL**: `https://yourusername.github.io/heysage-website/`

## 🛠️ Troubleshooting GitHub Pages

### Problem: "404 - File not found"
**Solution:**
- Check that `index.html` exists in the root directory
- Ensure all file names are lowercase
- Verify the repository is public

### Problem: "Changes not showing"
**Solution:**
- Wait 5-10 minutes for GitHub to rebuild
- Check the Actions tab for build status
- Try force refresh (Ctrl+F5 or Cmd+Shift+R)

### Problem: "Pages tab not available"
**Solution:**
- Make sure repository is public
- Check that you have admin permissions
- Ensure repository has at least one commit

## 🎨 Customization Guide

### Update Contact Information
Replace these placeholders in all files:
- `support@heysage.com` → Your actual email
- `privacy@heysage.com` → Your privacy email
- `legal@heysage.com` → Your legal email
- `(Your Company Address)` → Your actual address

### Add App Store Link
When your app is published, update the download buttons:
```html
<a href="https://apps.apple.com/app/heysage/idXXXXXX" class="cta-button">Download Now</a>
```

### Add Favicon
1. Create a `favicon.ico` file (16x16 or 32x32 pixels)
2. Upload it to your repository root
3. It will automatically appear in browser tabs

## 🌍 Custom Domain (Optional)

### Step 1: Purchase Domain
- Buy a domain from providers like GoDaddy, Namecheap, etc.
- Example: `heysage.com`

### Step 2: Configure DNS
Add these DNS records at your domain provider:
```
Type: CNAME
Name: www
Value: yourusername.github.io

Type: A
Name: @
Value: 185.199.108.153
Value: 185.199.109.153
Value: 185.199.110.153
Value: 185.199.111.153
```

### Step 3: Configure GitHub Pages
1. In repository Settings → Pages
2. Under "Custom domain", enter your domain
3. Check "Enforce HTTPS"
4. Save changes

## 🔒 Security Best Practices

### Enable HTTPS
- Always check "Enforce HTTPS" in Pages settings
- Your privacy policy and terms require secure connections

### Regular Updates
- Keep legal documents updated
- Review and update contact information
- Monitor for broken links

## 📊 Analytics (Optional)

### Add Google Analytics
Add this code before `</head>` in all HTML files:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 📱 Mobile Optimization

The website is already responsive and optimized for:
- iPhone (all sizes)
- iPad 
- Android phones and tablets
- Desktop browsers

## 🌐 Multi-language Setup

### Current Languages
- **Chinese (Default)**: `index.html`, `privacy-policy.html`, `terms-of-service.html`
- **English**: `index-en.html`, `privacy-policy-en.html`, `terms-of-service-en.html`

### Language Switching
Users can switch languages using the language selector in the top navigation.

## 📞 Support Information

### For Technical Issues
- **Email**: support@heysage.com
- **Response Time**: Within 48 hours

### For Legal Questions  
- **Email**: legal@heysage.com
- **Privacy**: privacy@heysage.com

## ✅ Pre-Launch Checklist

- [ ] All files uploaded to GitHub
- [ ] GitHub Pages enabled and working
- [ ] All links tested and functional
- [ ] Contact information updated
- [ ] Privacy policy and terms reviewed
- [ ] Mobile responsiveness tested
- [ ] App Store URLs configured
- [ ] Custom domain configured (if applicable)
- [ ] Analytics setup (if desired)

## 🎯 App Store Requirements Met

✅ **Privacy Policy**: Comprehensive, GDPR/CCPA compliant  
✅ **Terms of Service**: Detailed with medical disclaimers  
✅ **Support Contact**: Clear contact information  
✅ **Responsive Design**: Works on all devices  
✅ **HTTPS**: Secure connections enabled  
✅ **Multi-language**: Chinese and English support

Your website is now ready for App Store submission! 🎉 
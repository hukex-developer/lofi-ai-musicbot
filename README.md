# LO-F! AI Website

Professional website for your Discord music bot with Privacy Policy and Terms of Service pages.

## 📁 Files

- `index.html` - Homepage with bot features and invite link
- `privacy.html` - Privacy Policy (required for Discord verification)
- `terms.html` - Terms of Service (required for Discord verification)
- `style.css` - Modern pink-themed styling

## 🚀 Deployment Options

### Option 1: GitHub Pages (Free & Easy)

1. Create a new GitHub repository
2. Upload all files from the `website` folder
3. Go to Settings → Pages
4. Select "main" branch and "/" (root) folder
5. Your site will be live at: `https://yourusername.github.io/repo-name`

### Option 2: Netlify (Free & Fast)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the `website` folder
3. Your site will be live instantly with a custom URL

### Option 3: Vercel (Free & Professional)

1. Go to [vercel.com](https://vercel.com)
2. Import the `website` folder
3. Deploy with one click

### Option 4: AWS S3 + CloudFront (Your existing AWS)

1. Create an S3 bucket
2. Upload all files
3. Enable static website hosting
4. (Optional) Add CloudFront for HTTPS

## 📝 After Deployment

1. **Update Bot Invite Link** in `index.html`:
   - Replace `YOUR_CLIENT_ID` with your actual bot client ID

2. **Add URLs to Discord Developer Portal**:
   - Go to Discord Developer Portal → Your Bot → General Information
   - Add Privacy Policy URL: `https://yoursite.com/privacy.html`
   - Add Terms of Service URL: `https://yoursite.com/terms.html`

## 🎨 Customization

The website uses your bot's pink (#FF1493) theme. To customize:

- Edit colors in `style.css`
- Update content in HTML files
- Add your bot's logo/images

## ✅ Discord Verification Ready

These pages meet Discord's requirements for:
- Bot verification
- Public bot listing
- Partnership applications

---

**Made with ❤️ by HUKEX**

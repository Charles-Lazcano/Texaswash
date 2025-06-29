# Deployment Guide

This guide will help you deploy your AquaClean Pro website to Render and Vercel.

## 🚀 Deploy to Vercel

### Step 1: Prepare Your Repository
1. Create a new GitHub repository
2. Push your code to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/aquaclean-pro.git
   git push -u origin main
   ```

### Step 2: Deploy to Vercel
1. Go to [vercel.com](https://vercel.com)
2. Sign up/Login with your GitHub account
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will automatically detect it's a static site
6. Click "Deploy"
7. Your site will be live at `https://your-project-name.vercel.app`

### Step 3: Custom Domain (Optional)
1. In your Vercel dashboard, go to your project
2. Click "Settings" → "Domains"
3. Add your custom domain
4. Update DNS records as instructed

## 🌊 Deploy to Render

### Step 1: Create Render Account
1. Go to [render.com](https://render.com)
2. Sign up with your GitHub account

### Step 2: Deploy Static Site
1. Click "New +" → "Static Site"
2. Connect your GitHub repository
3. Configure the deployment:
   - **Name**: `aquaclean-pro` (or your preferred name)
   - **Build Command**: `echo "No build required"`
   - **Publish Directory**: `.`
   - **Environment**: `Static Site`
4. Click "Create Static Site"
5. Your site will be live at `https://your-site-name.onrender.com`

### Step 3: Custom Domain (Optional)
1. In your Render dashboard, go to your static site
2. Click "Settings" → "Custom Domains"
3. Add your custom domain
4. Update DNS records as instructed

## 🔧 Post-Deployment

### Update Contact Information
1. Edit `index.html` and update:
   - Phone number
   - Email address
   - Service area
   - Business hours

### Add Real Images
1. Replace placeholder content in the gallery section
2. Add your business logo
3. Include before/after photos of your work

### Configure Analytics
1. Add Google Analytics tracking code
2. Set up Google Search Console
3. Configure Facebook Pixel (if using Facebook ads)

### Test Your Site
1. Test on mobile devices
2. Check contact form functionality
3. Verify all links work
4. Test loading speed

## 📱 Mobile Optimization Checklist

- [ ] Site loads quickly on mobile
- [ ] Navigation is touch-friendly
- [ ] Text is readable on small screens
- [ ] Contact form works on mobile
- [ ] Images are optimized for mobile

## 🔍 SEO Checklist

- [ ] Meta descriptions are unique
- [ ] Title tags are optimized
- [ ] Images have alt text
- [ ] Site has a sitemap
- [ ] Robots.txt is configured
- [ ] Schema markup is added (optional)

## 🛠️ Troubleshooting

### Common Issues

**Site not loading:**
- Check if all files are committed to GitHub
- Verify deployment logs in Vercel/Render dashboard
- Ensure `index.html` is in the root directory

**Styling issues:**
- Check if `styles.css` is properly linked
- Verify CSS file is committed to repository
- Clear browser cache

**Contact form not working:**
- Check browser console for JavaScript errors
- Verify form validation is working
- Test on different browsers

### Getting Help

- Check deployment logs in your hosting platform
- Test locally first: `python -m http.server 8000`
- Validate HTML: [validator.w3.org](https://validator.w3.org)
- Validate CSS: [jigsaw.w3.org](https://jigsaw.w3.org/css-validator)

## 📞 Support

If you need help with deployment:
- Vercel: [vercel.com/support](https://vercel.com/support)
- Render: [render.com/docs](https://render.com/docs)
- GitHub: [github.com/help](https://github.com/help)

---

**Your website is now live and ready to attract customers! 🎉** 
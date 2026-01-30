# Luxury Holiday Caravan Website

A professional, modern website for a luxury holiday caravan rental built with AngularJS, CSS3, and responsive design principles.

## 🌟 Features

- **Professional Design**: Elegant gradient-based design with smooth animations
- **Responsive Layout**: Fully responsive design that works on all devices
- **AngularJS Framework**: Professional JavaScript framework for scalability
- **Separated Exterior/Interior Galleries**: Images organized into logical sections
- **Interactive Pricing Cards**: Clear pricing options with hover effects
- **Modal Image Viewer**: Click any image to view it in full size
- **Contact Section**: Easy-to-find contact information with icons
- **Smooth Animations**: Professional fade-in and scroll animations

## 📁 Project Structure

```
holiday-caravan/
├── index.html              # Main HTML file
├── css/
│   └── style.css          # All styles and responsive design
├── js/
│   └── app.js             # AngularJS application logic
├── data/
│   └── images/            # All caravan images
│       ├── frontalview.jpg
│       ├── sideview.jpg
│       ├── livingspace.jpg
│       └── ... (all other images)
└── README.md              # This file
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `holiday-caravan`)
5. Make it **Public**
6. Click "Create repository"

### Step 2: Upload Files

**Option A: Using GitHub Web Interface**

1. On your repository page, click "uploading an existing file"
2. Drag and drop ALL files and folders from the `holiday-caravan` directory
3. Commit the changes

**Option B: Using Git Command Line**

```bash
# Navigate to your project directory
cd holiday-caravan

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Holiday Caravan Website"

# Add remote repository (replace YOUR-USERNAME and YOUR-REPO)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be published at: `https://YOUR-USERNAME.github.io/YOUR-REPO/`

### Step 4: Wait and Access

- GitHub Pages takes a few minutes to build and deploy
- Once ready, visit your URL to see the live site
- Any updates you push to the main branch will automatically redeploy

## 📝 Customization Guide

### Updating Images

1. Place new images in the `data/images/` folder
2. Update the image arrays in `js/app.js`:
   - `$scope.exteriorImages` for exterior photos
   - `$scope.interiorImages` for interior photos

### Updating Pricing

Edit the `$scope.pricingOptions` array in `js/app.js`:

```javascript
{
    title: 'Your Package Name',
    price: '£XXX',
    duration: 'Your Duration',
    features: [
        'Feature 1',
        'Feature 2',
        'Feature 3'
    ]
}
```

### Updating Contact Information

Edit the contact section in `index.html`:

```html
<a href="tel:+44XXXXXXXXXX">+44 XXXX XXXXXX</a>
```

### Changing Colors

Edit CSS variables in `css/style.css`:

```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    --accent-color: #667eea;
}
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Advanced styling with gradients, animations, and flexbox/grid
- **AngularJS 1.8.2**: JavaScript framework for dynamic content
- **Google Fonts**: Playfair Display and Inter fonts
- **Responsive Design**: Mobile-first approach

## 🎨 Design Features

- Gradient backgrounds for modern look
- Smooth hover animations
- Modal image viewer
- Responsive grid layouts
- Professional typography
- Optimized for performance

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Contact Information

- **Phone**: +44 7808 550201
- **Facebook**: [Link to Facebook page]

## 📄 License

This project is for personal/commercial use for the holiday caravan rental business.

## 🔄 Updates and Maintenance

To update the website after initial deployment:

1. Make changes to your local files
2. Commit changes: `git add . && git commit -m "Description of changes"`
3. Push to GitHub: `git push origin main`
4. GitHub Pages will automatically rebuild (takes 2-5 minutes)

## 💡 Tips

- Keep image file sizes under 500KB for faster loading
- Use descriptive alt text for all images
- Test on mobile devices before deploying
- Consider adding Google Analytics for visitor tracking
- Back up your images regularly

## 🐛 Troubleshooting

**Images not showing:**
- Check that image paths are correct (`./data/images/filename.jpg`)
- Ensure all images are uploaded to GitHub
- Verify image file names match exactly (case-sensitive)

**Site not updating:**
- Clear browser cache
- Wait 5 minutes for GitHub Pages to rebuild
- Check GitHub Actions tab for build errors

**Layout issues on mobile:**
- Test using browser DevTools mobile view
- Check that viewport meta tag is present
- Verify CSS media queries are working

---

Built with ❤️ for luxury coastal getaways

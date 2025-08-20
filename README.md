# 🏴‍☠️ Treasure Hunt Form

A beautiful, responsive treasure hunt form divided into 8 rounds for collecting game data.

## 🚀 Quick Deploy to Vercel

### Option 1: Deploy with Vercel CLI (Recommended)

1. **Install Vercel CLI globally:**
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel:**
   ```bash
   vercel login
   ```

3. **Deploy to production:**
   ```bash
   vercel --prod
   ```

### Option 2: Deploy via GitHub

1. **Push your code to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Treasure Hunt Form"
   git remote add origin https://github.com/yourusername/treasure-hunt-form.git
   git push -u origin main
   ```

2. **Go to [vercel.com](https://vercel.com) and:**
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will automatically detect it's a static HTML project
   - Click "Deploy"

### Option 3: Drag & Drop (Simplest)

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Choose "Upload Template"
4. Drag and drop your `treasure_hunt_form.html` file
5. Click "Deploy"

## 📁 Project Structure

```
treasure-hunt-form/
├── treasure_hunt_form.html    # Main form file
├── vercel.json               # Vercel configuration
├── package.json              # Project dependencies
└── README.md                 # This file
```

## 🔧 Customization

- **Form Fields:** Modify the HTML to add/remove input fields
- **Styling:** Update the CSS in the `<style>` section
- **Validation:** Modify the JavaScript form handling
- **Database:** Uncomment and configure the fetch API call

## 🌐 Environment Variables

If you need to connect to a database, add these in your Vercel dashboard:
- `DATABASE_URL` - Your database connection string
- `API_KEY` - Any required API keys

## 📱 Features

- ✅ Responsive design for all devices
- ✅ Modern UI with hover effects
- ✅ Form validation
- ✅ Ready for database integration
- ✅ Optimized for Vercel deployment

## 🚀 After Deployment

Your form will be available at: `https://your-project-name.vercel.app`

## 📞 Support

For Vercel deployment issues, check the [Vercel documentation](https://vercel.com/docs).

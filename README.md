# 🎯 To-Do List Widget for DakBoard

![To-Do Widget Demo](https://img.shields.io/badge/status-ready%20to%20use-brightgreen)

## ✨ Features

- ✅ Create custom lists
- ✅ Add tasks with subtasks
- ✅ Drag and drop tasks between lists
- ✅ Drag lists to position them anywhere on your DakBoard
- ✅ Resize lists to fit your layout
- ✅ Real-time syncing across all devices
- ✅ Works on DakBoard, tablets, and phones
- ✅ Transparent design for DakBoard overlay
- ✅ Touch-friendly mobile version

## 🚀 Quick Start

**⚠️ IMPORTANT: Open `SETUP_INSTRUCTIONS.html` in your browser for complete step-by-step setup guide!**

## 📋 What You Need

- A free [Supabase](https://supabase.com) account (for database)
- A [GitHub](https://github.com) account (for hosting) - OR just use locally
- 15 minutes to set up

## 📁 Files Included

- `index.html` - Main widget (transparent, for DakBoard)
- `mobile.html` - Mobile-friendly version (with background)
- `icon-180.png` - Homescreen bookmark app icon
- `SETUP_INSTRUCTIONS.html` - **START HERE!** Complete setup guide
- `README.md` - This file

## 🎬 Getting Started

### Step 1: Open the Setup Guide
1. Download/clone this repository
2. Open `SETUP_INSTRUCTIONS.html` in your web browser
3. Follow the step-by-step instructions

### Step 2: Summary of What You'll Do
1. Create a free Supabase account
2. Run the provided SQL to set up your database
3. Get your API credentials
4. Add credentials to the HTML files
5. Host on GitHub Pages (or use locally)

**The setup guide walks you through everything with screenshots and copy-paste code!**

## 💻 How to Use

### On DakBoard:
1. Add a **Widget** block
2. Copy and paste the following:
   
```html



    
    
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <style>
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            background: transparent;
        }
        iframe {
            width: 100%;
            height: 100%;
            border: none;
            background: transparent;
        }
    </style>
</head>
<body>
    <iframe src="INSERT GITHUB PAGE URL" allowtransparency="true" frameborder="0" scrolling="no"></iframe>
</body>
</html>
    


    


```
3. Replace `INSERT_YOUR_GITHUB_PAGES_URL_HERE` with your actual URL: `https://your-username.github.io/your-repo/`
4. Save the block
5. Resize and position on your dashboard
6. Drag lists to arrange them as you like
7. Resize lists by dragging their right edge

### On Your Phone:
1. Open the mobile version: `https://your-username.github.io/your-repo/mobile.html`
2. Add to home screen for easy access:
   - **iPhone:** Safari → Share → Add to Home Screen
   - **Android:** Chrome → Menu → Add to Home Screen
3. All changes sync instantly with your DakBoard!

## 🎨 Customization

You can customize:
- **Colors:** Edit the CSS gradients and backgrounds
- **Font:** Change `font-family: 'Comfortaa'` to any Google Font
- **Sizes:** Adjust font sizes, padding, and spacing in the CSS
- **Layout:** Lists can be positioned anywhere on DakBoard

## 🔒 Privacy & Data

- Your data is stored in YOUR Supabase database (not shared with anyone)
- Only people with your GitHub Pages URL can access your widget
- Don't share your Supabase credentials with anyone
- Want to collaborate? Just share your URL with family/friends!

## 🐛 Troubleshooting

**Widget shows "Loading..." forever:**
- Check that you added your Supabase credentials to BOTH files
- Make sure you ran the SQL setup script
- Open browser console (F12) to see error messages

**Tasks don't sync:**
- Enable Replication for both tables in Supabase (see setup guide)
- Make sure all devices use the same URL

**Can't add lists:**
- Verify you created BOTH the tasks and lists tables
- Check browser console for errors

For more help, see the troubleshooting section in `SETUP_INSTRUCTIONS.html`


## 📝 License

Free to use and modify for personal use. Share it, customize it, make it your own!

## 🆘 Need More Help?

1. First, check `SETUP_INSTRUCTIONS.html` - it has detailed steps with code examples
2. Open your browser console (F12) to see error messages
3. Make sure you completed ALL setup steps, especially:
   - Running the SQL script
   - Enabling Replication
   - Adding credentials to BOTH HTML files

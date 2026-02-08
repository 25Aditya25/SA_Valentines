# 💕 Valentine's Memory Matching Game

A beautiful memory matching game created for Valentine's Day! Match pairs of cards to reveal special qualities.

## 🎮 How to Play

1. Click on any card to reveal a quality
2. Click on another card to reveal a second quality
3. If the two cards match, they stay revealed
4. Continue until all pairs are matched
5. Try to complete the game with as few moves as possible!

## 🚀 Hosting on GitHub Pages

To host this game on GitHub Pages:

1. **Create a GitHub repository**
   - Go to GitHub and create a new repository
   - Name it something like `valentines-memory-game`

2. **Upload the files**
   - Upload `index.html` to your repository
   - You can do this via the web interface or using git:
     ```bash
     git init
     git add index.html
     git commit -m "Initial commit"
     git branch -M main
     git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
     git push -u origin main
     ```

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your game**
   - Your game will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## ✨ Features

- Beautiful Valentine's Day themed design
- Responsive layout that works on mobile and desktop
- Smooth animations and transitions
- Move counter and match tracker
- Completion message when all pairs are found

## 🎨 Customization

You can easily customize the game by editing the `qualities` array in the JavaScript section:

```javascript
const qualities = [
    "Beautiful",
    "Kind",
    "Smart",
    // Add your own qualities here!
];
```

Make sure to keep an even number of qualities (or the code will create pairs automatically).

Enjoy your Valentine's Day game! 💕
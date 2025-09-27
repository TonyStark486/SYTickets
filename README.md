# 📂 Mobile Number File Finder

This is a simple web app hosted on **GitHub Pages**.  
Users can enter their mobile number, solve a quick captcha, and download their invitation ticket (`files/mobilenumber.png`).

## 🚀 How it works
1. Enter mobile number.
2. Solve a random math question (anti-bot verification).
3. If the file exists in the `/files` folder → download link appears.
4. If not found → message: *"No file found for this number. Please contact Roshan."*

## 📁 Project Structure
- `index.html` → UI
- `style.css` → Styling (modern light theme)
- `script.js` → Logic (captcha + search)
- `files/` → Place your `mobilenumber.png` files here

## 🌐 Hosting on GitHub Pages
1. Create a new repo.
2. Upload all files.
3. Add your `files/mobilenumber.png` images.
4. Enable GitHub Pages from `Settings → Pages`.
5. Access live site at: `https://USERNAME.github.io/REPO-NAME`

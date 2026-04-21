# Ruixi Li — Personal Website

## How to update
Edit `index.html` directly — it's plain HTML with comments marking each section.

### Add your photo
Find this comment in index.html:
```html
<!-- To use your LinkedIn photo: replace the div below with:
     <img src="[YOUR_PHOTO_URL_HERE](https://www.linkedin.com/in/ruixi-li-/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BwiJCs2MIQt%2Bl8WCBXNtMfA%3D%3D)" alt="Ruixi Li" loading="lazy"> -->
```
Right-click your LinkedIn profile photo → "Copy image address", then paste the URL.

### Update your LinkedIn URL
Search for `linkedin.com/in/ruixi-li` and replace with your actual LinkedIn profile URL.

## How to deploy (GitHub Pages — free)
1. Create a repo named `rl3328.github.io` on GitHub
2. Push this folder:
   ```bash
   cd ~/personal-website
   git init && git add . && git commit -m "init website"
   git remote add origin https://github.com/rl3328/rl3328.github.io.git
   git push -u origin main
   ```
3. Go to repo Settings → Pages → Source: main branch → Save
4. Your site is live at **https://rl3328.github.io** in ~60 seconds

## How to update the live site
```bash
cd ~/personal-website
git add . && git commit -m "update" && git push
```

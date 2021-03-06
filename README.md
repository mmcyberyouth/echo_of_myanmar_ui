# UI for Echo Of Myanmar Project

"ပြည်မြန်မာ၏ပဲ့တင်သံ" Website အတွက် UI Project ဖြစ်ပါသည်။

# To Do List

- [x] UI Design မှ Template Code အဖြစ်သို့ပြောင်းရန်

# UI Design Link (Figma)

[UI Design Link](https://www.figma.com/file/7xP0JhwGJawM6e02dL8Qzd/HearTheVoiceOfMyanmar?node-id=0%3A1)

# How to set-up project on local machine?

 - Fork this project to your personal repo.
 - Clone the forked repo to your local machine via `git clone <URI>`
 - In your terminal `npm install` command to install `node_modules`
 - Code in your local project 
 - Don't miss to latest commit 
 - When you pushed to the repo you must pull request to merge your code to main project

# Sass complications

```bash
# install sass as global
npm install -g sass
# compile scss to css
npm run build
# watch and compile scss to css
npm run watch
```

# Project Structure

```bash
echo_of_myanmar_ui
├── README.md
├── color.txt
├── gallery.html
├── index.html
├── new.html
├── news.html
├── package-lock.json
├── package.json
└── src
    ├── css
    │   ├── app.css
    │   ├── app.scss
    │   ├── custom.css
    │   └── custom.scss
    ├── img
    │   ├── bg1.jpg
    │   ├── bg2.jpg
    │   ├── bg2.png
    │   ├── gallery1.jpg
    │   ├── gallery2.jpg
    │   ├── gallery3.jpg
    │   ├── gallery4.jpg
    │   ├── gallery5.jpg
    │   ├── logo.jpg
    │   ├── logo1.jpg
    │   └── news1.jpg
    └── js
        └── app.js
```

# Notices

```html
<!-- Don't base on large screen -->
<nav class="expand-lg"></nav>

<!-- Base on medium size screen -->
<nav class="expand-md"></nav>
```

# Extra Reading

SCSS ရှင်းလင်းချက် ကို `color.txt` တွင် ဖတ်ပါ။


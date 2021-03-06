# Contriburing to Darkness
Please help us **improve existing skins and create new ones**. Pull requests are welcome!



## How to start developing?
1. First, [install Darkness locally](./README.MD) if you haven't
1. Run `npm start` to **watch SCSS files** and compile them in real time.
1. Write your awesome code - see below


## How do I...
##### Fix or improve an existing skin
Edit `/themes/websites/[WEBSITE].scss` (e.g. `/themes/websites/youtube.scss`)

##### Add skin for an new website (e.g. GitHub, Twitter)
Open `/themes/websites/WEBSITE-TEMPLATE.scss` in your code editor and follow the instructions.

##### Fix or improve a color theme
Edit `/themes/themes/[THEME].scss` (e.g. `/themes/themes/material.scss`)

##### Create a new color theme (in addition to Monokai, Tomorrow, etc.)
Open `/themes/themes/THEME-TEMPLATE.scss` in your code editor and follow the instructions.


## How to push code back to Darkness?
1. Please test your changes locally in Chrome
1. Commit and push:
	```bash
	git add .
	git commit -m 'Description of Changes'
	git push origin master
	```
1. Go to [GitHub](https://github.com) and navigate to **your fork of Darkness**. 
1. Click the **Compare & pull request** button.
1. Write a description and click **Create pull request**.

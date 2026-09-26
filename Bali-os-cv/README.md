# Bali-os Personal CV

## Student Information

- **Complete Name:** David Rey P. Bali-os
- **Year Level:** 4th Year
- **Set/Section:** BSIT 4-G
- **Subject:** IT415 – Application Development and Emerging Technologies

## Project Description

This project is a simple personal Curriculum Vitae webpage created using HTML and CSS. It presents my profile, education, technical skills, freelance experience, certifications, and contact information in a clean and responsive layout. The page is designed to work on both desktop and mobile screens and is suitable for publishing through GitHub Pages.

## Project Structure

```text
Bali-os-cv/
├── assets/
│   └── images/
│       └── mypicture.jpg
├── index.html
├── style.css
└── README.md
```

## Technologies Used

- HTML5 for the webpage structure and content
- CSS3 for the layout, colors, typography, and responsive design
- No JavaScript or external libraries are required

## How to View the Website Locally

1. Download or clone the project folder.
2. Open the `Bali-os-cv` folder.
3. Double-click `index.html` to open it in a web browser.
4. Resize the browser window to check the responsive layout.

For a local web server, open a terminal inside the project folder and run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in a browser. Press `Ctrl + C` in the terminal to stop the server.

## How to Upload the Project to GitHub

1. Sign in to GitHub and create a new public repository named `Bali-os-cv`.
2. Do not add another README, `.gitignore`, or license when creating the repository because this project already contains a README.
3. Open a terminal inside the project folder and run:

```bash
git init
git add .
git commit -m "Create personal CV webpage"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/Bali-os-cv.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your own GitHub username before running the `git remote add origin` command.

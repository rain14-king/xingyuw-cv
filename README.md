# Xingyu Wang - CV Website

A minimalist, monochrome CV website built with HTML, CSS, and JavaScript. Deployed on GitHub Pages.

## Features

- **Minimalist Design**: Clean, professional layout with monochrome color scheme
- **Dark/Light Mode**: Toggle between themes with persistent preference
- **Responsive**: Fully responsive design for mobile, tablet, and desktop
- **Smooth Navigation**: Smooth scrolling and active section highlighting
- **Downloadable PDF**: Direct download of your CV
- **Fast Performance**: No frameworks, pure HTML/CSS/JS

## Sections

- **About**: Career objective and professional summary
- **Education**: Master's and Bachelor's degrees
- **Skills**: Programming, IoT, and engineering skills
- **Projects**: Work experience and IoT projects
- **Languages**: Language proficiency levels

## Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/xingyuwang/xingyuw-cv.git
   cd xingyuw-cv
   ```

2. Open `index.html` in your browser:
   ```bash
   open index.html
   ```

### Deployment to GitHub Pages

1. Create a new repository on GitHub (e.g., `xingyuw-cv`)

2. Push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/xingyuwang/xingyuw-cv.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to Repository Settings → Pages
   - Select source: Deploy from a branch
   - Branch: main, Folder: / (root)
   - Click Save

4. Your site will be live at: `https://xingyuwang.github.io/xingyuw-cv/`

## Customization

### Update Your Information

Edit `index.html` to update:
- Personal information (name, contact details)
- Career objective
- Education history
- Skills
- Projects
- Languages

### Update Resume PDF

Replace `assets/resume.pdf` with your actual resume PDF file.

### Change Theme Colors

Edit `css/style.css` and modify the CSS variables in `:root` for light mode and `[data-theme="dark"]` for dark mode.

## Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Flexbox, Grid
- **JavaScript**: Vanilla JS (no frameworks)
- **GitHub Actions**: CI/CD for deployment

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- **Email**: xingyuw@mail.uni-paderborn.de
- **Phone**: (+49) 15127966226
- **Location**: Paderborn, Germany

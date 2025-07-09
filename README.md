# 💼 Paulo Victor - Portfolio

A modern and responsive portfolio built with Angular, showcasing my journey as a Software Engineer.

## 🚀 About the Project

This is my personal portfolio where I present my passion for technology and my experience as a developer. The site features a clean and modern design with subtle particle animations that create a unique visual experience.

### ✨ Key Features:
- 🎨 Modern and responsive design
- ⚡ Smooth animations with tsparticles
- 📱 Fully responsive for all devices
- 🔗 Direct links to GitHub and LinkedIn
- 🖼️ Profile picture display
- 🎯 Focus on user experience

## 🛠️ Technologies Used

- **Framework:** Angular 20
- **Language:** TypeScript
- **Styling:** SCSS + CSS3
- **Animations:** @tsparticles/angular
- **Build Tool:** Angular CLI
- **Version Control:** Git

## 📋 Prerequisites

Before you begin, you need to have the following installed on your machine:

- [Node.js](https://nodejs.org/) (version 20.19+ or 22.12+)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)
- [Git](https://git-scm.com/)

## 🔧 Installation and Setup

### 1. Clone the repository
```bash
git clone https://github.com/paulllo-victor/portfolio.git
cd portfolio
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the project in development mode
```bash
npm start
# or
ng serve
```

### 4. Open in browser
```
http://localhost:4200
```

## 📦 Production Build

To generate optimized files for production:

```bash
npm run build
```

The files will be generated in the `dist/portfolio/browser/` folder and will be ready for deployment on any static file hosting service.

### Deployment
1. Copy all files from the `dist/portfolio/browser/` folder
2. Upload to your hosting service
3. Configure the server to redirect 404s to `index.html`

## 🎨 Customization

### Change personal information
Edit the file `src/app/components/banner/banner.component.html`:
- Change the title "Software Engineer"
- Modify the personal description
- Update GitHub and LinkedIn links

### Replace profile picture
Replace the file `public/assets/images/profile.jpeg` with your photo.

### Customize colors and styles
Modify the file `src/app/components/banner/banner.component.scss` to adjust:
- Button colors
- Typography
- Spacing
- Animations

### Configure particles
Adjust settings in the file `src/app/components/banner/banner.component.ts`:
- Number of particles
- Movement speed
- Colors and opacity
- Interaction behaviors

## 👨‍💻 About Me

I'm passionate about technology with expertise in PHP, Laravel, and Node.js. I focus on creating scalable, efficient applications and enjoy working across the full stack to bring ideas to life.

### 🔗 Connect with me:
- **GitHub:** [paulllo-victor](https://github.com/paulllo-victor)
- **LinkedIn:** [Paulo Victor](https://www.linkedin.com/in/paulo-victor-22b615182)

⭐ **If this project helped you in any way, consider giving it a star!**

Made with ❤️ by [Paulo Victor](https://github.com/paulllo-victor)

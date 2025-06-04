# James McDaniel - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing projects, skills, and professional experience. Built with React and Tailwind CSS.

## 🌟 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling navigation with active section highlighting
- **Project Showcase**: Detailed project cards with technology stacks and links
- **Skills Section**: Organized skill categories with visual indicators
- **Contact Integration**: Direct links to email, LinkedIn, and GitHub

## 🚀 Live Demo

Visit the live website: [https://YOUR_USERNAME.github.io/james-mcdaniel-portfolio](https://YOUR_USERNAME.github.io/james-mcdaniel-portfolio)

## 📋 Prerequisites

Before running this project locally, make sure you have the following installed:

- **Node.js** (version 14.0 or higher)
  - Download from [nodejs.org](https://nodejs.org/)
  - Verify installation: `node --version`
- **npm** (comes with Node.js) or **yarn**
  - Verify npm: `npm --version`
  - Or install yarn: `npm install -g yarn`

## 🛠️ Local Development Setup

### Method 1: Using a Simple HTTP Server (Recommended for beginners)

If you just have the HTML file and want to run it locally:

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/james-mcdaniel-portfolio.git
   cd james-mcdaniel-portfolio
   ```

2. **Using Python (if you have Python installed)**
   ```bash
   # For Python 3
   python -m http.server 3000
   
   # For Python 2
   python -m SimpleHTTPServer 3000
   ```

3. **Using Node.js http-server**
   ```bash
   # Install http-server globally
   npm install -g http-server
   
   # Run the server
   http-server -p 3000
   ```

4. **Using Live Server (VS Code Extension)**
   - Install the "Live Server" extension in VS Code
   - Right-click on `index.html`
   - Select "Open with Live Server"

5. **Open in browser**
   - Navigate to `http://localhost:3000`
   - The website should load and be fully functional

### Method 2: React Development Environment

If you want to set up a full React development environment:

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/james-mcdaniel-portfolio.git
   cd james-mcdaniel-portfolio
   ```

2. **Create a new React app**
   ```bash
   npx create-react-app .
   ```

3. **Install additional dependencies**
   ```bash
   npm install lucide-react
   ```

4. **Replace the default files**
   - Replace the contents of `src/App.js` with the React component code
   - Update `src/index.css` with Tailwind CSS imports:
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

5. **Install and configure Tailwind CSS**
   ```bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p
   ```

6. **Update tailwind.config.js**
   ```javascript
   module.exports = {
     content: [
       "./src/**/*.{js,jsx,ts,tsx}",
     ],
     theme: {
       extend: {},
     },
     plugins: [],
   }
   ```

7. **Start the development server**
   ```bash
   npm start
   ```

8. **Open in browser**
   - The site will automatically open at `http://localhost:3000`
   - Changes will hot-reload automatically

## 📁 Project Structure

```
james-mcdaniel-portfolio/
│
├── index.html              # Main HTML file (if using static setup)
├── README.md              # This file
├── package.json           # Node.js dependencies (if using React)
├── src/                   # Source files (if using React)
│   ├── App.js            # Main React component
│   ├── index.js          # React entry point
│   └── index.css         # Global styles
├── public/               # Public assets (if using React)
│   ├── index.html        # HTML template
│   └── favicon.ico       # Site icon
└── build/                # Production build (generated)
```

## 🎨 Customization

### Updating Content

1. **Personal Information**
   - Edit the hero section with your name and title
   - Update the about section with your bio
   - Modify contact information and social links

2. **Projects**
   - Add/remove projects in the projects array
   - Update project descriptions, tech stacks, and links
   - Replace project images or use gradients

3. **Skills**
   - Modify skill categories and individual skills
   - Add new skill groups as needed
   - Update icons and descriptions

### Styling Changes

1. **Colors**
   - The site uses a blue color scheme (`text-blue-600`, `bg-blue-600`)
   - Update Tailwind classes to change the color theme

2. **Fonts**
   - Default fonts are system fonts
   - Add Google Fonts or custom fonts as needed

3. **Layout**
   - Modify Tailwind grid and spacing classes
   - Adjust responsive breakpoints

## 🚀 Deployment

### GitHub Pages

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Update portfolio website"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Select "Deploy from a branch"
   - Choose `main` branch and `/ (root)` folder
   - Save settings

3. **Access your site**
   - Visit `https://YOUR_USERNAME.github.io/james-mcdaniel-portfolio`

### Other Hosting Options

- **Netlify**: Drag and drop the build folder
- **Vercel**: Connect your GitHub repository
- **Surge.sh**: Run `npm install -g surge` and `surge`

## 🐛 Troubleshooting

### Common Issues

1. **Port already in use**
   ```bash
   # Find and kill the process using port 3000
   lsof -ti:3000 | xargs kill -9
   ```

2. **Node.js not found**
   - Ensure Node.js is properly installed
   - Restart your terminal after installation

3. **Permission errors**
   ```bash
   # Use sudo for global installations (macOS/Linux)
   sudo npm install -g http-server
   ```

4. **Images not loading**
   - Ensure image paths are correct
   - For GitHub Pages, use relative paths

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

James McDaniel
- **Email**: james@joinfloor.app
- **LinkedIn**: [linkedin.com/in/flio](https://linkedin.com/in/flio)
- **GitHub**: [github.com/JamesMcDaniel04](https://github.com/JamesMcDaniel04)
- **Website**: [joinfloor.app](https://www.joinfloor.app/)

---

⭐ If you found this project helpful, please give it a star on GitHub!

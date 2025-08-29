***REMOVED***

***REMOVED***



# Webpack Template

[![Webpack](https://img.shields.io/badge/webpack-5-blue?logo=webpack)](https://webpack.js.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/node-%3E%3D16-green?logo=node.js)](https://nodejs.org/)
[![npm](https://img.shields.io/badge/npm-%3E%3D9-red?logo=npm)](https://www.npmjs.com/)

A lightweight and maintainable **Webpack boilerplate** designed for modern web development.
This template provides a clean foundation with essential configurations for JavaScript, CSS, HTML, and asset management, making it easy to extend and adapt for future projects.



## 🚀 Features

* **Webpack 5** setup with production & development modes
* **Webpack Dev Server** with live reloading
* **CSS & Style loaders** for styling support
* **HTML loader & plugin** for HTML templating
* **Asset handling** for images (PNG, JPG, JPEG, SVG, GIF, WebP)
* **Clean build** (`dist` folder auto-cleans before every build)
* **Source maps** enabled in development for easier debugging



## 📦 Installation

1. Click the **"Use this template"** button at the top of this repository.
2. Create a new repository from this template.
3. Clone your newly created repo:

   ```bash
   git clone https://github.com/<your-username>/<your-new-repo>.git
   cd <your-new-repo>
   npm install
   ```



## 🛠 Usage

### Start Development Server

```bash
npm start
```

Runs webpack-dev-server with live reload. Your app will be served at:
👉 [http://localhost:8080](http://localhost:8080)

### Build for Production

```bash
npm run build
```

Bundles your app into the `dist` folder, optimized for deployment.



## 📂 Project Structure

```
webpack_template/
│── dist/               # Production-ready output (auto-generated)
│── src/
│   ├── index.js        # Main JS entry point
│   ├── template.html   # HTML template
│   └── styles.css      # Example stylesheet
│── webpack.config.js   # Webpack configuration
│── package.json        # Project metadata & scripts
```



## 🔧 Tech Stack

* Webpack 5
* Webpack Dev Server
* CSS Loader & Style Loader
* HTML Loader & HTML Webpack Plugin



## 🌱 Future Improvements

Planned enhancements to make this template even more powerful:

* [ ] **Babel integration** (support for modern JavaScript features and backwards compatibility)
* [ ] **SASS/SCSS support** for advanced styling
* [ ] **ESLint & Prettier** for linting and code formatting
* [ ] **Environment variables support** using dotenv
* [ ] **Code splitting & caching optimizations** for larger apps
* [ ] **TypeScript support** for type safety



## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 🎉

* Fork this repo & create your branch:

  ```bash
  git checkout -b feature/your-feature
  ```
* Commit your changes:

  ```bash
  git commit -m "feat: add your feature"
  ```
* Push the branch and open a Pull Request.



## 🐛 Issues

If you find any bugs or have suggestions, feel free to [open an issue](https://github.com/aqeel-sheikh/webpack_template/issues).



## 📜 License

This project is licensed under the **MIT License**.

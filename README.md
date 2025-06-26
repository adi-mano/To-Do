# JS Project Template

A minimal and modern boilerplate for JavaScript projects using Webpack, ESLint, and Prettier. Ideal for quick project bootstrapping with clean code practices.

---

## 🔧 Features

- ✅ Webpack (bundling)
- ✅ HTMLWebpackPlugin (auto-injects scripts)
- ✅ Style-loader & CSS-loader (CSS imports)
- ✅ ESLint (with Airbnb base config)
- ✅ Prettier (auto formatting)
- ✅ VSCode integration via `.vscode/settings.json`
- ✅ Forced LF line endings for cross-platform compatibility

---

## 📁 Project Structure

```
js-proj-template/
├── dist/                  # Production build output
├── node_modules/          # Installed dependencies
├── src/                   # Source code (entry point: index.js)
│   ├── index.js
│   └── style.css
├── .eslintrc.json         # ESLint configuration
├── .prettierrc            # Prettier configuration
├── .vscode/
│   └── settings.json      # VSCode editor settings (auto format on save, etc.)
├── package.json           # Project metadata and scripts
├── webpack.config.js      # Webpack configuration
└── README.md              # This file
```

---

## 🚀 Getting Started

```bash
npm install
npm run lint      # Runs ESLint
npm run format    # Formats with Prettier
npm run build     # Builds using Webpack (if added to scripts)
```

---

## 🧪 Recommendations

- Use `npm install` over `yarn` for consistency.
- Use VSCode with Prettier and ESLint extensions installed.
- Convert CRLF to LF if working across OS (already set up in settings).

---

## 📦 Installed Dev Dependencies

```bash
webpack
webpack-cli
html-webpack-plugin
style-loader
css-loader
eslint
eslint-config-airbnb-base
eslint-plugin-import
eslint-config-prettier
eslint-plugin-prettier
prettier
```

---

## 🧩 Future Ideas

- Add Babel for modern JS transpiling
- Add unit testing (Jest)
- Add TypeScript support

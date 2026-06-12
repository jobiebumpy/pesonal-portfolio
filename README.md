# Personal Portfolio

A modern, responsive personal portfolio website built with Angular. Showcase your projects, skills, and experience in a clean and professional manner.

## 📋 Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Development](#development)
- [Building](#building)
- [Testing](#testing)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **Modern Angular Setup** - Built with the latest Angular standalone components
- **Responsive Design** - Mobile-first, works seamlessly on all devices
- **SCSS Styling** - Pre-configured with SCSS for advanced styling
- **Clean Architecture** - Well-organized project structure for easy expansion
- **Route-based Navigation** - Built-in routing for multiple pages
- **Professional Layout** - Sections for hero, projects, about, and contact

## 🚀 Getting Started

### Prerequisites

- **Node.js** v18 or higher
- **npm** v9+ or **yarn** v3+
- Git for version control

You can check your versions with:
```bash
node --version
npm --version
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/jobiebumpy/pesonal-portfolio.git
   cd pesonal-portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

## 🔧 Development

Run the development server:
```bash
npm start
```

Navigate to `http://localhost:4200/` in your browser. The application will automatically reload whenever you modify any source files.

### Hot Module Replacement

The dev server uses Angular's built-in HMR (Hot Module Replacement) for fast development.

## 🏗️ Building

Build the project for production:
```bash
npm run build
```

Build artifacts will be stored in the `dist/personal-portfolio/` directory with optimizations enabled:
- Code minification
- Vendor chunk bundling
- Output hashing for cache busting
- Lazy-loaded modules

## 🧪 Testing

Run unit tests:
```bash
npm test
```

Tests are executed via Karma and use Jasmine for test specifications. Test files should be placed alongside their corresponding components with a `.spec.ts` extension.

Run tests with code coverage:
```bash
npm test -- --code-coverage
```

## 📁 Project Structure

```
pesonal-portfolio/
├── src/
│   ├── app/
│   │   ├── app.component.ts       # Root component
│   │   ├── app.component.html     # Root template
│   │   ├── app.component.scss     # Root styles
│   │   ├── app.config.ts          # App configuration & providers
│   │   └── app.routes.ts          # Route definitions
│   ├── index.html                 # Main HTML file
│   ├── main.ts                    # Application bootstrap
│   └── styles.scss                # Global styles
├── angular.json                   # Angular CLI configuration
├── tsconfig.json                  # TypeScript configuration
├── tsconfig.app.json              # App-specific TS config
├── tsconfig.spec.json             # Test-specific TS config
├── package.json                   # Dependencies & scripts
├── .gitignore                     # Git ignore rules
├── README.md                      # This file
└── dist/                          # Production build (generated)
```

## 🎨 Customization

### Update Project Information

Edit `src/app/app.component.ts`:
```typescript
export class AppComponent {
  title = 'Your Name\'s Portfolio';
}
```

### Modify HTML Template

Edit `src/app/app.component.html` to add your content, projects, and information.

### Customize Styles

Edit `src/app/app.component.scss` and `src/styles.scss`:
- Change color scheme
- Adjust responsive breakpoints
- Modify typography

### Add New Components

Generate a new component:
```bash
ng generate component components/header
```

### Add New Routes

Update `src/app/app.routes.ts` to add additional pages and routes.

### Update Package Information

Edit `package.json`:
- Update `name`, `version`, and `description`
- Add author information
- Customize npm scripts as needed

## 🌐 Deployment

### Deploy to GitHub Pages

1. Update `angular.json` with your repository URL
2. Install Angular CLI globally if needed:
   ```bash
   npm install -g @angular/cli
   ```
3. Build and deploy:
   ```bash
   ng build --configuration production
   ```

### Deploy to Netlify

1. Connect your GitHub repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist/personal-portfolio`

### Deploy to Vercel

1. Connect your GitHub repository to Vercel
2. Vercel will auto-detect Angular and configure settings
3. Deploy with default settings

## 📝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 📄 License

This project is open source and available under the MIT License. See the LICENSE file for details.

## 🤝 Support

For issues, questions, or suggestions, please open an GitHub issue or contact the maintainer.

---

**Made with ❤️ by [Your Name]**

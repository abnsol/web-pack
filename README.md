# Webpack Template

A basic Webpack configuration template designed to simplify the setup process for developers. This template-repository includes essential configuration files and provides an easy way to install dependencies, allowing you to focus on building your project.

## Features

- **Pre-configured Webpack**: Includes `webpack.common.js`, `webpack.dev.js`, and `webpack.prod.js` for streamlined development and production builds.
- **Essential Loaders and Plugins**: Easily install necessary dependencies using `npm run install-deps`.
- **Development Server**: Start a local development server with hot reloading.
- **Deployment Script**: Deploy your project to GitHub Pages with the `deploy` script.
- **ESLint and Prettier**: Integrated ESLint and Prettier configurations for consistent code quality and formatting.

## Why use this template?

This template-repository provides all essential configurations for any JavaScript project that requires Webpack. By using this template, you can:

- Save Time: Avoid the tedious process of setting up Webpack, ESLint, and Prettier from scratch.
- Stay Focused: Concentrate on building your project instead of managing configurations.
- Standardize Setup: Ensure consistency across multiple projects or team members.

## Getting Started

### Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/abnsol/web-pack.git
```

## Project Structure

- **src/**: Source files
  - **template.html**
- **webpack.common.js**: Common configuration
- **webpack.dev.js**: Development-specific configuration
- **webpack.prod.js**: Production-specific configuration
- **.eslintrc.js**: ESLint configuration
- **.prettierrc**: Prettier configuration
- **package.json**: Package configuration
- **.gitignore**: Ignore `node_modules` and `dist`
- **README.md**: Project documentation

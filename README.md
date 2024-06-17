# Astro Template

Welcome to the Astro Template repository! This template is designed to provide a solid starting point for developing modern, fast, and SEO-friendly websites using Astro, TypeScript, TailwindCSS, and other popular tools.

![Preview](https://raw.githubusercontent.com/pyyupsk/astro-template/main/.github/assets/preview.png)

## Table of Contents

- [Astro Template](#astro-template)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [Features](#features)
  - [Project Structure](#project-structure)
  - [Scripts](#scripts)
  - [Configuration](#configuration)
    - [ESLint](#eslint)
    - [Prettier](#prettier)
    - [Husky and Lint-Staged](#husky-and-lint-staged)
    - [TailwindCSS](#tailwindcss)
    - [TypeScript](#typescript)
  - [Contributing](#contributing)
  - [License](#license)

## Getting Started

To get started with this template, you'll need to have Node.js and PNPM installed on your machine.

1. **Clone the repository:**

   ```bash
   git clone https://github.com/pyyupsk/astro-template.git
   cd astro-template
   ```

2. **Install dependencies:**

   ```bash
   pnpm install
   ```

3. **Start the development server:**

   ```bash
   pnpm dev
   ```

   This will start the Astro development server and you can view the project at `http://localhost:3000`.

## Features

- **Astro**: Fast and modern static site generator.
- **TypeScript**: Type-safe JavaScript development.
- **TailwindCSS**: Utility-first CSS framework for rapid UI development.
- **ESLint**: Linting for JavaScript and TypeScript.
- **Prettier**: Code formatting.
- **Husky**: Git hooks for pre-commit and pre-push checks.
- **Lint-Staged**: Run linters on staged files.
- **Commitlint**: Lint commit messages.
- **Knip**: Analyze and remove unused files.

## Project Structure

```
astro-template/
├── .husky/                   # Husky hooks
├── public/                   # Static assets
├── src/                      # Source files
│   ├── components/           # Astro components
│   ├── layouts/              # Layout components
│   ├── pages/                # Pages
│   └── styles/               # Global styles
├── .eslintrc.cjs             # ESLint configuration
├── .gitignore                # Git ignore rules
├── .lintstagedrc.json        # Lint-Staged configuration
├── .prettierignore           # Prettier ignore rules
├── .prettierrc               # Prettier configuration
├── astro.config.mjs          # Astro configuration
├── package.json              # Project metadata and scripts
├── tailwind.config.mjs       # TailwindCSS configuration
└── tsconfig.json             # TypeScript configuration
```

## Scripts

- `pnpm dev`: Start the development server.
- `pnpm build`: Build the project for production.
- `pnpm preview`: Preview the production build.
- `pnpm format`: Check the formatting of your code.
- `pnpm format:fix`: Fix formatting issues.
- `pnpm lint`: Run ESLint on the source files.
- `pnpm knip`: Analyze the project for unused files.
- `pnpm knip:fix`: Remove unused files.

## Configuration

### ESLint

ESLint is configured to work with Astro and TypeScript. The configuration can be found in `.eslintrc.cjs`.

### Prettier

Prettier is used to ensure consistent code formatting. The configuration can be found in `.prettierrc`.

### Husky and Lint-Staged

Husky and Lint-Staged are used to run scripts on git hooks. The configurations are located in the `.husky` directory and `.lintstagedrc.json` file, respectively.

### TailwindCSS

TailwindCSS is configured in `tailwind.config.mjs`. You can customize the configuration to suit your project's needs.

### TypeScript

TypeScript configuration is found in `tsconfig.json`. It extends the default Astro strict configuration.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch with a descriptive name.
3. Make your changes.
4. Ensure all tests and checks pass.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for using the Astro Template! If you have any questions or feedback, feel free to open an issue or submit a pull request. Happy coding! 🚀

# React Webpack Boilerplate

A modern React boilerplate with Webpack configuration, TypeScript, ESLint, Prettier, and more.

## Features

- React 18 with TypeScript
- Webpack 5
- Babel configuration
- Hot Module Replacement (HMR)
- SCSS support
- ESLint + Prettier for code quality
- Husky + lint-staged for git hooks
- Development server
- Production build optimization

## Getting Started

1. Install dependencies:

```bash
npm install
```

2. Start development server:

```bash
npm start
```

3. Build for production:

```bash
npm run build
```

4. Lint your code:

```bash
npm run lint
```

5. Format your code:

```bash
npm run format
```

## Project Structure

```
├── public/
│   └── index.html
├── src/
│   ├── App.tsx
│   ├── index.tsx
│   └── styles.scss
├── .eslintrc.json
├── .prettierrc
├── package.json
├── tsconfig.json
├── webpack.config.js
└── README.md
```

## Available Scripts

- `npm start` - Starts the development server
- `npm run build` - Creates a production build
- `npm run lint` - Runs ESLint
- `npm run lint:fix` - Runs ESLint with auto-fix
- `npm run format` - Runs Prettier
- `npm test` - Runs tests (to be implemented)

## Code Quality Tools

- **TypeScript** - Static type checking
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Husky** - Git hooks
- **lint-staged** - Run linters on staged files

## Commit Message Convention

This project follows [Conventional Commits](https://www.conventionalcommits.org/) specification. Commit messages should be structured as follows:

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Types

- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc)
- `refactor`: Code changes that neither fix bugs nor add features
- `perf`: Performance improvements
- `test`: Adding or modifying tests
- `chore`: Changes to the build process or auxiliary tools
- `ci`: Changes to CI configuration files and scripts
- `revert`: Reverts a previous commit

### Examples

```
feat(auth): add login functionality
fix(api): handle null response from server
docs(readme): update installation instructions
style(components): format button styles
```

## License

MIT



# HRIS Frontend

This is a Human Resource Information System (HRIS) frontend application built with React, TypeScript, and Vite.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/adityanuriskandar17/HRIS-FE.git
cd HRIS-FE
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview the production build

## Commit Message Validation

This project uses Husky and commitlint to enforce conventional commit messages.

## Commit Message Format

Commits must follow the conventional commit format:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

## Commit Types

The following commit types are allowed:

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `build`: Changes that affect the build system or external dependencies
- `ci`: Changes to our CI configuration files and scripts
- `chore`: Other changes that don't modify src or test files
- `revert`: Reverts a previous commit

## Examples

```
feat: add user authentication
fix: resolve login issue on mobile devices
docs: update API documentation
refactor: simplify user service implementation
```

## Validation Rules

- Type must be one of the allowed types and in lowercase
- Subject cannot be empty
- Subject must not end with a period
- Subject must not be in start-case, pascal-case, or upper-case
- Header must not exceed 100 characters
- Body and footer lines must not exceed 100 characters
- Scope must be in lowercase if provided
# Contributing to OpenStudy Planner

Thank you for your interest in contributing to OpenStudy Planner! We welcome contributions from students, educators, developers, and anyone passionate about education technology.

## 🛠️ How to Contribute

### 1. Reporting Bugs

If you find a bug, please create a GitHub Issue using our "Bug Report" template. Include:
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable
- Your environment (browser, OS, etc.)

### 2. Suggesting Features

Have an idea for improving the study planner? Open an issue tagged `enhancement`. Describe:
- The feature you want to see
- Why it would help students
- Any implementation ideas you have

### 3. Pull Request (PR) Process

1. **Fork** the repository to your own GitHub account
2. **Clone** the project to your machine:
   ```bash
   git clone https://github.com/w0nsdoof/OpenStudy.git
   cd OpenStudy
   ```
3. Create a **new branch** for your feature:
   ```bash
   git checkout -b feature/amazing-new-feature
   ```
4. Make your changes and test thoroughly
5. Commit your changes with clear, descriptive messages:
   ```bash
   git commit -m "Add assignment reminder notifications"
   ```
6. Push to your branch:
   ```bash
   git push origin feature/amazing-new-feature
   ```
7. Create a **Pull Request** with a clear description of your changes

## 🏗️ Development Setup

1. Install dependencies:
   ```bash
   # Backend
   cd server && npm install

   # Frontend
   cd ../client && npm install
   ```

2. Set up your environment variables:
   ```bash
   cp server/.env.example server/.env
   # Edit .env with your configuration
   ```

3. Start the development servers:
   ```bash
   # Terminal 1 - Backend
   cd server && npm run dev

   # Terminal 2 - Frontend
   cd client && npm start
   ```

## 📝 Coding Standards

- **ESLint**: Our codebase uses ESLint for consistent style
- **Prettier**: Format your code before committing
- **Commit messages**: Use conventional commit format:
  - `feat:` for new features
  - `fix:` for bug fixes
  - `docs:` for documentation
  - `style:` for formatting changes
  - `refactor:` for code refactoring
  - `test:` for adding tests

## 🧪 Testing

Before submitting a PR, please ensure:
- All tests pass: `npm test`
- Your changes don't break existing functionality
- New features include appropriate tests
- The application builds successfully: `npm run build`

## 🎨 Design Contributions

If you're contributing to the UI/UX:
- Follow our design system and component library
- Ensure mobile responsiveness
- Test for accessibility (WCAG 2.1 AA)
- Consider dark mode support

## 📚 Documentation

Help us improve documentation by:
- Fixing typos or unclear explanations
- Adding examples and tutorials
- Translating documentation to other languages
- Creating video tutorials or walkthroughs

## 💬 Community

Join our community to discuss ideas and get help:
- GitHub Discussions: Ask questions and share ideas
- Discord: Chat with other contributors
- Twitter: Follow @OpenStudyPlanner for updates

## 🏆 Recognition

Contributors who make significant impacts will be:
- Featured in our README
- Invited to join our core team
- Eligible for contributor swag
- Recognized in our annual contributor report

## 📄 Licensing

By contributing to OpenStudy Planner, you agree that your contributions will be licensed under the MIT License.

Thank you for helping make education more accessible and organized for everyone! 🎓
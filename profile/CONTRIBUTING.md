# Contributing to Einsteini

Thank you for your interest in contributing to Einsteini! This document provides guidelines and information for contributors.

## 🌟 How to Contribute

### Reporting Issues
- Use the [issue templates](./.github/ISSUE_TEMPLATE/) to report bugs, request features, or ask questions
- Search existing issues before creating new ones
- Provide detailed information and steps to reproduce problems

### Submitting Changes
- Fork the repository
- Create a feature branch (`git checkout -b feature/amazing-feature`)
- Make your changes
- Commit your changes (`git commit -m 'Add amazing feature'`)
- Push to the branch (`git push origin feature/amazing-feature`)
- Open a Pull Request

## 🏗️ Project Structure

### einsteini-android (Flutter Mobile App)
- **Language**: Dart/Flutter
- **Architecture**: Clean Architecture with Riverpod state management
- **Key Features**: AI-powered LinkedIn assistant, overlay system, subscription management

### einsteini-backend (Node.js API)
- **Language**: JavaScript/Node.js
- **Framework**: Express.js
- **Database**: MongoDB
- **Key Features**: User management, AI processing, Stripe integration

### einsteini-dashboard (React Web App)
- **Language**: JavaScript/React
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Key Features**: Analytics dashboard, user management

### einsteini-extension (Chrome Extension)
- **Language**: JavaScript
- **Manifest**: V3
- **Key Features**: LinkedIn automation, content generation

## 🛠️ Development Setup

### Prerequisites
- Node.js 20+ (for backend, dashboard, extension)
- Flutter 3.6+ (for mobile app)
- Git

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/einsteiniai/.github.git
   cd .github
   ```

2. **Set up the mobile app**
   ```bash
   cd einsteini-android
   flutter pub get
   flutter run
   ```

3. **Set up the backend**
   ```bash
   cd einsteini-backend
   npm install
   npm start
   ```

4. **Set up the dashboard**
   ```bash
   cd einsteini-dashboard
   npm install
   npm run dev
   ```

5. **Set up the extension**
   ```bash
   cd einsteini-extension
   npm install
   # Load unpacked in Chrome Developer Mode
   ```

## 📝 Coding Standards

### General
- Use meaningful variable and function names
- Write clear, concise comments
- Follow the existing code style
- Add tests for new functionality

### Flutter/Dart
- Follow [Dart style guide](https://dart.dev/guides/language/effective-dart/style)
- Use `flutter format` for code formatting
- Run `flutter analyze` before committing

### JavaScript/Node.js
- Use ESLint for code linting
- Follow Airbnb JavaScript style guide
- Use Prettier for code formatting

### Git Commit Messages
Follow [Conventional Commits](https://www.conventionalcommits.org/):
- `feat: add new feature`
- `fix: resolve bug`
- `docs: update documentation`
- `test: add or update tests`
- `refactor: code refactoring`
- `chore: maintenance tasks`

## 🧪 Testing

### Running Tests
```bash
# Flutter tests
cd einsteini-android && flutter test

# Node.js tests
cd einsteini-backend && npm test

# React tests
cd einsteini-dashboard && npm test
```

### Test Coverage
- Aim for at least 80% test coverage
- Write unit tests for new functions
- Add integration tests for new features

## 📚 Documentation

- Update README.md files when adding features
- Add inline code documentation
- Update API documentation for backend changes
- Include screenshots for UI changes

## 🔐 Security

- Never commit API keys or sensitive data
- Use environment variables for configuration
- Follow security best practices
- Report security vulnerabilities privately

## 📄 License

By contributing, you agree that your contributions will be licensed under the same license as the project.

## 🤝 Community

- Be respectful and inclusive
- Help others learn and grow
- Follow the [Code of Conduct](./CODE_OF_CONDUCT.md)
- Participate in discussions and reviews

## 🆘 Getting Help

- Check the project documentation
- Search existing issues and discussions
- Ask questions in GitHub Discussions
- Contact the maintainers directly

## 🎯 Priority Areas

We especially welcome contributions in these areas:
- Bug fixes and performance improvements
- UI/UX enhancements
- Documentation improvements
- Test coverage expansion
- Accessibility improvements
- Internationalization/Localization

Thank you for contributing to Einsteini! 🚀

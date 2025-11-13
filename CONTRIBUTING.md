# Contributing to Engage360

Thank you for your interest in contributing to Engage360! 🎉

This document provides guidelines and instructions for contributing to the project. We welcome contributions from everyone, regardless of experience level.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Development Workflow](#development-workflow)
- [Coding Standards](#coding-standards)
- [Commit Guidelines](#commit-guidelines)
- [Pull Request Process](#pull-request-process)
- [Reporting Issues](#reporting-issues)
- [Feature Requests](#feature-requests)

## 📜 Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for all contributors.

### Our Standards

- Be respectful and considerate
- Welcome newcomers and help them learn
- Accept constructive criticism gracefully
- Focus on what is best for the community

## 🚀 Getting Started

1. **Fork the repository**
   ```bash
   # Click the "Fork" button on GitHub
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/Engage360.git
   cd Engage360
   ```

3. **Add the upstream remote**
   ```bash
   git remote add upstream https://github.com/soccertanuj/Engage360.git
   ```

4. **Install dependencies**
   ```bash
   npm install
   ```

5. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 💻 Development Workflow

### Running the Development Server

```bash
npm start
```

### Running on Specific Platforms

```bash
# iOS Simulator (macOS only)
npm run ios

# Android Emulator
npm run android

# Web Browser
npm run web
```

### Testing Your Changes

- Test on both iOS and Android if possible
- Ensure the app runs without errors
- Test the specific feature you're working on
- Check for any console warnings or errors

## 📝 Coding Standards

### Code Style

- Use **2 spaces** for indentation
- Use **single quotes** for strings (unless double quotes are needed)
- Use **camelCase** for variables and functions
- Use **PascalCase** for components
- Add comments for complex logic

### Component Structure

```javascript
import React from 'react';
import { View, Text, StyleSheet } from 'react-native';

export default function ComponentName() {
  // Component logic here
  
  return (
    <View style={styles.container}>
      <Text>Component content</Text>
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    // Styles here
  },
});
```

### File Naming

- Use **PascalCase** for component files: `Header.js`, `EventCard.js`
- Use **camelCase** for utility files: `helpers.js`, `apiClient.js`
- Use **lowercase** for constants files: `constants.js`

## 📦 Commit Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification.

### Commit Message Format

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Types

- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, missing semicolons, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

### Examples

```bash
feat(Home): Add daily quiz scoring system
fix(Events): Fix RSVP button not updating state
docs(README): Update installation instructions
style(Community): Format code with prettier
refactor(Navigation): Simplify tab navigator setup
```

## 🔀 Pull Request Process

1. **Update your fork**
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```

2. **Create your feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Write clean, readable code
   - Add comments where necessary
   - Test your changes thoroughly

4. **Commit your changes**
   ```bash
   git add .
   git commit -m "feat(Component): Add new feature"
   ```

5. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request**
   - Go to the original repository on GitHub
   - Click "New Pull Request"
   - Select your branch
   - Fill out the PR template
   - Submit the PR

### PR Checklist

- [ ] Code follows the project's style guidelines
- [ ] Self-review completed
- [ ] Comments added for complex code
- [ ] Documentation updated (if needed)
- [ ] No new warnings generated
- [ ] Tested on iOS/Android (if applicable)
- [ ] Changes tested and working

## 🐛 Reporting Issues

### Before Reporting

1. Check if the issue already exists
2. Search closed issues for similar problems
3. Ensure you're using the latest version

### Issue Template

When creating an issue, please include:

- **Description**: Clear description of the issue
- **Steps to Reproduce**: Detailed steps to reproduce the bug
- **Expected Behavior**: What should happen
- **Actual Behavior**: What actually happens
- **Screenshots**: If applicable
- **Environment**:
  - OS: [e.g., iOS 17.0, Android 13]
  - Device: [e.g., iPhone 14, Pixel 7]
  - Expo version: [e.g., ~53.0.17]
  - React Native version: [e.g., 0.79.5]

## 💡 Feature Requests

We welcome feature requests! When suggesting a feature:

1. Check if it's already been requested
2. Provide a clear description
3. Explain the use case
4. Consider implementation complexity

## 📚 Resources

- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [Expo Documentation](https://docs.expo.dev/)
- [React Navigation Documentation](https://reactnavigation.org/docs/getting-started)

## ❓ Questions?

If you have questions, feel free to:

- Open an issue with the `question` label
- Reach out to the maintainers

## 🙏 Thank You!

Your contributions make Engage360 better for everyone. Thank you for taking the time to contribute!

---

**Happy Coding! 🚀**


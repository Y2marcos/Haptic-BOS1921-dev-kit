# 🤝 Contributing to Haptic-BOS1921 Dev Kit

Thank you for your interest in contributing to the **Haptic-BOS1921 Dev Kit**! 🎉 We're excited to have you here and appreciate your help in making this project even better. Whether you're fixing a bug 🐛, improving documentation 📖, or adding new features 💡, your contributions are valued!

---

## 📜 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [PCB Design Improvements](#pcb-design-improvements)
  - [Documentation](#documentation)
  - [Hardware Testing](#hardware-testing)
- [Pull Request Process](#pull-request-process)
- [Style Guidelines](#style-guidelines)
- [Getting Help](#getting-help)

---

## 📏 Code of Conduct

This project and everyone participating in it is governed by our commitment to providing a welcoming and inclusive environment. By participating, you are expected to:

- **Be respectful** and considerate in your communication
- **Be collaborative** and open to feedback
- **Be patient** with others who may be learning
- **Focus on what is best** for the community and the project

We do not tolerate harassment, discriminatory language, or disrespectful behavior of any kind.

---

## 💡 How Can I Contribute?

### 🐛 Reporting Bugs

Found a bug? Help us fix it! Before creating a bug report, please check the [existing issues](https://github.com/Y2marcos/Haptic-BOS1921-dev-kit/issues) to avoid duplicates.

When reporting a bug, please include:

- **A clear, descriptive title**
- **Detailed description** of the issue
- **Steps to reproduce** the problem
- **Expected behavior** vs. actual behavior
- **Hardware specifications** (if applicable - board revision, component versions, etc.)
- **Photos or diagrams** if the issue is visual or hardware-related
- **Any relevant files** (Gerber files, schematics, etc.)

### ✨ Suggesting Enhancements

Have an idea to make this project better? We'd love to hear it! 

When suggesting enhancements, please:

- **Check existing issues** to see if it's already been suggested
- **Provide a clear description** of the enhancement
- **Explain why this enhancement would be useful** to most users
- **Include mockups, diagrams, or examples** if possible

### 🔧 PCB Design Improvements

Contributing to the hardware design? Here's what we're looking for:

- **Layout optimizations** for better signal integrity or manufacturability
- **Component substitutions** that improve performance, reduce cost, or increase availability
- **BOM updates** with verified, available components
- **Design rule check (DRC) fixes** and improvements
- **Schematic improvements** for clarity or functionality

When submitting PCB design changes:

1. **Document your changes** thoroughly in the pull request
2. **Update the BOM** if components have changed
3. **Update the Pick-and-Place file** if component positions have changed
4. **Export new Gerber files** if the layout has changed
5. **Update the schematic** to match any circuit changes
6. **Include a changelog** explaining what changed and why

### 📖 Documentation

Documentation is just as important as the hardware design! You can contribute by:

- **Fixing typos** and grammatical errors
- **Improving clarity** of existing documentation
- **Adding examples** of how to use the dev kit
- **Creating tutorials** or guides
- **Translating documentation** into other languages
- **Adding photos** or diagrams to clarify concepts

### 🧪 Hardware Testing

Built the dev kit? Share your experience!

- **Report build experiences** - what worked, what didn't
- **Share assembly tips** and tricks
- **Document component sourcing** challenges or alternatives
- **Test different configurations** and share results
- **Measure and report performance metrics**
- **Share application examples** and use cases

---

## 🚀 Pull Request Process

Ready to submit your contribution? Follow these steps:

1. **Fork the repository** and create your branch from `main`:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes** following our style guidelines

3. **Update documentation** if needed:
   - Update README.md if your changes affect usage
   - Update BOM if components changed
   - Update schematic if circuits changed
   - Include version numbers and dates in filenames

4. **Test your changes** if applicable:
   - Verify DRC passes (for PCB changes)
   - Check that all files are properly exported
   - Ensure Gerber files can be imported by manufacturers

5. **Commit your changes** with a clear, descriptive commit message:
   ```bash
   git commit -m "Add: Brief description of your changes"
   ```

6. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Open a Pull Request** with:
   - A clear title describing the change
   - Detailed description of what changed and why
   - Links to any related issues
   - Screenshots, photos, or diagrams if relevant
   - Any testing you've performed

8. **Wait for review** - maintainers will review your PR and may suggest changes

9. **Address feedback** if requested

10. **Celebrate!** 🎉 Once approved, your contribution will be merged!

---

## 🎨 Style Guidelines

### File Naming Conventions

- Use descriptive names with dates: `ComponentName_YYYY-MM-DD.ext`
- Keep filenames consistent with existing files
- Use underscores for spaces, not hyphens

### Documentation Style

- Use clear, friendly language
- Include emojis where appropriate (following README style)
- Use proper markdown formatting
- Include code blocks with syntax highlighting where applicable
- Add images with descriptive alt text

### PCB Design Standards

- Follow the [BOS1921 datasheet](https://www.boreas.ca) recommendations
- Maintain consistent trace widths and clearances
- Use appropriate layer stackup for the design
- Include proper grounding and power distribution
- Add test points where appropriate
- Label all connectors and important signals

### Commit Message Guidelines

Use clear, descriptive commit messages:

- **Add:** for new features or files
- **Update:** for changes to existing features
- **Fix:** for bug fixes
- **Docs:** for documentation changes
- **Refactor:** for code/design restructuring

Example: `Add: Alternative voltage regulator option to BOM`

---

## 🆘 Getting Help

Need help with your contribution?

- **Check the [README](./README.md)** for project information
- **Review existing [Issues](https://github.com/Y2marcos/Haptic-BOS1921-dev-kit/issues)** for similar questions
- **Open a new issue** with your question
- **Consult the [BOS1921 Datasheet](https://www.boreas.ca)** for technical details

---

## 🙏 Thank You!

Every contribution, no matter how small, helps make this project better. Whether you're fixing a typo or redesigning a circuit, we appreciate your time and effort! 

Happy contributing! 🚀✨

---

## 📝 License

By contributing to this project, you agree that your contributions will be licensed under the same [MIT License](./LICENSE) that covers the project.

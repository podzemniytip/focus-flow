# Contributing to Focus Flow

Thank you for considering contributing to Focus Flow! 🎉

## 🤝 How to Contribute

### Reporting Bugs

1. Check if the bug has already been reported in [Issues](https://github.com/YOUR_USERNAME/focus-flow/issues)
2. If not, create a new issue with:
   - Clear title
   - Steps to reproduce
   - Expected vs actual behavior
   - Device/browser info
   - Screenshots if applicable

### Suggesting Features

1. Check [existing discussions](https://github.com/YOUR_USERNAME/focus-flow/discussions)
2. Create a new discussion with:
   - Clear use case
   - Why it's valuable
   - Potential implementation ideas

### Code Contributions

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Test thoroughly on mobile device
5. Commit: `git commit -m "Add amazing feature"`
6. Push: `git push origin feature/amazing-feature`
7. Open a Pull Request

## 📝 Development Guidelines

### Code Style

- Use clear, descriptive variable names
- Add comments for complex logic
- Keep functions small and focused
- Follow existing code patterns

### Testing

Before submitting PR, test:
- ✅ Timer functionality (start, pause, reset, complete)
- ✅ Habits (add, toggle, streaks)
- ✅ Goals (add, complete, progress)
- ✅ Stats (calculations, charts)
- ✅ Dark mode toggle
- ✅ Data persistence (refresh page)
- ✅ Mobile responsiveness
- ✅ Touch interactions

### File Structure

```
focus-flow/
├── SKILL.md              # Don't change metadata structure
├── scripts/
│   └── index.html        # Background logic only
├── assets/
│   └── webview.html      # UI and interactions
└── README.md             # Keep updated
```

## 🎨 Design Guidelines

- Maintain gradient color scheme (primary: #6366f1, secondary: #ec4899)
- Ensure dark mode support for all new elements
- Keep mobile-first approach
- Use smooth transitions (0.3s ease)
- Test on small screens (320px width)

## 💾 Data Guidelines

- All localStorage keys must start with `focusFlow`
- Maintain backward compatibility with saved data
- Add migration logic if changing data structure
- Never lose user data

## 🐛 Bug Fix Checklist

- [ ] Bug reproduced
- [ ] Root cause identified
- [ ] Fix implemented
- [ ] Tested on device
- [ ] No new bugs introduced
- [ ] Code reviewed
- [ ] Documentation updated

## ✨ Feature Checklist

- [ ] Feature designed
- [ ] UI mockup (if visual)
- [ ] Code implemented
- [ ] Tested thoroughly
- [ ] Documentation added
- [ ] README updated
- [ ] CHANGELOG updated

## 📦 Pull Request Template

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing
- [ ] Tested on Android
- [ ] Tested on iOS
- [ ] Dark mode works
- [ ] No console errors
- [ ] Data persists correctly

## Screenshots
[Add if visual changes]

## Additional Notes
Any other context
```

## 🚀 Release Process

1. Update version in SKILL.md
2. Update CHANGELOG.md
3. Merge to main
4. Tag release: `git tag v1.1.0`
5. Push tag: `git push origin v1.1.0`
6. Create GitHub release with notes
7. Announce in discussions

## 💬 Communication

- Be respectful and constructive
- Ask questions if unclear
- Help others learn
- Celebrate contributions

## 📜 Code of Conduct

- Be kind and welcoming
- Respect different viewpoints
- Accept constructive criticism
- Focus on what's best for the community

## ⭐ Recognition

Contributors will be:
- Listed in README
- Mentioned in release notes
- Credited in CHANGELOG
- Part of an awesome project!

## 🎯 Priority Areas

Help needed with:
1. **Testing** - More devices, edge cases
2. **Documentation** - Tutorials, examples
3. **Features** - See GitHub issues
4. **Bug fixes** - Check issue tracker
5. **Localization** - Multi-language support

## 📚 Resources

- [Google AI Edge Gallery Docs](https://github.com/google-ai-edge/gallery/tree/main/skills)
- [JavaScript Best Practices](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [Web APIs](https://developer.mozilla.org/en-US/docs/Web/API)

---

**Thank you for making Focus Flow better! 🙏**

Questions? Open a discussion or contact maintainers.

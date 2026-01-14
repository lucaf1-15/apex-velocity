# Contributing to Apex Velocity Template

First off, thanks for taking the time to contribute! 🎉🏁

This template is FREE and open for community improvements. Every contribution helps make it better for racing teams worldwide.

---

## 🚀 Quick Start for Contributors

1. **Fork the repository**
2. **Clone your fork:** `git clone https://github.com/yourusername/apex-velocity.git`
3. **Create a branch:** `git checkout -b feature/your-feature-name`
4. **Make your changes**
5. **Test thoroughly**
6. **Commit:** `git commit -m 'Add some feature'`
7. **Push:** `git push origin feature/your-feature-name`
8. **Open a Pull Request**

---

## 📋 Ways to Contribute

### 🐛 Report Bugs
Found something broken? Help us fix it!

**Before reporting:**
- Check if it's already reported in [Issues](https://github.com/yourusername/apex-velocity/issues)
- Test in multiple browsers
- Check if you're using the latest version

**When reporting, include:**
- Clear description of the bug
- Steps to reproduce
- Expected vs actual behavior
- Browser and OS info
- Screenshots if relevant
- Code snippets if applicable

### ✨ Suggest Features
Have an idea? We'd love to hear it!

**Before suggesting:**
- Check existing feature requests
- Consider if it fits the template's purpose
- Think about backward compatibility

**When suggesting, include:**
- Clear description of the feature
- Why it would be useful
- How it might work
- Mockups/examples if possible

### 🔧 Submit Code
Want to fix bugs or add features? Awesome!

**Before coding:**
- Discuss major changes in an issue first
- Follow the code style guide (below)
- Test your changes thoroughly
- Update documentation if needed

### 📝 Improve Documentation
Documentation is just as important as code!

**You can help by:**
- Fixing typos or unclear instructions
- Adding examples
- Improving explanations
- Translating (future feature)

---

## 💻 Development Setup

### Prerequisites
- Text editor (VS Code recommended)
- Web browser (Chrome recommended for dev tools)
- Basic HTML/CSS/JS knowledge
- Git

### Local Setup
```bash
# Clone your fork
git clone https://github.com/yourusername/apex-velocity.git

# Navigate to directory
cd apex-velocity

# Open in browser
open index.html

# Or use local server (recommended)
python -m http.server 8000
# Visit http://localhost:8000
```

### Testing Your Changes
1. Test in multiple browsers (Chrome, Firefox, Safari, Edge)
2. Test responsive design (mobile, tablet, desktop)
3. Check all navigation links work
4. Verify animations are smooth
5. Test form validation
6. Check for console errors (F12)

---

## 📐 Code Style Guide

### HTML
```html
<!-- Use semantic HTML5 tags -->
<section class="section">
  <div class="container">
    <!-- Clear, descriptive class names -->
    <h2 class="section-title">Title</h2>
  </div>
</section>

<!-- Proper indentation (2 spaces) -->
<!-- Self-closing tags for void elements -->
<img src="image.jpg" alt="Description">

<!-- Meaningful alt text -->
<!-- Lowercase attributes -->
```

### CSS
```css
/* Organize by component */
/* Use BEM-inspired naming */
.component {}
.component-element {}
.component--modifier {}

/* Group related properties */
.example {
  /* Positioning */
  position: relative;
  top: 0;
  
  /* Box model */
  display: flex;
  width: 100%;
  padding: 1rem;
  
  /* Typography */
  font-family: var(--font-body);
  font-size: 1rem;
  
  /* Visual */
  background: var(--color-primary);
  color: var(--color-light);
  
  /* Misc */
  transition: all 0.3s ease;
}

/* Use CSS variables for theme values */
/* Comment complex selectors */
/* Mobile-first media queries */
```

### JavaScript
```javascript
/* Use modern ES6+ syntax */
const myFunction = () => {
  // Clear, descriptive names
  // Comment complex logic
  // Handle errors gracefully
};

/* Modular functions */
/* Avoid global scope pollution */
/* Use const/let, not var */

// Event listeners in separate functions
function initNavigation() {
  const nav = document.querySelector('.nav');
  // ...
}
```

### Naming Conventions
- **HTML/CSS Classes:** `kebab-case` (e.g., `hero-title`)
- **JavaScript Variables:** `camelCase` (e.g., `navToggle`)
- **CSS Variables:** `--kebab-case` (e.g., `--color-primary`)
- **File Names:** `kebab-case` (e.g., `contact-form.js`)

---

## 🎯 Contribution Guidelines

### Do's ✅
- **Test thoroughly** before submitting
- **Follow the code style** of the existing code
- **Update documentation** if you change functionality
- **Keep commits atomic** (one feature per commit)
- **Write clear commit messages**
- **Be respectful** in discussions
- **Ask questions** if unsure

### Don'ts ❌
- **Don't add frameworks** (keep it vanilla)
- **Don't break backward compatibility** without discussion
- **Don't add unnecessary dependencies**
- **Don't submit untested code**
- **Don't change the core license terms**
- **Don't remove existing attribution**

---

## 📝 Commit Message Format

Use clear, descriptive commit messages:

### Format
```
<type>: <subject>

<body (optional)>

<footer (optional)>
```

### Types
- **feat:** New feature
- **fix:** Bug fix
- **docs:** Documentation changes
- **style:** Code style changes (formatting, no logic change)
- **refactor:** Code refactoring
- **test:** Adding tests
- **chore:** Maintenance tasks

### Examples
```
feat: Add dark mode toggle

Implemented dark/light mode switcher in navigation.
Saves user preference to localStorage.

fix: Correct mobile menu z-index issue

Mobile menu was appearing behind hero section.
Updated z-index to 1000 to fix overlap.

docs: Update installation instructions

Added section on local server setup for development.

style: Format CSS with consistent spacing

Ran code through Prettier for consistent formatting.
No functional changes.
```

---

## 🔄 Pull Request Process

### Before Submitting
1. ✅ Update your fork with latest main branch
2. ✅ Test all changes thoroughly
3. ✅ Update documentation if needed
4. ✅ Add yourself to CONTRIBUTORS.md (if not there)
5. ✅ Ensure no merge conflicts

### PR Title Format
Follow commit message format:
- `feat: Add new feature`
- `fix: Correct bug`
- `docs: Update guide`

### PR Description Template
```markdown
## Description
Brief description of what this PR does

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Code refactoring
- [ ] Other (please describe)

## Changes Made
- List specific changes
- Be detailed but concise

## Testing Done
- Describe how you tested
- List browsers tested
- Note any edge cases checked

## Screenshots (if applicable)
Add screenshots for UI changes

## Checklist
- [ ] Code follows style guidelines
- [ ] Documentation updated
- [ ] Tested in multiple browsers
- [ ] No console errors
- [ ] Responsive design works
- [ ] Backward compatible

## Additional Notes
Any other relevant information
```

### Review Process
1. Maintainer will review within ~1 week
2. May request changes or clarification
3. Make requested changes
4. Once approved, will be merged
5. Your contribution will be in the next release!

---

## 🏆 Recognition

Contributors are recognized in multiple ways:

1. **CONTRIBUTORS.md** - Your name added to contributors list
2. **GitHub Contributors** - Automatic recognition on GitHub
3. **Release Notes** - Mentioned in changelog for significant contributions
4. **Social Media** - Major contributors may be shouted out

---

## 🤔 Questions?

Not sure about something? Here's how to get help:

- 💬 **GitHub Discussions:** Best for general questions
- 🐛 **GitHub Issues:** For specific bugs or features
- 📧 **Email:** your.email@example.com (for sensitive matters)

**No question is too small!** Everyone was a beginner once.

---

## 📜 Code of Conduct

### Our Pledge
We pledge to make participation in our project a harassment-free experience for everyone, regardless of:
- Age, body size, disability
- Ethnicity, gender identity
- Experience level
- Nationality, race, religion
- Sexual identity and orientation

### Our Standards
**Positive behavior includes:**
- Being respectful and inclusive
- Accepting constructive criticism
- Focusing on what's best for the community
- Showing empathy toward others

**Unacceptable behavior includes:**
- Harassment or discriminatory comments
- Trolling or insulting comments
- Personal or political attacks
- Publishing others' private information

### Enforcement
Instances of unacceptable behavior may be reported to [your.email@example.com]. All complaints will be reviewed and investigated.

---

## 🙏 Thank You!

Every contribution, no matter how small, helps make this template better for the entire racing community.

**You're awesome for contributing!** 🏁🚀

---

## 📚 Additional Resources

- [HTML Best Practices](https://github.com/hail2u/html-best-practices)
- [CSS Guidelines](https://cssguidelin.es/)
- [JavaScript Style Guide](https://github.com/airbnb/javascript)
- [Semantic Versioning](https://semver.org/)
- [Keep a Changelog](https://keepachangelog.com/)

---

**Happy Contributing! 🎉**

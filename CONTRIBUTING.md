# Contributing to LUCA

Thank you for your interest in contributing to the LUCA Free License project!

## How to Contribute

Since this project is licensed under LUCA v1.0, you can **DO WHAT THE FUCK YOU WANT TO** with it. But here are some guidelines if you want to contribute back to the official repository:

### Ways to Contribute

1. **Improve Documentation**
   - Fix typos or unclear explanations
   - Add examples
   - Translate to other languages
   - Improve website design

2. **Share Feedback**
   - Report issues with the license text
   - Suggest improvements
   - Share use cases
   - Provide legal analysis

3. **Spread the Word**
   - Use LUCA in your projects
   - Write blog posts about LUCA
   - Share LUCA on social media

### Submitting Changes

1. Fork the repository
2. Make your changes
3. Submit a pull request

That's it! No CLA, no complicated process.

### Development Workflow

#### Setting Up Development Environment

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/LUCA.git
   cd LUCA
   ```
3. Add upstream remote:
   ```bash
   git remote add upstream https://github.com/druvx13/LUCA.git
   ```

#### Making Changes

1. Create a branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Make your changes
3. Test your changes (see Testing Guidelines below)
4. Commit with clear messages:
   ```bash
   git commit -m "Add: Brief description of change"
   ```
5. Push to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a pull request

#### Pull Request Guidelines

- **Clear Title**: Describe what the PR does
- **Description**: Explain why this change is needed
- **Small Commits**: Keep changes focused and atomic
- **Test**: Ensure documentation renders correctly
- **Links**: Reference related issues if applicable

### Testing Guidelines

Since this is a documentation project, testing means:

1. **Markdown Validation**
   - Ensure all markdown renders correctly
   - Check links are valid
   - Verify code blocks have proper syntax highlighting

2. **Website Testing** (if modifying docs/ folder)
   - Test HTML renders properly
   - Check responsive design on mobile
   - Verify all links work
   - Test in multiple browsers

3. **Content Review**
   - Check for typos and grammar
   - Ensure consistency with existing docs
   - Verify accuracy of technical information
   - Test example code snippets

#### Running Local Website

To test the website locally:

```bash
# Python SimpleHTTPServer
cd docs
python -m http.server 8000
# Visit http://localhost:8000

# Or with Node.js
npx http-server docs -p 8000
```

### Style Guide

#### Markdown Style

- Use ATX-style headers (`#` not underlines)
- Use `**bold**` for emphasis
- Use ` ``` ` for code blocks with language specifier
- Keep line length reasonable (80-100 chars when possible)
- Use consistent emoji (✅ ❌ 💡 🚀 etc.)

#### Writing Style

- **Clear**: Write for clarity, not cleverness
- **Concise**: Be brief but complete
- **Consistent**: Match existing documentation tone
- **Inclusive**: Use welcoming, inclusive language
- **Professional**: Keep profanity to the license text itself

#### Code Examples

- **Complete**: Show full, working examples
- **Commented**: Add comments explaining non-obvious parts
- **Tested**: Verify examples actually work
- **Diverse**: Cover multiple languages/platforms

#### File Structure

```
LUCA/
├── *.md              # Markdown documentation
├── COPYING           # License text
└── docs/             # Website files
    ├── *.html        # Web pages
    ├── style.css     # Styling
    └── *.xml/txt     # Meta files
```

### Code of Conduct

Be respectful. That's all we ask.

### Questions?

Open an issue or start a discussion on GitHub.

### Review Process

1. **Automated Checks**: PRs may run automated link checkers
2. **Review**: Maintainer reviews changes for accuracy and consistency
3. **Feedback**: Address any requested changes
4. **Merge**: Once approved, PR is merged
5. **Website**: Changes automatically deploy to GitHub Pages

### Contribution Ideas

Not sure what to contribute? Here are some ideas:

- **Documentation Improvements**
  - Fix typos or grammar
  - Add missing examples
  - Clarify confusing sections
  - Add diagrams or illustrations

- **Translations**
  - Translate docs to other languages
  - Review existing translations
  - Create language-specific examples

- **Examples**
  - Real-world project examples
  - Integration guides
  - Platform-specific instructions

- **Website**
  - Improve styling
  - Add interactive features
  - Enhance mobile experience
  - SEO improvements

- **Community**
  - Share LUCA with others
  - Write blog posts
  - Create tutorials
  - Answer questions in issues

### Recognition

Contributors are recognized in:
- GitHub contribution graphs
- Pull request history
- Community discussions

We don't maintain a separate CONTRIBUTORS file since LUCA is about freedom, not attribution requirements.

## License

All contributions to this project are automatically licensed under LUCA v1.0.

By contributing, you agree that your contributions will be licensed under the same license.

---

**DO WHAT THE FUCK YOU WANT TO.**

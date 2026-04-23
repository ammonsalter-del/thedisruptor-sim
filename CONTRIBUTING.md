# Contributing to The Disruptor

Thank you for your interest in contributing to The Disruptor! This project is open source under CC BY-NC-SA 4.0, and we welcome contributions from educators, developers, and students.

## Ways to Contribute

### Report Bugs
Found something that doesn't work as expected? Please open an issue using the bug report template. Include:
- A clear description of the problem
- Steps to reproduce the issue
- Expected vs actual behaviour
- Your browser and operating system
- Screenshots if helpful

### Suggest Features
Have an idea for improving the game? Open an issue using the feature request template or start a discussion. We're particularly interested in:
- New company scenarios or industry variants
- Accessibility improvements
- Educational enhancements (teaching tools, assessment features)
- Localisation for different countries or innovation ecosystems
- Teacher/research tools and dashboards

### Submit Code
We welcome pull requests for bug fixes, new features, and improvements. Please:

1. **Fork the repository** and create your branch from `main`
2. **Test your changes** thoroughly in multiple browsers
3. **Follow the existing code style** (the game is written as a single HTML file with embedded CSS and JavaScript)
4. **Write clear commit messages** explaining what and why
5. **Update documentation** if your changes affect how the game works
6. **Submit a pull request** with a clear description of your changes

### Create Adaptations
Under the license, you're free to create your own versions of the game. If you create something interesting — a new company scenario, a translation, a variant for a different industry or institutional context — open a Discussion on GitHub so the community can see it.

### Improve Documentation
Help us improve the README, FAQ, Teaching Guide, or other documentation. Clear documentation helps everyone.

### Share Your Experience
Using the game in your teaching? Post your experiences, lesson plans, or student feedback in the GitHub Discussions section so other educators can learn from them.

## Development Guidelines

### Code Structure
The game is intentionally built as a single HTML file for maximum portability — it can be downloaded and played offline without any build process or dependencies. Please maintain this architecture unless there's a compelling reason to change it.

The file is large (~116,000 lines) and organised into clearly commented sections. Use the section markers (e.g., `// ═══ Section Name ═══`) to navigate.

### Testing
Before submitting changes, please test:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android) if possible

Pay particular attention to:
- The quarterly cycle (advance through several quarters to verify nothing breaks)
- The R&D pipeline and stage-gate process
- Alliance and CVC interactions
- The board review and year-end sequences
- Mini-games (Design Thinking Pinball, Lead User Patrol, Wellness Ecosystem Chase)

### Style Guide
- Use clear, descriptive variable and function names
- Comment complex logic
- Keep functions focused and reasonably sized
- Maintain consistent indentation (4 spaces)
- Use British English spelling in user-facing text (to match the existing content)
- Follow the 21 Design Principles documented in the game — particularly Principle 2 (Causal Ambiguity) when adding new gameplay mechanics

### Commit Messages
Write clear commit messages that explain what changed and why:
```
Add sustainability scoring to board review

- Board now evaluates EcoFit line performance as part of annual review
- Connects to Foundation mission alignment metric
- Threshold set at 3/5 to trigger positive Foundation feedback
```

## Pull Request Process

1. Ensure your code works correctly and doesn't break existing functionality
2. Update the README or other documentation if needed
3. Add yourself to the Contributors list if this is your first contribution
4. Submit the pull request with a clear description
5. Respond to any feedback from reviewers

## Community Guidelines

- Be respectful and constructive in all interactions
- Welcome newcomers and help them get started
- Focus on the work, not the person
- Assume good intentions
- Give credit where it's due

## Questions?

If you're unsure about anything, please ask in the Discussions section before investing significant time. We're happy to provide guidance on whether a contribution would be welcome and how best to approach it.

## License

By contributing to this project, you agree that your contributions will be licensed under the same CC BY-NC-SA 4.0 license that covers the project.

Thank you for helping make The Disruptor better!

# Contributing to Microsoft 365 Copilot Custom Agents

First off, thank you for considering contributing to this project! It's people like you that make this such a great project.

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issues list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps which reproduce the problem**
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed after following the steps**
- **Explain which behavior you expected to see instead and why**
- **Include screenshots and animated GIFs if possible**

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

- **Use a clear and descriptive title**
- **Provide a step-by-step description of the suggested enhancement**
- **Provide specific examples to demonstrate the steps**
- **Describe the current behavior and why it needs improvement**
- **List some other applications where this enhancement exists**

### Pull Requests

- Fill in the required template
- Follow the Python/Markdown styleguides
- End all files with a newline
- Avoid platform-dependent code

## Styleguides

### Prompt Engineering Guidelines

When modifying agent prompts:

1. **Clarity**: Prompts should be clear and unambiguous
2. **Structure**: Use logical sections and formatting
3. **Examples**: Include examples when helpful
4. **Context**: Provide sufficient context for the LLM to understand the task
5. **Testing**: Test thoroughly before submitting

### Documentation Styleguide

- Use clear, simple language
- Include code examples where relevant
- Use proper markdown formatting
- Keep lines to a reasonable length
- Include a table of contents for longer documents

### Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

Example:
```
Add Email Assistant Agent prompt v2.1

This prompt-based agent helps rewrite emails and messages into
professional business English tailored to Indian MNC standards.

Fixes #123
```

## Getting Started

### Setting up your local environment

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR-USERNAME/Microsoft365-Copilot-Custom-Agents.git`
3. Create a new branch: `git checkout -b my-new-feature`
4. Make your changes
5. Test thoroughly
6. Commit your changes: `git commit -am 'Add new feature'`
7. Push to the branch: `git push origin my-new-feature`
8. Submit a pull request

### Testing

Before submitting a pull request, please test your changes:

1. **For prompt changes**: Test in Copilot Studio with various inputs
2. **For documentation**: Check formatting and clarity
3. **For code changes**: Ensure no breaking changes

## Project Structure

```
Microsoft365-Copilot-Custom-Agents/
├── README.md                           # Project overview
├── SETUP_GUIDE.md                      # Deployment guide
├── CONTRIBUTING.md                     # This file
├── LICENSE                             # MIT License
├── Email_Assistant_Ak_2.1.txt         # Email Agent prompt
└── Universal_SQL_Developer_Agent.txt  # SQL Agent prompt
```

## Types of Contributions

### Bug Fixes
- Identify and fix issues in agent prompts
- Improve documentation clarity
- Enhance setup instructions

### Feature Requests
- New agent capabilities
- Enhanced documentation
- New integration examples

### Improvements
- Optimize agent prompts
- Expand support for more SQL dialects
- Add more comprehensive examples
- Improve error handling guidance

## Recognition

Contributors will be recognized in:
- Project README (Acknowledgments section)
- Release notes
- GitHub contributors page

## Questions?

Feel free to open an issue with the label "question" if you need clarification on anything.

## Additional Notes

### Issue and Pull Request Labels

- `bug` - Something isn't working
- `enhancement` - New feature or request
- `documentation` - Improvements or additions to documentation
- `good first issue` - Good for newcomers
- `help wanted` - Extra attention is needed

## Licensing

By contributing to this project, you agree that your contributions will be licensed under its MIT License.

---

Thank you for contributing! 🎉

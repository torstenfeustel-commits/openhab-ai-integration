# Contributing to OpenHAB AI Integration

Thank you for considering contributing! This project was born from collaboration between a frustrated smart home user and Claude AI. We welcome contributions from the community.

## 🤝 Ways to Contribute

### 1. Report Bugs

Found a bug? Please open an issue with:
- **Clear title**: "Device X not recognized" 
- **Description**: What you expected vs what happened
- **Environment**: 
  - OpenHAB version
  - OpenWebUI version
  - LLM model used
- **Logs**: Any error messages
- **Steps to reproduce**

### 2. Suggest Features

Have an idea? Open an issue with:
- **Use case**: Why this feature would be useful
- **Example**: How it would work in practice
- **Impact**: Who would benefit

### 3. Improve Documentation

- Fix typos or unclear instructions
- Add examples or use cases
- Translate to other languages
- Create video tutorials

### 4. Code Contributions

#### Getting Started

1. **Fork the repository**
2. **Create a branch**: `git checkout -b feature/your-feature-name`
3. **Make changes**
4. **Test thoroughly**
5. **Submit pull request**

#### Code Standards

- **Python**: Follow PEP 8
- **Comments**: Explain *why*, not *what*
- **Error handling**: Always include try/except
- **Logging**: Use appropriate log levels

#### Testing Checklist

Before submitting:
- [ ] Tested with OpenHAB 4.x
- [ ] Tested with OpenHAB 5.x
- [ ] Tested with qwen3
- [ ] Tested with at least 50+ devices
- [ ] Error messages are clear
- [ ] No breaking changes to existing functionality

### 5. Share Your Setup

Help others by sharing:
- **Screenshots** of interesting AI responses
- **Automation ideas** using the integration
- **Performance benchmarks** with different models
- **Blog posts** about your experience

## 📋 Pull Request Process

1. **Update documentation** if behavior changes
2. **Add examples** for new features
3. **Keep commits atomic**: One feature/fix per commit
4. **Write clear commit messages**:
   ```
   Fix: Device control timeout for slow networks
   
   - Increased timeout from 10s to 15s
   - Added retry logic for transient failures
   - Improved error messages
   ```
5. **Reference issues**: "Fixes #123" or "Relates to #456"

## 🐛 Bug Fix Priority

1. **Critical**: Data loss, security issues, crashes
2. **High**: Major features broken
3. **Medium**: Minor features broken, poor UX
4. **Low**: Cosmetic issues, small improvements

## 🎨 Feature Request Evaluation

We evaluate features based on:
- **User benefit**: How many users need this?
- **Complexity**: Implementation effort required
- **Maintenance**: Long-term support burden
- **Scope**: Does it fit the project's goals?

## 💬 Communication

- **GitHub Issues**: Bug reports, feature requests
- **GitHub Discussions**: Questions, ideas, show-and-tell
- **Pull Requests**: Code contributions

## 🙏 Recognition

Contributors will be:
- Listed in README
- Credited in release notes
- Given our eternal gratitude 😊

## 📜 Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inspiring community for everyone.

### Our Standards

**Positive behavior**:
- Using welcoming and inclusive language
- Being respectful of differing viewpoints
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

**Unacceptable behavior**:
- Trolling, insulting/derogatory comments, and personal attacks
- Public or private harassment
- Publishing others' private information without permission
- Other conduct which could reasonably be considered inappropriate

### Enforcement

Instances of unacceptable behavior may result in:
1. Warning
2. Temporary ban
3. Permanent ban

Report to: [maintainer email]

## 🚀 Development Setup

```bash
# Clone your fork
git clone https://github.com/yourusername/openhab-ai-integration.git
cd openhab-ai-integration

# Create development environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install development dependencies
pip install -r requirements-dev.txt

# Run tests
python -m pytest tests/

# Format code
black openhab_tool.py

# Lint
pylint openhab_tool.py
```

## 📚 Resources

- [OpenHAB REST API Docs](https://www.openhab.org/docs/configuration/restdocs.html)
- [OpenWebUI Tools Guide](https://docs.openwebui.com/tutorials/tools/)
- [Ollama Model Library](https://ollama.com/library)

## ❓ Questions?

Not sure how to contribute? Open a discussion! No question is too small.

---

**Thank you for helping make smart homes smarter! 🏡🤖**

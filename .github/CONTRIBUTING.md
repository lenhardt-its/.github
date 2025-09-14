# Contributing to lenhardt-its Ansible Roles

Thank you for your interest in contributing to our Ansible roles! This document provides guidelines for contributing to any of our ansible-role-* repositories.

## 🚀 Getting Started

1. **Fork the repository** you want to contribute to
2. **Create a feature branch** from `main`
3. **Make your changes** following our guidelines below
4. **Test your changes** thoroughly
5. **Submit a pull request**

## 📋 Contribution Guidelines

### Code Style
- Follow [Ansible best practices](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html)
- Use descriptive variable names
- Include comments for complex logic
- Maintain consistent indentation (2 spaces for YAML)

### Commit Messages
- Use conventional commit format: `type(scope): description`
- Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`
- Keep the first line under 72 characters
- Include detailed description if needed

### Testing
- Test on supported platforms listed in `meta/main.yml`
- Ensure all existing tests continue to pass
- Add tests for new functionality when applicable

### Documentation
- Update README.md if adding new features
- Document all variables in `defaults/main.yml`
- Include usage examples where helpful

## 🐛 Reporting Issues

Please use our issue templates when reporting bugs or requesting features. Provide as much detail as possible including:
- Operating system and version
- Ansible version
- Role configuration
- Error messages and logs

## 📧 Contact

- **Email**: dominik@lenhardt-it.com
- **Website**: https://lenhardt-it.com

## 📄 License

All our Ansible roles are licensed under the MIT License. By contributing, you agree that your contributions will be licensed under the same license.

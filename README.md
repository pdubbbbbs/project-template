# Project Template Repository

This is a standardized template repository that enforces code quality standards and best practices across all projects. Use this template when creating new repositories to ensure consistent quality and structure.

## Features

- 🔍 Automated quality checks
- 📝 Standardized PR process
- 📚 Documentation requirements
- ✅ Test coverage enforcement
- 🏗️ Required project structure
- 🔒 Branch protection rules

## Usage

### Creating a New Project

1. Click the "Use this template" button at the top of this repository
2. Name your new repository
3. Choose public or private visibility
4. Click "Create repository from template"

### Required Structure

Your project must maintain the following structure:

```
.
├── .github/
│   ├── workflows/          # GitHub Actions workflows
│   └── PULL_REQUEST_TEMPLATE.md
├── docs/                   # Project documentation
├── src/                    # Source code (for code projects)
├── tests/                  # Test files (for code projects)
└── README.md              # Project documentation
```

### Quality Standards

This template enforces:

1. **Code Quality**
   - No direct commits to main branch
   - PR description requirements
   - Required file structure
   - Test coverage requirements

2. **Documentation**
   - Comprehensive README
   - API documentation (if applicable)
   - Usage examples
   - Setup instructions

3. **Pull Requests**
   - Detailed description
   - Type of change
   - Testing instructions
   - Impact assessment
   - Related issues
   - Screenshots (if applicable)

## Customization

While this template provides a strong foundation, you can customize it for your specific needs:

1. Modify `.github/workflows/quality-checks.yml` for project-specific checks
2. Update PR template requirements in `.github/PULL_REQUEST_TEMPLATE.md`
3. Add additional documentation requirements in `/docs`

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Support

For questions or issues with this template, please open an issue in the repository.

## License

Copyright (c) 2025 Philip S. Wright

This template is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

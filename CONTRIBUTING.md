# Contributing to All Frontend Projects

Thank you for your interest in this frontend collection! This guide will help you understand how to add and organize projects in this repository.

## Adding a New Project

### 1. Choose the Right Location

- **Full Projects**: Add to the `projects/` directory
- **Reusable Templates**: Add to the `templates/` directory
- **Shared Components**: Add to the `components/` directory
- **Documentation**: Add to the `docs/` directory

### 2. Project Structure

Each project should follow this structure:

```
project-name/
├── README.md              # Required: Project documentation
├── src/                   # Source code directory
├── public/                # Public assets (images, icons, etc.)
├── package.json          # Dependencies (if using npm/yarn)
├── index.html            # Entry point (for static sites)
└── [other config files]  # .prettierrc, .eslintrc, etc.
```

### 3. Required README Content

Each project's README.md must include:

```markdown
# Project Name

Brief description of what this project does.

## 🎯 Features

- Feature 1
- Feature 2
- Feature 3

## 🛠️ Technologies Used

- Technology 1
- Technology 2
- Framework/Library

## 🚀 Getting Started

### Prerequisites

List any prerequisites needed.

### Installation

\`\`\`bash
# Installation commands
npm install
\`\`\`

### Running the Project

\`\`\`bash
# Run commands
npm start
\`\`\`

## 📸 Screenshots

[Add screenshots or demo GIFs here]

## 📝 License

Specify the license for this project.
```

### 4. Code Quality

- Write clean, readable code
- Add comments where necessary
- Follow consistent naming conventions
- Include proper error handling

### 5. Testing

- Test your project before adding it
- Ensure all links and assets work correctly
- Verify responsive design (if applicable)

### 6. Update Main README

After adding your project, update the main README.md to include:
- Project name and description
- Link to the project directory
- Key technologies used

## Project Naming Conventions

- Use lowercase with hyphens: `my-project-name`
- Be descriptive but concise
- Avoid special characters

## Commit Messages

Follow conventional commit format:

```
feat: Add new calculator project
fix: Correct responsive layout in header
docs: Update project installation instructions
style: Format code in navigation component
```

## Questions?

Feel free to open an issue if you need help or have questions!

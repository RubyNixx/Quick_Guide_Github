**Methods of working with Git**

*Command Line Interface (CLI)*

Some developers prefer using Git on the command line for several reasons:

- Full control: The CLI offers direct access to all Git commands and features, making it suitable for complex and customized workflows
- Speed: For experienced users, the CLI can be faster for common tasks
- Scripting and automation: The CLI is scriptable, enabling developers to automate repetitive tasks
- Better understanding: Using the CLI helps developers truly understand Git's underlying concepts and operations

*Browser-based Interface*

Others prefer using Git via a browser interface (like GitHub's web interface) because:

- Simplicity: It's more intuitive for beginners and requires no local setup
- Accessibility: It can be accessed from any device with a web browser
- Quick edits: For small changes or when working on unfamiliar machines, it's convenient

*Git GUI Applications (e.g., GitHub Desktop)*

Many users opt for Git GUI applications due to:

- Visual representation: GUIs provide a graphical view of the repository structure and history
- User-friendly interface: They offer intuitive interfaces for common Git operations
- Integration: Some GUIs integrate with issue tracking and other development tools

Ultimately, the choice depends on personal preference, project requirements, and the user's level of Git expertise. Many developers use a combination of these methods, selecting the most appropriate tool for each task.

**Creating a Repository from a Template**

1. Navigate to the main page of the template repository on GitHub.com.
2. Click the "Use this template" button near the top-right of the page.
3. Select "Create a new repository" from the dropdown menu.
4. Choose the owner of the new repository from the "Owner" dropdown menu.
5. Enter a name for your new repository.
6. Optionally, add a description for your repository.
7. Choose the repository visibility (Public or Private). Consider 'everyone'.
8. If desired, select "Include all branches" to copy all branches from the template, not just the default branch.
9. Click "Create repository from template".

**Creating a Pull Request Template**

1. In your repository, create a new file named PULL_REQUEST_TEMPLATE.md.
2. Place this file in one of the following locations:
    - Root directory
    - .github folder
    - docs folder
3. Add your desired template content to the file.
4. Commit the new file to your repository.

**Creating Issue Templates**

1. Go to your repository & create new file
2. Create a md file eg '.github/ISSUE_TEMPLATE/enhancement_request.md'

Examples can be found as md files in this repo.

You can have as many templates as you want for issues, so you might have a different one intended for enhancements & issues.

**Setting Repository Permissions**

    Go to your repository's "Settings" tab.
    Click on "Collaborators and teams" in the left sidebar.
    Under "Manage access", click "Add people" or "Add teams" to invite collaborators.
    Choose the appropriate permission level for each collaborator or team.

**Useful Resources**

- GitHub Docs on Creating Templates: https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests
- GitHub CLI Documentation: https://cli.github.com/manual/
- GitHub Flow Guide: https://guides.github.com/introduction/flow/

**README.md Templates**
Two simple README.md templates you can use as a starting point:


*Basic README Template*
```md
text
# Project Name

Brief description of the project.

## Installation

Steps to install the project.

## Usage

Instructions on how to use the project.

## Contributing

Guidelines for contributing to the project.

## License

Information about the project's license.
```

*Detailed README Template*

```md
text
# Project Name

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

One-paragraph description of the project.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [License](#license)
- [Contact](#contact)

## Features

- Feature 1
- Feature 2
- Feature 3

## Installation

npm install your-project-name

text

## Usage

Provide examples of how to use your project.

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## Tests

Explain how to run the automated tests for this system.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Your Name - [@your_twitter](https://twitter.com/your_twitter) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)
```

**Useful Resources:**
[Working with Git on the command line](https://user-guidance.analytical-platform.service.justice.gov.uk/github/command-line-git.html)

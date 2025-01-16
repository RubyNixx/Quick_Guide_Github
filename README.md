:black_square_button: **Methods of working with Git** :black_square_button:

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

:black_square_button: **Creating a Repository from a Template** :black_square_button:

1. Navigate to the main page of the template repository on GitHub.com.
2. Click the "Use this template" button near the top-right of the page.
3. Select "Create a new repository" from the dropdown menu.
4. Choose the owner of the new repository from the "Owner" dropdown menu.
5. Enter a name for your new repository.
6. Optionally, add a description for your repository.
7. Choose the repository visibility (Public or Private). Consider 'everyone'.
8. If desired, select "Include all branches" to copy all branches from the template, not just the default branch.
9. Click "Create repository from template".

:black_square_button: **Creating a Pull Request Template** :black_square_button:

1. In your repository, create a new file named PULL_REQUEST_TEMPLATE.md.
2. Place this file in one of the following locations:
    - Root directory
    - .github folder
    - docs folder
3. Add your desired template content to the file.
4. Commit the new file to your repository.

:black_square_button: **Creating Issue Templates** :black_square_button:

1. Go to your repository & create new file
2. Create a md file eg '.github/ISSUE_TEMPLATE/enhancement_request.md'

Examples can be found as md files in this repo.

You can have as many templates as you want for issues, so you might have a different one intended for enhancements & issues.

:black_square_button: **Setting Repository Permissions** :black_square_button:

    Go to your repository's "Settings" tab.
    Click on "Collaborators and teams" in the left sidebar.
    Under "Manage access", click "Add people" or "Add teams" to invite collaborators.
    Choose the appropriate permission level for each collaborator or team.


:black_square_button: **README.md Templates** :black_square_button:

Two simple README.md templates you can use as a starting point:


:one: *Basic README Template*
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

:two: *Detailed README Template*

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
:black_square_button: **Commit Structure** :black_square_button:

![image](https://github.com/user-attachments/assets/836a717a-e394-4659-bca9-795377513b6a)

In the first commit, we see a unique identifier ending in six-five. This identifier is known as a hash, which we will discuss later. Two files were modified in the tree - report.md and mental-health-survey.csv. The blob shows a snapshot of what the files contained at that time. 

In the second commit, three files are in the tree, but only two were modified - mental-health-survey.csv and a newly created summary statistics file. Therefore, the tree links report.md to the blob from the previous commit, as it wasn't modified in this commit. 

In the third and most recent commit, report-dot-md and mental-health-survey.csv are modified, with updated blobs created and linked to the tree. The summary statistics file wasn't changed, so the tree links to the blob in the second commit. 

:black_square_button: **Git Hash** :black_square_button:

![image](https://github.com/user-attachments/assets/7ad9b941-7c50-445a-9876-0dce80ecfab5)

Git has a unique identifier called a hash. This is a 40-character string of numbers and letters like this. It is called a hash because Git produces it using a pseudo-random number generator called a hash function. Hashes enable Git to share data efficiently between repos. If two files are the same, their hashes will be the same. Therefore, Git can tell what information needs to be saved in which location by comparing hashes rather than entire files. 

:black_square_button: **Comparing two commits** :black_square_button:

![image](https://github.com/user-attachments/assets/a0f2bc81-029a-4602-a771-512ba4b6f1a7)

![image](https://github.com/user-attachments/assets/95688cc1-04fa-4093-93a2-82870ca69a4b)

![image](https://github.com/user-attachments/assets/e5f6a611-5534-45b0-9e95-416cb904c695)

:black_square_button: **Reverting files** :black_square_button:

![image](https://github.com/user-attachments/assets/edb2f717-9528-4289-9835-c744f7d1b914)



:black_square_button: **Useful Resources** :black_square_button:

- [GitHub Docs on Creating Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests)
- [GitHub CLI Documentation](https://cli.github.com/manual/)
- [GitHub Flow Guide](https://guides.github.com/introduction/flow/)
- [Working with Git on the command line](https://user-guidance.analytical-platform.service.justice.gov.uk/github/command-line-git.html)
- [Datacamp Course](https://app.datacamp.com/learn/courses/introduction-to-git)

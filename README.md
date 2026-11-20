# Team Project Repository with Branches, Pull Requests and README Documentation

## Experiment Details
- **Student Name:** J Yukesh Kumar
- **Register Number:** 192524464
- **Department:** B.Tech Artificial Intelligence and Data Science
- **Course:** Software Engineering
- **Repository:** CSA1010-SOFTWARE-ENGINEERING

## Aim
To create and manage a team project repository using GitHub, demonstrate branch-based development, submit changes through pull requests, and document the workflow in a README file.

## Objectives
1. Create a shared GitHub repository for a team project.
2. Use separate branches so members can work independently.
3. Commit and push changes to a remote branch.
4. Create and review a pull request.
5. Merge approved changes into the main branch.
6. Maintain clear project setup and experiment documentation.

## Tools Required
- Git
- GitHub account and web interface
- Visual Studio Code or another text editor
- Web browser

## Repository Structure
```text
CSA1010-SOFTWARE-ENGINEERING/
├── README.md
├── docs/
│   └── experiment-report.md
├── team/
│   └── roles.md
└── examples/
    └── contribution.txt
```

## How to Run / Perform the Experiment

### 1. Open the repository
Visit [CSA1010-SOFTWARE-ENGINEERING](https://github.com/yukeshkumar2k8-ship-it/CSA1010-SOFTWARE-ENGINEERING).

### 2. Clone the repository
Open a terminal and run:
```bash
git clone https://github.com/yukeshkumar2k8-ship-it/CSA1010-SOFTWARE-ENGINEERING.git
cd CSA1010-SOFTWARE-ENGINEERING
```

### 3. Create a working branch
Use a separate branch for each task or team member:
```bash
git switch -c feature/documentation
```
If using an older Git version:
```bash
git checkout -b feature/documentation
```

### 4. Make and save a change
Edit a project file or create a new file. For this experiment, update the documentation or add a contribution note.

### 5. Stage and commit the change
```bash
git add .
git commit -m "Add team project documentation"
```

### 6. Push the branch to GitHub
```bash
git push -u origin feature/documentation
```

### 7. Create a Pull Request
1. Open the repository on GitHub.
2. Select **Pull requests** and click **New pull request**.
3. Set the base branch to `main`.
4. Set the compare branch to `feature/documentation`.
5. Review the changed files and click **Create pull request**.
6. Add a meaningful title and description.

### 8. Review and merge
Check the changed files, confirm that the update is correct, and merge the pull request into `main`. Delete the feature branch after merging if it is no longer needed.

### 9. Update the local main branch
```bash
git switch main
git pull origin main
```

## Useful Git Commands

| Command | Purpose |
|---|---|
| `git status` | Shows changed files and current branch |
| `git branch` | Lists local branches |
| `git switch -c branch-name` | Creates and switches to a branch |
| `git add .` | Stages changes |
| `git commit -m "message"` | Records a commit |
| `git push -u origin branch-name` | Pushes a branch to GitHub |
| `git pull origin main` | Gets the latest main branch changes |
| `git log --oneline` | Displays commit history |

## Expected Output
- A GitHub repository containing project documentation.
- A separate working branch for development.
- A commit showing the contribution.
- A pull request comparing the working branch with `main`.
- The reviewed changes merged into `main`.

## Result
The team project repository workflow was demonstrated using GitHub. Branch-based development, commits, pull requests, merging, and README documentation were included to support organized team collaboration.

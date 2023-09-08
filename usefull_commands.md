# Useful Git Commands

This repository serves as a quick reference guide to essential Git commands. Whether you're new to Git or need a handy reference for your daily workflow, you'll find these commands helpful.

## Getting Started

### Installing Git

If you haven't already installed Git, you can download and install it from the official Git website: [https://git-scm.com/downloads](https://git-scm.com/downloads).

### Configuration

Before using Git, it's a good idea to configure your identity:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

Replace "Your Name" and "your.email@example.com" with your actual name and email address.

## Essential Git Commands

Here's a list of commonly used Git commands and their descriptions:

### 1. Initializing a Repository

- Initialize a new Git repository:

```bash
git init
```

### 2. Cloning a Repository

- Clone a remote repository to your local machine:

```bash
git clone <repository_url>
```

### 3. Making Changes

- Check the status of your working directory:
```bash
git status
```

- Add changes to the staging area:
```bash
git add <file(s)>
```

- Commit changes with a message:
```bash
git commit -m "Your commit message"
```

### 4. Branching

- Create a new branch:
```bash
git branch <branch_name>
```

- Switch to a different branch:
```bash
git checkout <branch_name>
```

- Create and switch to a new branch:
```bash
git checkout -b <new_branch_name>
```

### 5. Merging

- Merge changes from one branch into another:
```bash
git merge <branch_name>
```

### 6. Remote Repository Interaction

- Add a remote repository:
```bash
git remote add <remote_name> <repository_url>
```

- Push changes to a remote repository:
```bash
git push <remote_name> <branch_name>
```

- Pull changes from a remote repository:
```bash
git pull <remote_name> <branch_name>
```

### 7. History and Logs

- View commit history:
```bash
git log
```

- View a specific commit's changes:
```bash
git show <commit_hash>
```

### 8. Discarding Changes

- Discard changes in the working directory:
```bash
git restore <file(s)>
```

- Discard changes in the staging area:
```bash
git restore --staged<file(s)>
```

### 9. Removing and Deleting

- Remove a file from version control (but keep it locally):
```bash
git rm --cached <file(s)>
```

- Delete a branch:
```bash
git branch -d <branch_name>
```

### 10. Configuration

- View Git configuration settings:
```bash
git config --list
```

## Additional Resources

For more information on each command and advanced Git topics, refer to the official Git documentation: https://git-scm.com/docs

## License

This project is licensed under the MIT License.

---

Feel free to use this repository as a reference whenever you need to use Git commands in your projects. Happy coding!

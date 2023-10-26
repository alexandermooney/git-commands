# Git Commands

| Command | Description |
| ------------- |----------- |
| `git init` | Initializes a local repository. Used in lieu of cloning a GitHub repo. All local repos contain a hidden `.git` directory responsible for holding repo-related data. |
| `git status` | Checks and reports on the status of your repo. It will inform you what changes to tracked (staged) files will be included in next commit, if there are any untracked files that have been added to the project or have changes, etc. |
| `git add <path>` | Adds an entire directory or individual file (or files using a `*` as a wildcard) to the "staging area" for the next commit. |
| `git add -A` | Adds all changes within the repo to the staging area for the next commit |
| `git committ -m "<message>"` | Commits all staged changes to the local repo. The message should be worded in such that it describes what the commit does, not what it did. For example, "Style nav bar" instead of "Styled nav bar". |
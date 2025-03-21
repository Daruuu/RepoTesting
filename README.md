# Git Repository Update Automation

This project provides a script and a Makefile target to automate the process of updating a Git repository. The script simplifies adding, committing, and pushing changes to a specified branch.

## Features
- **Automates Git operations**: Adds, commits, and pushes changes with minimal input.
- **User-friendly prompts**: Asks for a commit message and branch name.
- **Logs recent commits**: Displays the last three commits after pushing changes.
- **Compatible with Makefile and Bash**: Can be executed either via a Makefile target or directly as a Bash script.

## Usage

### Using the Makefile
Run the following command:
```bash
make run
```
This will:
1. Show the current Git status.
2. Add all changes.
3. Ask for a commit message and commit the changes.
4. Ask for the branch name (default is `main`) and push the changes.
5. Display the last three commits.

### Using the Bash Script
Run the script manually:
```bash
chmod +x update_repo.sh
./update_repo.sh
```
Follow the prompts to complete the Git update process.

## Requirements
- Git must be installed and configured.
- The script should be placed inside a Git repository.

## License
This project is licensed under the MIT License.


# My Details
Name : Kumar Abhinav 
Roll No : BT25CSE197 
Section : CSE C2

# Description
This project is to test the understanding of git concepts, git version control operations and other concepts such as Git configuration, repository creation, shell scripting, selective staging, inspecting changes, ignoring generated files, and resolving merge conflicts.

# Completed Exercises
|Exercise no. |Description |Status |
|-------------|------------|-------|
|Exercise 1 |Greet User|Completed |
|Exercise 2 |Calculator Interface|Completed |   
|Exercise 3 |Search Employees of a Branch in DataFile|Completed |   
|Exercise 4 |Find m^n|Completed |   
|Exercise 5 |Create a Shell File|Completed | 

# How to Compile and run
### Installing Bash

**Windows:**

1. Install Git for Windows from the official website: https://git-scm.com/downloads/win
2. Open Git Bash after installation.
3. Verify the installation:

```bash
bash --version
```

### Cloning the Repository
Open a terminal and execute:

```bash
git clone https://github.com/bt25cse197-create/git-practice-BT25CSE197.git
cd git-practice-BT25CSE197
```

### Executing Shell Scripts

1. Open the terminal in the repository directory.
2. Navigate to the required exercise folder. For example:

```bash
cd exercise-1
```
3. Execute the shell script:
```bash
bash input.sh
```
After execution you will see the suitable output in the output.txt file

# Links to issues
1: https://github.com/bt25cse197-create/git-practice-BT25CSE197/issues/1
2: https://github.com/bt25cse197-create/git-practice-BT25CSE197/issues/2

# Links to PRs
https://github.com/bt25cse197-create/git-practice-BT25CSE197/pull/4

# Merge conflict and resolving it

A merge conflict occurred when the same line in `exercise-5/input.sh` was modified differently in the `main` branch and `conflict-branch`.
When I attempted to merge `conflict-branch` into `main`, Git was unable to automatically decide which version to retain.
I resolved the conflict by opening the file, reviewing both versions, choosing the required content, and removing the conflict markers (`<<<<<<<`, `=======`, and `>>>>>>>`).
After resolving the conflict, I staged the file, committed the changes, and pushed the updated `main` branch.
# find-deletable-branches

This script lists all local or remote branches that have already been merged into the main branch (e.g., 'master' or 'main'). It displays the branch name, the date it was merged, and the merge commit ID.
The output is sorted by merge date, with the most recent merges appearing first.
The results are displayed on the screen and also saved to a file named 'deletable_branches_report.txt'.
This helps identify branches that are safe to delete.

# How to use?
1. Git must be installed on your computer
2. Copy the script to the folder with the repository!
3. Edit the variables in the script 'searchMode' (default remote), 'mainBranchName' (default master), possibly 'outputFile' (default deletable_branches_report.txt). See the description in the script comment.
4. The script is executed in Windows PowerShell and must be in the folder with the repository.
Run command
```
powershell -ExecutionPolicy Bypass -File .\find-deletable-branches.ps1
```
The result will be saved to the file specified in the outputFile variable

# find-deletable-branches
Finds Git branches that have been merged into a specified main branch.

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

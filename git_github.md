# Git Instructions

open terminal of vs code and type
1. git
2. git --version
3. git config --global user.name "Selva" (One time)
4. git config --global user.email "selva.jeyaseelan@gmail.com" (One Time)
5. git config --list ( Opens long pager: to come out press 'q' or cntrl + c, press enter or space to come to end of line )
6. git init (initialized git, source control tracks and color of files changes, git will track chagnes to files in the folder) - when you right click on folder and see hidden files(.git) you will be able to see a folder with meta infomation. ALso notice the chagnes to the file exlorer and source control section

7. [working directory-> staging area (folder) -> Local repository when you commit] - All this in your local folder -> Remote (git hub, final push)
8. git status (shows current status)
9. git add git_github.md ( after this notice the the .md files moves to staging area, alternatively you can click on the plus symbol on the left pane in source control, you can use "-' symbol to remove (unstage) the add and bring in back to working directory)
10. git status
11. git add . ( to add everything to stage)
12. git commit -m "first git checkin" (all files now local repo still in local system, notice the source control for the files disappears, -m means message. Now local files are frozen)
13. Notice in source control there is publish branch - UI interface to push to github
14. Create an account in git hub and create a repository with default options
15. git branch -M main
16. git remote add origin https://github.com/selvajeyaseelan/github_6_sep.git
17. git push -u origin main

18. Once you begin to change anything in your files, again the source control is triggered and the changes gets tracked
19. Right click on the file name and say open changes. THis shows the changes to the file since the last commit. This is the meaning of purpose control. Notice next to file name you see an M which means modified, hover over it
20. git status (shows files are modified, in red)
21. git add .
22. git status (green)
23. git commit -m "added more updates to the github.md file" (source control disappears since changes frozen)
24. git status (your branch is up to date with origin/main)
25. git push -u origin main (or source control and sync changes up arrow)
26. again make changes to the file and then see changes with colors.

Light Red / Soft Red (Left side): Marks an entire line that was modified or removed compared to the last commit.

Darker Red (Left side, line 24–25): Highlights the exact characters or words that were changed or deleted within that line.

Light Green / Soft Green (Right side): Marks entire new lines that have been added to your file.

Darker Green (Right side, line 24): Highlights the exact characters or words that were newly inserted or edited within an existing line.

The striped diagonal area on the left simply fills empty space to keep unchanged lines aligned across both panes.

27. Go to github and you will see the new commit message. Click on the file, go to history on the top right, you can see version contorl here, alternatively click on the commit message
28. WE can revert to earlier change levels any time. In local system, vs code, source control, chagnes, three dots, commit, undo last commit
29. Pull request
30. new folder: git clone https://github.com/selvajeyaseelan/github_6_sep
31. Generally it is not recommended to clone a repo and start changing the files, we have not initiazed git, no code tracking
32. If you have done changes by mistake then: git pull origin main or git init, then discard all changes
33. when working in a team dont push to main branch(source of truth), create your own branch (development branch), after verification only must be pushed to main branch
34. git branch (shows all available branch)
35. git branch test (creates new branch)
36. git branch (still shows main)
37. git switch ( now shows test branch in green, also notice at the bottom left, the branch name is shown)










 
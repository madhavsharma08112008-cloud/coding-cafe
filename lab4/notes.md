Question 1: --global makes the setting apply to every repository for my user on this computer, stored in ~/.gitconfig. Without it, Git would try to set it only for the current repository.

Question 2: A hidden .git directory appeared. It holds everything Git uses to track the project, like the saved versions, history, branches and config.

Question 3: Git offered to track roughly [N] files and folders, almost all inside .venv/. Those are installed libraries, not code I wrote.

Question 4: The .venv/ entries (and other ignored items like __pycache__/) disappeared from the untracked list. Git now skips anything matching the patterns in .gitignore.

Question 5: It should be committed, not ignored. It is part of the project setup, so anyone who clones the repo gets the same ignore rules.

Question 6: README.md moved from "Untracked files" to "Changes to be committed", meaning it went from the working directory to the staging area.

Question 7: Git printed a summary like "[main abc1234] Lab work so far" with the number of files changed, insertions, and a create mode line per file. It said [N] files changed.

Question 8: The first seven characters are the short commit hash. They uniquely identify that commit so I can refer to it without typing the full 40 characters.

Question 9: The four steps are edit, check with git status, stage with git add, and save with git commit.

Question 10: GitHub automatically shows README.md on the repository's front page, so it needs that exact name and sits at the root. It is the first thing visitors see and explains the project.

Question 11: It logged me in through the browser and stored a token, and set up Git to use it as its credential. So Git supplies it automatically on every push.

Question 12: The front page shows the rendered README.md with my name, roll number and contents list. GitHub displays the README there because it treats it as the project's description.

Question 13: No, my local history looked exactly the same. Push only copies commits to GitHub, though it updates origin/main in my local view.

Question 14: A private repository exists on GitHub and holds my code, but only I and people I invite can see it. A repository that does not exist on GitHub has no online copy at all, so there is no backup and nothing to share.

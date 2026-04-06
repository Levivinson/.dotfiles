https://github.com/Levivinson/.dotfiles

This assignment helped me learn how to set up and use GitHub along with Git on the command line. I created a GitHub account and repository called “.dotfiles,” and then configured Git locally using my name and email. I also set up SSH authentication by generating an ed25519 key and adding it to my GitHub account. This allowed me to securely connect my local machine to GitHub without needing a password every time.

After setting everything up, I created a local “.dotfiles” directory and added files like README.md and .nanorc. I used nano to edit these files and added the required content from the assignment. Then, I initialized a Git repository in that directory, added all the files, made my first commit, and pushed everything to my GitHub repository. This process helped me understand how version control works and how local changes can be tracked and uploaded online.

One challenge I faced was getting the repository to push correctly to GitHub. I ran into errors related to the repository not being found and later had issues with merging local and remote histories. I learned how to fix these problems by correcting the remote URL and using commands like git pull --allow-unrelated-histories and force pushing when necessary. Overall, this assignment helped me better understand Git, GitHub, and how to troubleshoot common issues when working with version control systems.

Commands used:
mkdir .dotfiles
cd .dotfiles
nano README.md
nano .nanorc
cp .nanorc ~/.nanorc
git init
git add --all
git commit -m "INIT commit"
git branch -M main
git remote add origin git@github.com:Levivinson/.dotfiles.git
git pull --no-rebase origin main --allow-unrelated-histories
git push -u origin main --force

Resources:
GitHub Docs
Course assignment PDF

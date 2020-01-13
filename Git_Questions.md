Question 1: What is the difference between git pull and git fetch?
Session1_thuPhaHoai
Git pull automatically merges any pulled commits into the branch you are currently working in
Git fetch only copies the latest data and stores in your local repository
Phuong Vo:
			git pull: downloads the changes and merges them into your current branch
			git fetch: just "downloads" the changes from the remote to your local repository
Van Vo:
git pull : merge to local repo and working space
git fetch: only merge to local repo

Question 2: What is the three states of Git ? list them.
git add file fro working space to staging, then commit that file to local repo. After then, git push file to remote repo.
Phuong Vo: Working brach - Staging - Repository

Question 3: What command "git stash" does ? when to use this command ?
Phuong Vo: 	Using git stash to store the changes but not committed yet, then you can switch to other brach.
			After that you can back to working brach, then apply the changes and commit it later on.
Van Vo
==> Sorry. I do not know the answer :)))
Session1_thuPhaHoai
Git stash temporarily saves and stores your uncommitted code for later use. Use this when you need to work on different branch.

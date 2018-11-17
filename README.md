# Kottans_frontend course 2019

![cat](https://pbs.twimg.com/profile_images/447832292023480320/VKvHw9c-.png)


##Stage 0
### General Basics

- [+] <a href='https://github.com/kottans/frontend/blob/master/tasks/git-intro.md'>Git Basics</a>
- [ ] <a href='https://github.com/kottans/frontend/blob/master/tasks/linux-cli-http.md'>Linux CLI, and HTTP</a>
- [ ] <a href='https://github.com/kottans/frontend/blob/master/tasks/git-collaboration.md'>VCS (hello gitty), GitHub and Collaboration</a>

### Front-End Basics
- [ ] <a href='https://github.com/kottans/frontend/blob/master/tasks/html-css-intro.md'>Intro to HTML & CSS</a>
- [ ] <a href='https://github.com/kottans/frontend/blob/master/tasks/html-css-responsive.md'>Responsive Web Design</a>
- [ ] <a href='https://github.com/kottans/frontend/blob/master/tasks/js-basics.md'>JavaScript Basics</a>
- [ ] <a href='https://github.com/kottans/frontend/blob/master/tasks/js-dom.md'>Document Object Model</a>

### Advanced Topics

- [ ] <a href='https://github.com/kottans/frontend/blob/master/tasks/js-pre-oop.md'>Building a Tiny JS World (pre-OOP) </a> 



# Topics overview:
## 1.Git Basics - **Done**

#### useful information:
- **comperisons to different VCS** systems like (svn, git, dropbox, googledocs, wiki)
- **git log** (to find id of commit, author, message, date)
- **git checkout** (go to specific commit in git log history)
- **git checkout -b ${branch_name}** creates new branch by git branch ${branch_name} and make a git checkout ${branch_name} to this branch
- **git branch** view current branch
- **git add** adds file to the staging area [working_area] -add-> [staging_area] -commit-> [local_repo] -push-> [remote_repo]
- **git pull** pull commits from remote to local repo [local_repo] <-pull- [remote_repo] -> it's combination of git fetch + git merge
- **git remote origin ${git_url}** coordinate [local_repo] with [remote_repo]
- **git remote -v** information about git repo coordination
- **git fetch** moves last commit from [remote_repo] to your [local_repo] where last origin/master stands


#### new to me:
- **diff** command for comparing files (e.g. diff -u new.js old.js)
- **git diff** comparing working_area => with staging_area
- **git diff commit1 commit2**  comparing commits by ids (e.g git diff commidId1 commitId2)
- **git diff --staged** see difference between staging_area -> local_repo 
- **git log --graph --oneline ${branch1} ${branch2}** compares two branches and show differences on commit history 
- **upstream/master** make communication between forked repository and remote repository on you local_repo


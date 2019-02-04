# Kottans_frontend course 2019

<img src="https://pbs.twimg.com/profile_images/447832292023480320/VKvHw9c-.png" alt="drawing" width="200"/>


## Stage 0
### General Basics

- [+] <a href='https://github.com/kottans/frontend/blob/master/tasks/git-intro.md'>Git Basics</a>
- [+] <a href='https://github.com/kottans/frontend/blob/master/tasks/linux-cli-http.md'>Linux CLI, and HTTP</a>
- [+] <a href='https://github.com/kottans/frontend/blob/master/tasks/git-collaboration.md'>VCS (hello gitty), GitHub and Collaboration</a>

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

## 2. Linux CLI, and HTTP - **Done**

[completed screenshots](https://github.com/sLisnychyi/kottans-frontend/tree/master/task_linux_cli)

#### useful information:
- **~/.bash_profile** bash_profile information with exporting variables
- **>>source ~/.bash_profile** to enable .bash_profile for current session
- **alias p="pwd""** for creating different alias 
- **history** history of commands
- **export PS1=">>"** for changing command prompt    
- **ls -alt** list of files -a hiden -l in long format -t sorted by the time were last modified


#### new to me:
- **env** show enviroment variables
- **>** e.g. cat file1 > file2 redirect the standard output of file1 into file2
- **>>** append content
- **wc** word count command
- **sort** sorts content of resource
- **uniq** filter out adjacent, duplicates
- **sed** e.g. sed 's/loss/win/' games.txt replace all instances of the word 'loss' with 'win'


## 3. VCS (hello gitty), GitHub and Collaboration - **Done**

[completed_screenshots](https://github.com/sLisnychyi/kottans-frontend/tree/master/task_git_collaboration)

#### useful information:
- **git log** for reviewing list of commits
- **git show ${commit_hash}** to check description about some specific commit
- **git tag** -> for taging commit indicate commit with release phase for example. e.g. (git tag -a v1.0 -m "..." | git tag -a v1.0 a87984)
- **git fetch** -> retrieve commits from a remote repository's branch but it does not automatically merge the local branch with the remote
- **git pull** -> git fetch + merge

#### new to me:
- **git log --oneline** show one commit per line
- **git log --stat** display the files that have been changed in the commit, as well as the number of lines that have been added or deleted
- **git log -p** display the actual changes made to a file
- **git log -p** display the actual changes made to a file
- **git shortlog** display grouped commits by athor + additional params [-s to show just the number of commit], [-n to sort them numerically]
- **git diff** display file difference with repository file version

- **git --amend** changing the last commit/ add forgoten files to commit
- **git revert** {commit_hash} reverting, creates a new commit that reverts or undos a previous commit
- **git reset** erases commits

git reset --mixed HEAD~1 (changes from last commit will go to working directory) -> by default in git reset; 

git reset --soft HEAD~1 (changes from last commit will go to staging index);

git reset --hard HEAD~1 (changes from last commit will go to trash)
- **git branch backup** is doing before reseting commits

## 4. Intro to HTML & CSS - **Done**

[completed_screenshots](https://github.com/sLisnychyi/kottans-frontend/tree/master/task_html_css_intro)

#### useful information:
- research information about tags with examples - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button
- pattern for tags <tag>content</tag>

#### new to me:
- interesting information about parent and child tag connections
<parrent>
    <children1>
    <children2>
<parrent>
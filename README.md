# devopsrepo
Commands used 

$ git init
Reinitialized existing Git repository in C:/Minu/P/devopsrepo/.git/


$ git add .
warning: in the working copy of 'sample-project/css/site.css', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'sample-project/index.html', LF will be replaced by CRLF the next time Git touches it


$ git commit -m 'sample project commited'
[main 1fda3f3] sample project commited
 9 files changed, 198 insertions(+)
 create mode 100644 sample-project/css/site.css
 create mode 100644 sample-project/fonts/segoeuil.ttf
 create mode 100644 sample-project/img/cloneWhite.svg
 create mode 100644 sample-project/img/deployWhite.svg
 create mode 100644 sample-project/img/lightbulbWhite.svg
 create mode 100644 sample-project/img/stackWhite.svg
 create mode 100644 sample-project/img/successCloudNew.svg
 create mode 100644 sample-project/img/tweetThis.svg
 create mode 100644 sample-project/index.html


$ git branch newfeaturebranch


$ git checkout newfeaturebranch
Switched to branch 'newfeaturebranch'


$ git add .


$ git commit -m 'feature branch details committed'
[newfeaturebranch 68ac38a] feature branch details committed
 1 file changed, 2 insertions(+), 1 deletion(-)


$ git push --set-upstream origin newfeaturebranch
info: please complete authentication in your browser...



$ git push --set-upstream origin newfeaturebranch
Enumerating objects: 20, done.
Counting objects: 100% (20/20), done.
Delta compression using up to 4 threads
Compressing objects: 100% (15/15), done.
Writing objects: 100% (18/18), 460.84 KiB | 9.60 MiB/s, done.
Total 18 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'newfeaturebranch' on GitHub by visiting:
remote:      https://github.com/MMDRepo/devopsrepo/pull/new/newfeaturebranch
remote:
To https://github.com/MMDRepo/devopsrepo.git
 * [new branch]      newfeaturebranch -> newfeaturebranch
branch 'newfeaturebranch' set up to track 'origin/newfeaturebranch'.


$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)


$ git merge newfeaturebranch
Already up to date.


$ git pull
Already up to date.


$ git branch
* main
  newfeaturebranch







$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/MMDRepo/devopsrepo.git
   c9d57a3..68ac38a  main -> main


$


$ git remote add origin https://github.com/MMDRepo/newdevopsrepo.git
error: remote origin already exists.


$ git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date


$ git remote add origin https://github.com/MMDRepo/newdevopsrepo.git



$ git branch -M main


$ git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date


$ git branch
* main
  newfeaturebranch


$ git remote add new-remote-url ^C


$ git remote add new-remote-url https://github.com/MMDRepo/newdevopsrepo.git


$ git fetch new-remote-url

$ git push new-remote-url main:main
Enumerating objects: 21, done.
Counting objects: 100% (21/21), done.
Delta compression using up to 4 threads
Compressing objects: 100% (16/16), done.
Writing objects: 100% (21/21), 461.67 KiB | 9.05 MiB/s, done.
Total 21 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
To https://github.com/MMDRepo/newdevopsrepo.git
 * [new branch]      main -> main


$ git branch -r
  new-remote-url/main
  origin/HEAD -> origin/main
  origin/main
  origin/newfeaturebranch

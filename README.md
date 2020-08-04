# ci

    git init
    git add .
    git commit -m "first commit"
    git remote add origin https://github.com/nawafisuren/ci.git
    git push -u origin master
    git pull origin master
    git push -u origin master
		====0reff
		https://medium.com/aisy-rozsidhy/tutorial-penggunaan-github-untuk-pemula-part-1-upload-file-ke-github-e807df4e9ecc
		


basobox@basobox-69:/opt/lampp/htdocs/1234/webgis_ci$ git remote add origin https://github.com/nawafisuren/ci.git


basobox@basobox-69:/opt/lampp/htdocs/1234/webgis_ci$ git push -u origin master
Username for 'https://github.com': nawafisuren
Password for 'https://nawafisuren@github.com': 
To https://github.com/nawafisuren/ci.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/nawafisuren/ci.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


basobox@basobox-69:/opt/lampp/htdocs/1234/webgis_ci$ git pull origin master
warning: no common commits
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/nawafisuren/ci
 * branch            master     -> FETCH_HEAD
 * [new branch]      master     -> origin/master
Merge made by the 'recursive' strategy.
 README.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 README.md


basobox@basobox-69:/opt/lampp/htdocs/1234/webgis_ci$ git push -u origin master
Username for 'https://github.com': nawafisuren
Password for 'https://nawafisuren@github.com': 
Counting objects: 5583, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (5436/5436), done.
Writing objects: 100% (5583/5583), 21.75 MiB | 103.00 KiB/s, done.
Total 5583 (delta 1442), reused 0 (delta 0)
remote: Resolving deltas: 100% (1442/1442), done.
To https://github.com/nawafisuren/ci.git
   087d622..8396041  master -> master
Branch master set up to track remote branch master from origin.
basobox@basobox-69:/opt/lampp/htdocs/1234/webgis_ci$ 

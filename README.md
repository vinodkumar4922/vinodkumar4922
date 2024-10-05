
BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ git remote add origin https://github.com/vinodkumar4922/vnod
fatal: detected dubious ownership in repository at 'C:/'
'C:/' is owned by:
        'S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464'
but the current user is:
        'S-1-5-21-3099290835-4184616228-995990836-1001'
To add an exception for this directory, call:

        git config --global --add safe.directory C:/

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ git commit -m "first commit"
fatal: detected dubious ownership in repository at 'C:/'
'C:/' is owned by:
        'S-1-5-80-956008885-3418522649-1831038044-1853292631-2271478464'
but the current user is:
        'S-1-5-21-3099290835-4184616228-995990836-1001'
To add an exception for this directory, call:

        git config --global --add safe.directory C:/

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ cd ..

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ cd..
bash: cd..: command not found

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ cd ..

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ cd ..

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ cd d

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git remote add origin https://github.com/vinodkumar4922/vnod
error: remote origin already exists.

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git branch
* master
  new

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git commit -m "first commit"
[master bef1b86] first commit
 1 file changed, 5 insertions(+)
 create mode 100644 gitlabds027/prog3.c

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git push origin master
remote: Permission to rachanabenal/pmg2.git denied to vinodkumar4922.
fatal: unable to access 'https://github.com/rachanabenal/pmg2.git/': The requested URL returned error: 403

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git push origin master
remote: Permission to rachanabenal/pmg2.git denied to vinodkumar4922.
fatal: unable to access 'https://github.com/rachanabenal/pmg2.git/': The requested URL returned error: 403

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git push origin master
remote: Permission to rachanabenal/pmg2.git denied to vinodkumar4922.
fatal: unable to access 'https://github.com/rachanabenal/pmg2.git/': The requested URL returned error: 403

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git push origin master
remote: Permission to rachanabenal/pmg2.git denied to vinodkumar4922.
fatal: unable to access 'https://github.com/rachanabenal/pmg2.git/': The requested URL returned error: 403

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
safe.directory=D:/
user.name=Vinod
user.email=vinodjangamashetti8@gmail.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.worktree=D:/
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/rachanabenal/pmg2.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.master.remote=origin
branch.master.merge=refs/heads/master

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git remote rm origin

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git remote add origin https://github.com/vinodkumar4922/vnod

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git push origin master
Enumerating objects: 17, done.
Counting objects: 100% (17/17), done.
Delta compression using up to 20 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (17/17), 1.35 KiB | 1.35 MiB/s, done.
Total 17 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/vinodkumar4922/vnod
 * [new branch]      master -> master

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ 9C8C-0D4Cls
bash: 9C8C-0D4Cls: command not found

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ la
bash: la: command not found

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ ls
'$RECYCLE.BIN'/   184/          2BL22CS415/   2bl21cs095/   2bl23cs037/   CDTROOT/                      Test/            clone/    fir/           madhu/            prog1.c       two.txt
 131/             2/            2BL23CD027/   2bl21cs099/   2bl23cs132/   CSE61_FSD/                    a1/              cs027/    fridaylab/    'pankaj kittad'/   program2/     usn184/
 164/             2BL21CS010/   2BL23CD057/   2bl21cs101/   2bl23cs312/   CSE_FSD/                      a11/             daksha/   gee66/         pavanst/          rachana097/
 167/             2BL21CS131/   2BL23CS027/   2bl22cs019/   61/           DjangoProj/                   angular/         exam/     gee67/         pgm/              rachana1/
 169/             2BL21CS408/   2BL23CS164/   2bl22cs169/   Angular.txt   Helloword.txt                 angular,jss.js   exp3/     gitlabds027/   prathmesh/        rakshita/
 182/             2BL22CS407/   2bl21cs003/   2bl22cs408/   CD027/       'System Volume Information'/   chaitra/         exp4/     layout/        prg1/             saqlain/

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ cd 2bl23cd057

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ ls
prog1  prog1.c

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git push origin master
fatal: protocol 'https' is not supported

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ nano prog1.c

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git add prog1.c

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git commit -m
error: switch `m' requires a value

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git commit -m "prog"
On branch master
nothing to commit, working tree clean

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git commit -m "prog"
On branch master
nothing to commit, working tree clean

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git push origin master
fatal: protocol 'https' is not supported

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
safe.directory=D:/
user.name=Vinod
user.email=vinodjangamashetti8@gmail.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=<U+0096>https://github.com/vinodkumar4922/vnod
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git add prog1.c

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git commit -m "prog"
On branch master
nothing to commit, working tree clean

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git commit -m "prog1.c"
On branch master
nothing to commit, working tree clean

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ ls
prog1  prog1.c

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git add prog1

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git commit -m "prog1"
On branch master
nothing to commit, working tree clean

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ nano vnod.c

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ ls
prog1  prog1.c  vnod.c

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git add vnod.c
warning: in the working copy of 'vnod.c', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git commit -m "vnod"
[master 671ed8a] vnod
 1 file changed, 6 insertions(+)
 create mode 100644 vnod.c

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git push origin master
fatal: protocol 'https' is not supported

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git push origin master
fatal: protocol 'https' is not supported

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git config --global user.name "vinodkumar4922"

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git config --global user.password "49222510@Vk."

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git config --global user.email "vinodjangamashetti8@gmail.com"

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git remote add origin https://github.com/vinodkumar4922/vnod
error: remote origin already exists.

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git remote remove origin

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git remote add origin https://github.com/vinodkumar4922/vnod

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git push origin master
To https://github.com/vinodkumar4922/vnod
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/vinodkumar4922/vnod'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git remote remove origin

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git remote add origin https://github.com/vinodkumar4922/newrepo

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)
$ git push origin master
Enumerating objects: 16, done.
Counting objects: 100% (16/16), done.
Delta compression using up to 20 threads
Compressing objects: 100% (13/13), done.
Writing objects: 100% (16/16), 1.30 KiB | 1.30 MiB/s, done.
Total 16 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/vinodkumar4922/newrepo
 * [new branch]      master -> master

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/2bl23cd057 (master)

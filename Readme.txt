core.editor='C:/Program Files (x86)/Notepad++/notepad++.exe' -multiInst -nosession
core.editor=gedit
core.editor=notepad++
code.editor='C:/Program Files (x86)/Notepad++/notepad++.exe'  -n -w

git config --global --unset-all core.editor
git config --global --unset core.editor  // не працює коли багато таких стрічок.

ocitk@citkowski_ov MINGW64 /f/goodtools (master)
$ git config --global --unset core.editor.*
error: invalid key: core.editor.*

ocitk@citkowski_ov MINGW64 /f/goodtools (master)
$ git config --global -l
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
user.name=OCitkowski
user.email=38069264+OCitkowski@users.noreply.github.com
core.editor='C:/Program Files (x86)/Notepad++/notepad++.exe' -multiInst -nosession
core.editor=gedit
core.editor=notepad++

ocitk@citkowski_ov MINGW64 /f/goodtools (master)
$ git config --local -l
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
submodule.active=.
remote.origin.url=https://github.com/OCitkowski/GoodTools.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.master.remote=origin
branch.master.merge=refs/heads/master

ocitk@citkowski_ov MINGW64 /f/goodtools (master)
$ git config --system -l
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
http.sslbackend=openssl
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
credential.helper=manager
core.editor='C:\Program Files (x86)\Notepad++\notepad++.exe' -multiInst -notabbar -nosession -noPlugin

ocitk@citkowski_ov MINGW64 /f/goodtools (master)

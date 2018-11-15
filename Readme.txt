git config --global --unset-all core.editor
git config --global --unset core.editor  // не працює коли багато таких стрічок.

global
system
local
git config --local commit.template $HOME/.gitmessage.txt // Текст при коміті
// коли треба видалити запис, а редактор не працює))
//  global/system/local
git config --global --unset-all core.editor
git config --global --unset core.editor  // не працює коли багато таких стрічок.

//  global/system/local
git config --local -l  // Показує файл конфіга (тут репозіторія)
git config --local commit.template F:/goodtools/gitmessage.txt // Текст при коміті



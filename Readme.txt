// ���� ����� �������� �����, � �������� �� ������))
//  global/system/local
git config --global --unset-all core.editor
git config --global --unset core.editor  // �� ������ ���� ������ ����� ������.

//  global/system/local
git config --local -l  // ������ ���� ������� (��� ���������)
git config --local commit.template F:/goodtools/gitmessage.txt // ����� ��� ����


�or create a new repository on the command line

echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:OCitkowski/goodtools.git
git push -u origin master

�or push an existing repository from the command line

git remote add origin git@github.com:OCitkowski/goodtools.git
git push -u origin master
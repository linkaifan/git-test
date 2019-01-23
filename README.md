## git常用命令
  - git add 
  - git commit 
  - git reset --hard [版本号]
  - git log
  - git reflog
  - 当你改乱了工作区某个文件的内容，想直接丢弃工作区的修改时，用命令git checkout -- file【git checkout其实是用版本库里的版本替换工作区的版本，无论工作区是修改还是删除，都可以“一键还原”。
  - 当你不但改乱了工作区某个文件的内容，还添加到了暂存区时，想丢弃修改，分两步，第一步用命令git reset HEAD file，就回到了场景1，第二步按场景1操作。
  - git rm用于删除一个文件。如果一个文件已经被提交到版本库，那么你永远不用担心误删，但是要小心，你只能恢复文件到最新版本，你会丢失最近一次提交后你修改的内容。
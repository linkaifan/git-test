## git常用命令
  - git add 
  - git commit 
  - git reset --hard [版本号]
  - git log
  - git reflog
  - 当你改乱了工作区某个文件的内容，想直接丢弃工作区的修改时，用命令git checkout -- file
  - 当你不但改乱了工作区某个文件的内容，还添加到了暂存区时，想丢弃修改，分两步，第一步用命令git reset HEAD file，就回到了场景1，第二步按场景1操作。
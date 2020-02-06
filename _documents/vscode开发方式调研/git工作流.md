## git工作流

### 工作流方式
1. 中心式协同工作流
    * git pull
    * git commit
    * git push

2. 功能分支协同工作流
    * 开出一个额外的功能分支
    * 功能开发完之后合并到主分支上

3. GitFlow协同工作流
    * master分支
    * hot-fix分支
    * dev分支
    * 功能分支
    * release分支
其中dev分支和master分支长期维护，hot-fix分支用于修复线上bug

4. GitHub/GitLab协同工作流










### 问题
1. git pull --rebase为什么可以避免merge的动作
2. git merge --no-ff
3. 如何合并上游分支
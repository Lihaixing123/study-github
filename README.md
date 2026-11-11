# study-github

Git / GitHub 零基础学习记录，每天一次 commit。目标：能独立维护一个自己的项目。

## 学习进度

- Day 1：SSH，把本地和 GitHub 接上
- Day 2：核心循环，改动从本地走到云端
- Day 3：branch，平行世界与合并
- Day 4：.gitignore，让 git 不跟踪某些文件
- Day 5：仓库装修，About / README / Pin

## 踩坑记录

- `git add -dry--run` 报 `error: unknown switch 'd'`——短选项一次一字母，演练要用 `--dry-run`
- PowerShell 里 `cd /d` 不成立——`/d` 是 CMD 的参数，PowerShell 直接 `cd D:\路径`
- 网页改过 README 后 push 被拒——先 `git pull` 再推，永不 `--force`

## 三区模型

- 工作区：看得见摸得着的那份
- 暂存区：add 之后的候选清单
- 版本库：commit 之后的档案
- 这一行是 add 之后才加的，还没进暂存区
# A-项目 Git 常用命令说明
---
## 克隆仓库到本地
git clone https://github.com/askjdhx/A-.git
---
## 克隆指定分支（比如 develop）
git clone -b develop https://github.com/askjdhx/A-.git
---
## 切换分支到 develop
git checkout develop
---
## 拉取远程最新代码（推送前一定要先拉取）
git pull
---
## 添加更改到暂存区
git add .
---
## 提交更改（加上说明）
git commit -m "这里写本次提交的简短说明"
---
## 推送更改到远程分支（当前分支）
git push
---
## 合并 develop 分支到 main 分支
git checkout main
git merge develop
---
## 额外提示
- 避免多人同时修改同一个文件，防止冲突
- 遇到冲突时，手动解决后再提交
- 养成频繁提交、及时同步的习惯

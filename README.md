测试1
git add README.md        # 将新文件添加到暂存区
git commit -m "添加新的 README.md 文件"  # 提交更改
git push origin main     # 推送到远程仓库


说明
git add .                # 1. 把修改/新增的文件“暂存”
git commit -m "说明"     # 2. 提交到本地仓库（"说明"换成你这次改了什么）
git push origin main     # 3. 推到你 GitHub 的 main 分支
**git add . 是一次性打包当前目录所有变更，而 git add 具体文件名 则是精确挑选单个文件**。
# 1. 并在本地项目根目录下初始化 Git（如果还没初始化的话）
git init

# 2. 关联远程 GitHub 仓库（将下方的链接替换为你刚复制的链接）
git remote add origin https://github.com/saabzhi/study_repo.git

或使用SSH 方式
把 mac 用户的 ssh 公钥添加到 GitHub 账号
git remote set-url origin git@github.com:saabzhi/study_repo.git
测试连通性
git -T git@github.com

# 3. 推送代码
git branch -M main

git push -u origin main

# Gitリポジトリを初期化
git init

# mainブランチに切り替え
git branch -M main

# すべてのファイルをステージング
git add .

# 最初のコミット
git commit -m "Initial commit: DocFX project"

# GitHubリポジトリを追加（URLは自分のものに置き換える）
git remote add origin https://github.com/scriabin110/scriabin110.github.io.git

# GitHubにプッシュ
git push -u origin main

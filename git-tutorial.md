# 初期設定
git config --global user.name "XXXX"　\\名前を入力  
git config --global user.email "XXXX"　\\メールアドレスを入力  

# ローカルにリポジトリを作成してリモートにプッシュ
*リポジトリとは、コードやファイルを保存して共同作業できる場所
git init  
git add .  
git commit -m "Initial commit"  
git remote add origin https://github.com/XXXX/XXXXXX.git  
git push -u origin maste  

# ローカルでブランチ作成
git branch <ブランチ名>　\\ブランチ作成  
git checkout <ブランチ名>　\\ブランチの切り替え  
git branch -d <ブランチ名>　\\ブランチの削除  
git diff <ブランチ名><ブランチ名>　\\ブランチの比較  
git marge <ブランチ名>　\\ブランチのマージ  

-----------------------------------------------------

# リモートからクーロン
git clone https://github.com/XXXX/XXXXXX.git

# リモートにプッシュ
git push origin <ブランチ名>

# addの取り消し
git reser HEAD <ファイル名>

# リモートから変更を取得
git pull  
or  
git fetch  
git merge origin/master  

# コミットするためのファイルの登録
git add <ファイル名>

# ファイルの変更や追加をコミット
git commit -m "コミットメッセージ"

# ローカルの変更を確認
git status

# リモートとローカルのファイルの差分を抽出
git diff <ファイル名>

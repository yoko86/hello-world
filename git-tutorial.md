# 初期設定
git config --global user.name "XXXX"　\\名前を入力　\n
git config --global user.email "XXXX"　\\メールアドレスを入力 \n

# ローカルにリポジトリを作成してリモートにプッシュ
git init\n
git add .\n
git commit -m "Initial commit"\n
git remote add origin https://github.com/XXXX/XXXXXX.git\n
git push -u origin maste\n

# ローカルでブランチ作成
git branch <ブランチ名>　\\ブランチ作成\n
git checkout <ブランチ名>　\\ブランチの切り替え\n
git branch -d <ブランチ名>　\\ブランチの削除\n
git diff <ブランチ名><ブランチ名>　\\ブランチの比較\n
git marge <ブランチ名>　\\ブランチのマージ\n

-----------------------------------------------------

# リモートからクーロン
git clone https://github.com/XXXX/XXXXXX.git

# リモートにプッシュ
git push origin <ブランチ名>

# addの取り消し
git reser HEAD <ファイル名>

# リモートから変更を取得
git pull\n
or\n
git fetch\n
git merge origin/master\n

# コミットするためのファイルの登録
git add <ファイル名>

# ファイルの変更や追加をコミット
git commit -m "コミットメッセージ"

# ローカルの変更を確認
git status

# リモートとローカルのファイルの差分を抽出
git diff <ファイル名>

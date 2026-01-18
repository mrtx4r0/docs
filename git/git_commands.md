# git config
|操作|コマンド|備考|
|---|---|---|
|ユーザ名を設定する|git config --global user.name "USERNAME"|globalスコープはユーザ全体|
|メールアドレスを設定する|git config --global user.email "ADDRESS"|
|設定一覧を出力|git config --list|system, global, local全スコープの設定一覧を出す。スコープをしぼりたければ、--global等つける|

# git branch
|操作|コマンド|備考|
|---|---|---|
|ブランチを作成する|git branch main|
|チェックアウトしているブランチの追跡ブランチを設定する|git branch -u origin/main|
|チェックアウトしているブランチの追跡ブランチを設定する|git branch -u origin/feature||

# git switch
|操作|コマンド|備考|
|---|---|---|
|現在チェックアウトしているブランチを切り替える|git switch master main|

# git clone
|操作|コマンド|備考|
|---|---|---|
|任意のローカルディレクトリにリポジトリをブランチ指定してクローンする|git clone -b <ブランチ名> <リモートリポジトリのURL> <ローカルのディレクトリ名>||

# git add
|操作|コマンド|備考|
|---|---|---|
|対話モードでファイルごとに差分を確認してステージするかを決める|git add -p|git addで特定のファイルをステージしたいが、パスを指定するのが面倒なときに使える

# git push
|操作|コマンド|備考|
|---|---|---|
|mainブランチをリモートにPUSH＋今後はmainのpush/pullのデフォルトをorigin/mainに設定する|git push -u origin main|

# git reset
|操作|コマンド|備考|
|---|---|---|
|アンステージする|git reset <ファイル名>|

# git diff
|操作|コマンド|備考|
|---|---|---|
|作業ツリーとHEADの差分を表示する|git diff HEAD|
|ステージとHEADの差分を表示する|git diff --staged|

# git remote
|操作|コマンド|備考|
|---|---|---|
|リモートリポジトリに名前をつける|git remote add <リモート名> <リポジトリURL>||
|指定したリモート名のURLを変更|git remote set-url <リモート名> <新しいリポジトリURL>||

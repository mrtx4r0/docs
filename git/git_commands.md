||||
|---|---|---|
|ブランチを作成する|git branch main|
|現在チェックアウトしているブランチを切り替える|git switch master main|
|チェックアウトしているブランチの追跡ブランチを設定する|git branch -u origin/main|
|mainブランチをリモートにPUSH＋今後はmainのpush/pullのデフォルトをorigin/mainに設定する|git push -u origin main|
|任意のローカルディレクトリにリポジトリをブランチ指定してクローンする|git clone -b <ブランチ名> <リモートリポジトリのURL> <ローカルのディレクトリ名>||
|チェックアウトしているブランチの追跡ブランチを設定する|git branch -u origin/feature||
|対話モードでファイルごとに差分を確認してステージするかを決める|git add -p|git addで特定のファイルをステージしたいが、パスを指定するのが面倒なときに使える
|アンステージする|git reset <ファイル名>|
|作業ツリーとHEADの差分を表示する|git diff HEAD|
|ステージとHEADの差分を表示する|git diff --staged|

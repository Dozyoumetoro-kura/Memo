1.メールアドレスの設定
    git config --global user.name “ユーザ名”
    git config --global user.email アドレス
2.gitリポジトリ作成
    git init
    リポジトリを作成

    git init リポジトリ名
    ディレクトリを作り、リポジトリを中に作成
3.ステージング
    git add ファイル名
    ファイル名をステージング

    git add .
    すべてのファイルをステージング
4.gitignore
    git config --global core.excludesfile ~/ファイル名
    ファイル名をgitignoreファイルにする
    <書式>
        ファイル名
        ディレクトリ名/

    git status --ignored
    ファイルの状態を表示
5.コミット
    git commit -m "コミットメッセージ"
    コミットする
6.リモートリポジトリとの紐づけ
    git remote add origin "リモートリポジトリのURL"
    リモートリポジトリのURLを登録する
7.プッシュ
    git push origin master
    コミットされたものがリモートリポジトリにアップロードされる

## PJコマンド
```
#プロジェクトフォルダの作成
django-admin startproject プロジェクトフォルダ名
#開発用サーバーの立ち上げ
python manage.py runserver
#データベースの詳細
sqlite3 db.sqlite3
#マイグレーションファイルの新規作成または変更を反映
python manage.py migrate
#アプリケーションの作成
python manage.py startapp snippets
#SQLの自動生成
python manage.py makemigrations
#ユーザーの作成
python manage.py createsuperuser
#シェルの使用
python manage.py shell
#
```

## Gitコマンド
```
#Gitのリモートリポジトリをローカルリポジトリにコピー
git clone
#Gitのリモートリポジトリからローカルリポジトリとの差異を反映
Git pull
#リモートリポジトリに変更を反映すること
git push
#ブランチの切り替えや過去のファイルの復元
git checkout ブランチ名
#Gitでコミットした履歴を確認する
git log
#現在作業しているプロジェクトのファイル状態を確認
git status
#現在のカレントディレクトリ配下の全てファイルをステージエリアに追加する
git add .
#指定したファイルを追加
git add ファイル名
#コミットする
git commit -m "コミットメッセージ"
```
## memo
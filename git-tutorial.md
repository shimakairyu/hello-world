# git command
- git status
Gitリポジトリが適切に初期化されたことを確認する。作業ツリーの状態が表示される。
- git add
特定のファイルの変更の追跡を開始するようにGitに指示するためのコマンド。
- git commit
作業内容をスナップショットに保存する。コピーを新しいバージョンとしてリポジトリに格納する。
- git log
以前のコミットに関する情報を見ることが可能。メッセージや作成者、タイムスタンプ等の情報が出力される。
- git help
全てのコマンドに関する情報を取得できる。
- git branch
ブランチの作成
- git checkout
ブランチの切り替え
削除されたファイルの復旧
- git merge
ブランチをマージしてメインブランチに戻す。
- git clone
リポジトリをコピーする。
-git pull
リモートのリポジトリからローカルのものに変更をコピーする。
- git request-pull
変更をメインのコードにプルするよう求める。
- git remote
別の開発者のリポジトリをリモートとして設定。
- --amend
履歴を変更
-git reset
git rmによって削除されたファイルの復旧
- git revert
変更をコミットした後に、直前のコミットに戻す。

# git flow
gitフローとは、チームでGitを使う際に役立つ運用方法をまとめたツールのことであり、以下に示す5つのブランチが存在する。

1.マスターブランチ（master）<br>
2.開発ブランチ（develop）<br>
3.トピックブランチ（featureブランチ）<br>
4.リリースブランチ（releaseブランチ）<br>
5.ホットフィックスブランチ（hotfixブランチ）<br>

このようなブランチを用いることで、開発を効率的かつ安全に進めることが出来る。

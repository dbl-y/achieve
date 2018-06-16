# Gitチュートリアル
***
## Git コマンド
```
1. `git add "ファイル名"`` でステージング領域に上げる
1. リポジトリにコミットする
1. `git log` でリポジトリを確認する
1. 編集したら `git diff` で編集内容を確認
```

## Git コマンド（ブランチ）

1. `git branch` でブランチの一覧を確認
1. `git branch hoge` でブランチを追加
1. `git checkout hoge` でブランチを移動
1. `git checkout -b develop` でdevelopブランチを作成 && そこのブランチへ移動
1. ブランチをマージさせる


## ブランチの切り替えとかプルとか出来ない時
```
1. `git stash`で現在行っている作業を一時退避
1. `git reset --hard  HEAD`を実行
```

## ローカルでGitHubの操作をする
```
1.  git remote add origin コピーしたSSHプロトコルURL
2. 'git remote -v' 登録した送り先を確認
3. "git push origin master" リモートリポジトリ(GitHubリポジトリ)に送信
4. ""git push origin ブランチ名" ブランチをリモートリポジトリに送信
```

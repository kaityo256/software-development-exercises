# ソフトウェア開発演習

## 講義計画

1. バージョン管理とは
   - バージョン管理の必要性
   - Gitの概要
   - コマンドライン入門
   - 演習：Gitの初期設定
   - 演習：最初のリポジトリ作成(`git init`, `git add`, `git commit`)
1. Gitの基礎
   - 初期化(`git init`)
   - 状態の確認(`git status`)
   - ステージング(`git add`)
   - コミット(`git commit`)
   - 歴史の確認(`git log`)
   - 差分の確認(`git diff`)
1. ブランチの作成、切り替え、マージ
   - マージ(`git merge`)
   - Squash and merge
   - Fast forwardマージ
   - FFできる場合でもマージコミットを作る
   - 衝突の解決
1. リベース
   - コミットの並び替え(`git rebase -i`)
   - リベース中の衝突の解決
1. Gitのトラブルシューティング
   - `commit --amend`
   - `restore`
   - `restore --staged`
   - `stash`
1. Gitを使ったデバッグ
   - ソフトウェアのデバッグについて
   - `git blame`
   - `git bisect`
1. 公開鍵認証
   - 公開鍵認証の説明
   - 公開鍵認証について動作確認
   - GitHubのアカウント作成
   - 開通確認(`ssh -T`)
   - git cloneしてローカルで修正してpushの確認
1. リモートリポジトリの操作
   - 追跡ブランチの説明
   - `git remote`の操作
   - httpsでcloneしてからsshに修正
1. Issueによる課題管理
   - 演習：Issueとブランチの連携
   - 演習：KanbanによるProject管理
1. フォーク
   - forkしてからclone
   - プルリクエストの作成
1. GitHub Pagesのデプロイ
   - uv による環境構築
   - 機械学習の実行
   - Live Serverによるローカルの動作確認
   - GitHub Pagesへのデプロイ
1. ブラウザゲーム開発(1)
1. ブラウザゲーム開発(2)

## 方針

- 第1〜3回で、全員がGitの基本操作を一通り経験する。
- 第4〜7回で、ブランチ、マージ、リベース、復旧操作を段階的に扱う。
- 第8〜12回で、GitHub上の一人開発から複数人開発、デプロイへ進む。
- 第13・14回は、既存のゲーム作成を「環境構築・基本改造」と「独自開発・公開」に分割する。

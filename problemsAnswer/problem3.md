# 問題3
非常に長いコミット履歴を持つリモートレポジトリがある.

このレポジトリから最新の開発ブランチをビルドする目的のためにソースコードを取得したい
しかし, コミット数が多いレポジトリから通常のcloneを行った場合, 非常に時間がかかる.

ビルドするためだけの最新コミットをcloneするために必要な`git-clone`コマンドのオプションを記入せよ
ただし, 開発ブランチはmasterブランチではなく, 名前は`develop`であり,
リモートのurlは https://github.com/d-o-n-u-t-s/git-school.git とする.

# 解答
$ git clone --depth=1 https://github.com/d-o-n-u-t-s/git-school.git develop
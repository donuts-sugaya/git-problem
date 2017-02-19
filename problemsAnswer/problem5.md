# 問題5
gitでファイルを無視するには通常`.gitignore`などを使うが,  
すでにgit管理化にあるファイルを無視したい。


`git update-index`のオプションを使って、特定のファイルを無視してみましょう.

（やり方は複数あります. 時間がある人は, それぞれの違いも調べてみましょう．）

# 解答
$ git update-index --assume-unchanged 特定のファイル
# 問題4
レポジトリ内の全てのcatをdogに一斉に置換したい.  


`git grep`などを使って一行のコマンドで一斉に置換してみよう.

# 解答
$ git grep -l "cat" | xargs sed -i "" "s/cat/dog/g"
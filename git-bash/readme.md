# Git bash 構築メモ

## 補完を有効にする
 - MinGWをインストールしてGit bashでのみ環境変数を参照するようにする  
   https://ktrysmt.github.io/blog/use-mingw-with-git-bash-on-windows/

 - makeコマンドのインストールとリネーム
   mekeコマンドを以下のコマンドでインストールして、
   mingw-get install mingw32-make  
   C:\MinGW\bin にある mingw32-make.exe をコピーして make.exe にリネームしておく。

 - 管理者権限でgit bash を起動して以下の手順を行う
   Git Bash for Windows で bash-completion を使う  
   https://zenn.dev/sprout2000/articles/e80168e97fc306

 - bash_completionを読み込む  
   /usr/local/share/bash-completion/bash_completion にファイルが作られているので読み込む
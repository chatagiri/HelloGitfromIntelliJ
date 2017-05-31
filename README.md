# HelloGitfromIntelliJ
Testing uses a Git&amp;Github from IntelliJ IDEA

#IntelliJ上でターミナルを開く
エディタ上にてAlt+F12でローカルプロジェクトのパスをカレントディレクトリとしてターミナルを開ける
gitインスコ済み&amp;git.exeのパスを指定済み(後述)であればここからコマンド打ち込んでgitできる

#IntelliJのターミナルでGitする設定
File -> Settings -> Versionコントロールタブを開く
サイドメニューからGitタブを開く
"Path to Git Executable" テキストフィールドからGit.exeを指定する
エディタでAlt+F12してターミナルからgit使えれば成功

#IntelliJからGithubする設定
File -> Settings -> Versionコントロールタブを開く
サイドメニューからGitHubタブを開く
2行目右端，"CreateAPIToken"押す
作成済みGitHub垢のユーザ名，パスワードでログイン
タブ閉じるor閉じたら一番下のOK押すのを忘れない

#IntelliJのGUIからGitHubする
Projectを右クリック -> "Git" -> "Commit Directory"
CommitMessageを入力して右下Commit押す






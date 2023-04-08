# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリは複数人で共有できるネット上にあるリポジトリ
- ローカルリポジトリは個人のパソコン上に配置されたリポジトリ


## プッシュとマージの違いは何でしょうか？
- プッシュはローカルリポジトリで変更した内容をリモートリポジトリに反映させるコマンド
- マージはローカルリポジトリで内容を変更したブランチをローカルリポジトリ内にある他のブランチに反映させるコマンド


## コミットとプッシュの違い
- プッシュはローカルリポジトリで変更した内容をリモートリポジトリに反映させるコマンド
- コミットはローカルリポジトリで変更した内容をローカルリポジトリに保存するコマンド


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 誰がいつみてもどこを変更したのかを分かりやすく記載する


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカル内で内容をマスターブランチに反映させて、ローカルのマスターからリモートのマスターに反映させるのがローカルでマージするフロー
- プルリクエストの場合は、サブブランチをリモートにあげ、それをマスターに反映させる権限を持った人が許可するとリモートのマスターブランチに反映される


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 方法は三つあり、いづれかで対処する
1.先にマージされた変更内容を取り込む
2.後にマージしようとしている変更内容を取り込む
3.どちらの変更内容も取り込む

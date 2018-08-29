作業内容を記録する
==================

作業した内容をリポジトリに記録します。例えるならば、Steins;Gate でストーリーを進めた後、セーブをするようなものです。

SourceTree でのやり方
---------------------

リポジトリ内にファイルを新しく作成した場合 SourceTree 上ではファイル名の横に「？」が付く形で表示されます。これは、ファイルがまだバージョン管理されてない事を示しています。

![変更したファイルにチェックを付ける前](ch3/git-commit/source-tree/add-before.jpg)

この状態でファイル名の左横にあるチェックボックスにチェックを付けると「ステージングエリア」といわれるところにファイルが移動します。

![変更したファイルにチェックを付けた後](ch3/git-commit/source-tree/add-after.jpg)

移動した状態で、画面の下部にある「コミットメッセージ」と書かれている場所に任意のメッセージを入力します。

![コミットメッセージを入力する前](ch3/git-commit/source-tree/commit-before.jpg)

入力した後「コミット」ボタンを押すと、作業した内容がリポジトリに記録されます。なお、初回以降は画面上部にある「コミット」ボタンを押す事により、メッセージを入力できます。

![コミットした後](ch3/git-commit/source-tree/commit-after.jpg)

ちなみに、コミットメッセージなどが表示されている場所の「ラベル」部分に「HEAD」という記載がありますが、これは「現時点でどのブランチにいるかを判別する情報」です。つまり、世界線の観測ができているという事で、これを例えるならば、ダイバージェンスメーターです。

GitHub for Windows (Mac) でのやり方
-----------------------------------

GitHub for Windows (Mac) では、リポジトリ内にファイルを新しく作成した場合、画面上部に「1 Change」と表示され、またファイル名の横にあるチェックボックスにチェックが付いた状態になります。

![追加したファイルをコミットする前](ch3/git-commit/github-app/git-commit-before.jpg)

GitHub for Windows (Mac) の場合「ステージングエリア」にファイルを移動する必要はなく、そのまま画面下部でコミットメッセージを書く事ができます。

![コミットメッセージを入力している最中](ch3/git-commit/github-app/git-commit-message.jpg)

コミットメッセージを書いて「Commit to master」というボタンを押すと、作業した内容がリポジトリに記録されます。

![コミットした後](ch3/git-commit/github-app/git-commit-after.jpg)
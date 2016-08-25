===========
Sphinx導入
===========
自宅PCにSphinxをインストールしてみた。適当なメモとかはここに書くので、良さそう。

導入経緯
=========
* 雑記を書く場所が適当にほしい
* ブログはめんどくさいし、いちいちユーザー登録するのがめんどくさい
* 仕事で使えそうで、適当に勉強がてら使えるものがほしい

利用エディタ
=============
| Atom + rst-preview-pandoc
| リアルタイムプレビューがあると、格段に使いやすい。

rst-Preview-Pandoc
-------------------
| AtomでreSTのプレビュー機能を持ったツールないかなーと思ったらあったので導入。
| reST --Pandocで変換--> MarkDown --> Preview な感じ

メモ
=============
ビルド先をDropBoxのPublicにしたいけど、うまくいかないのはなぜ。
結局ローカルでもデータを持っておきたいので、DropBoxにコピーするコマンドをmake.batに追加して解決

参考にしたページ
=================

* Sphinxの導入方法はここを参考に
 * http://sphinx-users.jp/
* Sphinxの文章の書き方とかファイル構成はここを参考にした
 * http://planset-study-sphinx.readthedocs.io/ja/latest/index.html
* reStructuredTextのチートシートはこれを見てる
 * http://pekopeko1.bitbucket.org/blog/html/2012/12/02/rest_syntax.html

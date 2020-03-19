# setup
### Do not use this repository if you are not tatsu.
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/xtatsux/setup/master/bootstrap)"
```
# My Enviroment Setup Doc

It mainly assumes a Mac environment.

## Script外の設定変更

シェルの変更については以下リンクを参照
[Macでログインシェルを確認/変更するいくつかの方法](https://rcmdnk.com/blog/2015/05/25/computer-mac-bash-zsh/)

Touch Barのカスタマイズ方法
[MacBook Pro で Touch Bar を使う方法](https://support.apple.com/ja-jp/HT207055)

>Control Strip をカスタマイズする
>Control Strip のボタン (Siri のボタンなど) を追加または削除したり、並べ替えたりすることもできます。
>カスタマイズに対応した (Finder などの) App で、「表示」>「Touch Bar をカスタマイズ」の順に選択します。Touch Bar の Control Strip 部分をタッチして、Control Strip のカスタマイズ画面に切り替えます。カーソルを使って、希望の項目をディスプレイから下方向に Touch Bar へとドラッグしてください。Control Strip の中で項目を左右にドラッグして並べ替えたり、Touch Bar の上にドラッグして取り除いたりすることができます。設定が終わったら、Touch Bar の「完了」をタップするか、画面の「完了」をクリックします。
>システム環境設定の「キーボード」セクションで「Control Strip をカスタマイズ」をクリックして、Control Strip のカスタマイズモードに切り替えることもできます。

#### Other

* Setup Terraform
  * [tfenvを用いたterraformのインストール方法](https://qiita.com/sasshi_i/items/b5117d51fed800fa6b09)
* iTerm font setting:link is my notion note.
  * [iTerm2のフォントを見やすく変更してみた - Qiita](https://www.notion.so/xtatsux/iTerm2-Qiita-7783e0ada3764a729581c02d6af763bd)
* sudoをTouchIDで利用できるようにする→セットアップスクリプトに組み込んだ
  * [MacのTerminalでsudo実行時にタッチIDを使用する方法 ｜ Developers.IO](https://www.notion.so/xtatsux/Mac-Terminal-sudo-ID-Developers-IO-76d80ecc31924d74a03c83843a37c7de)

## Tips

## Tools, I am using recently

* Browser
    * Safari
    * [Google Chrome](http://www.google.co.jp/intl/ja/chrome/browser/)
    * [Vivaldi](https://vivaldi.com/ja/)
* Editor
    * [Visual Studio Code](https://code.visualstudio.com)
* development tools
    * python
        * virtualenv経由で利用
    * ruby
        * rvm
        * compass
    * npm module (後々setup.shで処理するようにする予定)
        * yo (yeoman)
        * bower
        * grunt-cli (grunt)
        * topojson
      * Terraform
        * tfenv経由で利用
* Util
    * [Atok](https://www.justsystems.com/jp/products/atokmac/)
    * [Alfred](https://www.alfredapp.com)
    * [Bartender](https://www.macbartender.com)
    * [Omnifocus](https://www.omnigroup.com/omnifocus)
        * タスク管理ツール。ないと死ぬ。
    * [Evernote](https://evernote.com)
        * メモ全般の管理→Notionにほぼ移行
    * [Notion](https://www.notion.so/)
    * [Ulysses](https://ulysses.app)
    * [1Paassword](https://1password.com)
    * [SourceTree](https://ja.atlassian.com/software/sourcetree)
    * [TexExpander](https://textexpander.com)
    * [Fantstical3](https://flexibits.com/jp/fantastical)
    * [Spark](https://sparkmailapp.com/ja)
    * [iTerm](https://www.iterm2.com)
    * [Better Touch Tools](https://www.boastr.net)
        * 便利ツール
    * [Box Drive](https://www.box.com/resources/downloads/drive)
        * Storage Service
        * Box syncからBox Driveに変更
        * ついでにBox Editも導入。
    * [StartupSound.prefPane](http://www5e.biglobe.ne.jp/~arcana/StartupSound/BETA/)
    * [Paste](https://pasteapp.me)
    * [Karabiner](https://pqrs.org/osx/karabiner/)
        * EISUU to Command_L
        * KANA to Command_L
    * Jump Desktop
    * OneDrive
    * Scrivener
    * The Unarchiver
    * Notability
    * GoodNotes5
    * Slack
    * Day one
    * PopClip
    * tmux-powerline (setup.shで処理)
        * ref:[モテるtmux - まつぼ x Web](http://matsu.teraren.com/blog/2013/02/10/moteru-tmux-powerline/)
    * oh-my-zsh (setupu.shで処理)
        * ref：[Mac OS X で zsh ＋ oh-my-zsh の環境を作って一通り設定するまで - Qiita](http://qiita.com/udzura/items/0d08d71d809bfd8c5981)
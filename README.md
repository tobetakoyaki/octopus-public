# octopus-public
## スタイルファイルに関する説明
このレポジトリは，普段私が用いている私製スタイルファイルを紹介する目的で作成されました．

私製スタイルファイルとして公開しているものは以下の4つです．

- octopus.sty
- octopusbeamer.sty
- octopuscommand.sty
- octopus-kanbun.sty

これらのスタイルファイルは，作成したい文書の形式によって異なるものが使用されます．具体的には，以下のような対応をなします．

- octopus.sty <- 通常のドキュメント
- octopusbeamer.sty <- 発表などのスライド
- octopus-kanbun.sty <- 漢文を用いたドキュメント

なお，octopuscommand.styは上2つのスタイルファイルの内部で呼び出され，更に詳細な各種コマンドを定義するのに用いられています．

これらの，特にoctopus.styとoctopuscommand.styの詳細な使用方法や出力例はexample.texを参照ください．なお，このtexファイルをコンパイルしてpdf化したものはReleasesにて公開されていますので，そちらも併せてご確認ください．

## .latexmkrcなどについての説明
このレポジトリでは，example.texを更新すると，新たにpdfをリリースする機構を採用しています．以上までに登場した「example.tex」および4つのstyファイル以外のファイルやディレクトリはすべてそれを実現するためのものであり，スタイルファイルの定義内容に直接関係するものではありません．

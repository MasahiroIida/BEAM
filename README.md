# 【BEAMプロジェクトのRepository】

BEAMプロジェクト：機械学習による画像認識の開発を行うプロジェクト。  
プロジェクト名は作業中にJIM BEAMを飲みながら作業をしていたためそこから取りました。  
  
  
## ■プロジェクトの開発環境  
- Pythonは3.6.8を採用する。(tensorflowがwindows版だとpython3.7.Xに対応していないため)  
下記リンクからインストールすること。  
32bitOSの場合にはWindows x86 web-based installer  
64bitOSの場合にはWindows x86-64 web-based installer  
https://www.python.org/downloads  
  
- パッケージ管理はpipenvを採用する。  
pythonインストール後、コマンドプロンプトでプロジェクト直下にて「pipenv install」を実行する。  
これで必要なライブラリ群がインストールされる。  
  
- IDEはEclipse+PyDev。Eclipseのバージョンは任意。下記サイトを参考にすること  
https://qiita.com/takeyamajp/items/03cb19ee24a0ec580d64  
  
  
## ■プロジェクトのルール  
作業時に引用した、あるいは非常に参考となったサイトがある場合、URLをWikiに記載すること。  
  
pipenvでライブラリ管理を行うため。ライブラリをインストールする際はプロジェクト直下で「pipenv install XXX」にてインストールを行うこと。  
pipenvについては下記参照  
https://qiita.com/y-tsutsu/items/54c10e0b2c6b565c887a  
  
  
## ■使用ライブラリ(随時更新)  
- pipenv  
ライブラリ管理。node.jsでいうとこのnpmみたいなもの。  
- Pillow  
画像の操作。  
- Keras  
ディープラーニング用ライブラリ  
- Tensorflow  
  よく分からないけどKeras動かすのに必要
  
  
## ■その他
前提となる事項、ルールがある場合はREADMEに記載すること。

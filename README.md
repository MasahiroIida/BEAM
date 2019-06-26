# 【BEAMプロジェクトのRepository】

BEAMプロジェクト：機械学習による画像認識の開発を行うプロジェクト。  
プロジェクト名は作業中にJIM BEAMを飲みながら作業をしていたためそこから取りました。  
  
  
## ■プロジェクトの開発環境  
1. Pythonは3.6.8を採用する。(tensorflowがwindows版だとpython3.7.Xに対応していないため)  
下記リンクからインストールすること。  
32bitOSの場合にはWindows x86 web-based installer  
64bitOSの場合にはWindows x86-64 web-based installer  
https://www.python.org/downloads  
  
2. パッケージ管理はpipenvを採用する。  
pythonインストール後、コマンドプロンプトで「pip install pipenv」でpipenvをインストールする。  
  
3. IDEはpycharm。下記からコミュニティ版をインストールすること  
https://qiita.com/takeyamajp/items/03cb19ee24a0ec580d64  
  

4. 環境構築  
pycharmで「BEAM\project-beam\2q-project」をプロジェクトに指定して起動する  
下記手順で初期構築  
```
Terminalで以下を行う。
① 「py -m site --user-site」
      出力例は次のとおり。
      C:\Users\jetbrains\AppData\Roaming\Python\Python37\site-packages
② このパスの site-packages を Scripts に置き換えて、PATH 変数に追加する
      例は以下の通り。
      「set PATH "%PATH%;C:\Users\jetbrains\AppData\Roaming\Python\Python37\Scripts"」
③ 必要な環境変数を追加
      「set PIPENV_VENV_IN_PROJECT=1」
      「set PIPENV_IGNORE_VIRTUALENVS=1」
④ ライブラリ群をインストールする
      「pipenv install」
```
  
## ■プロジェクトのルール  
作業時に引用した、あるいは非常に参考となったサイトがある場合、URLをWikiに記載すること。  
  
- ライブラリのインストールは「pipenv install XXX」で  
pipenvでライブラリ管理を行うため。ライブラリをインストールする際はpycharmのTerminalから「pipenv install XXX」にてインストールを行うこと。  
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
- scikit-learn  
  コメントは後で書く  
- matplotlib  
  コメントは後で書く  
  
  
## ■その他
前提となる事項、ルールがある場合はREADMEに記載すること。

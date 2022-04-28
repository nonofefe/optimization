# SYSRDC Academy（組合せ最適化入門）

SYSRDC Academy（組合せ最適化入門）で実施する演習問題を整理します。

## 概要

サンプルコード（[tutorial.ipynb](src/tutorial.ipynb)）を基に演習問題（[problem.html](doc/problem.html)）を解いてください。  
サンプルコードを用いずにオリジナルで解いても構いません。また、何から手を付けてよいか分からない方は、ヒント（[hint.ipynb](src/hint.ipynb)）を参照してください。  
提出の際は、作成した結果データに対して提出用ファイル作成（[submit.ipynb](src/submit.ipynb)）を行ってください。

各ファイルはipynb形式で記述しています。演習環境については各自にお任せしますが、例えば[Google Colab](https://colab.research.google.com/?hl=ja)を使用するとパッケージインストール不要で実行可能のため便利です。Google Colabはブラウザ上でpythonの記述と実行ができるサービスで、Googleアカウントがあれば無料で使用することができます。

## フォルダ構成

- [data](data)
  - [in](data/in) - 入力データ
    - [companies.csv](data/in/companies.csv) - 会社情報  
    会社ごとの番号$CID$、位置$\left(X, Y\right)$、プレゼン希望時間帯$\left[EPT, LPT\right]$、プレゼン時間$PT$、プレゼン資料重量$PW$を格納する。
  - [out](data/out/) - 出力データ
    - [97947126_username.csv](data/out/97947126_username.csv) - 提出用ファイルフォーマット  
    作成した結果データに対して、[submit.ipynb](src/submit.ipynb)を適用する。
    - [sample_res.csv](data/out/sample_res.csv) - 結果データ  
    営業番号$SID$、会社番号$CID$（訪問順）を出力する。
- [doc](doc)
  - [problem.html](doc/problem.html) - 演習問題（html形式）
  - [problem.md](doc/problem.md) - 演習問題（md形式）
- [src](src)
  - [hint.ipynb](src/hint.ipynb) - ヒント
  - [submit.ipynb](src/submit.ipynb) - 提出用ファイル作成
  - [tutorial.ipynb](src/tutorial.ipynb) - チュートリアル

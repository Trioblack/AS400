Sorry Japanese only.
  English version is also I write someday.

  AS400 コンパイルツール

  ====

  これはAS400用のツールです。
  指定したソースファイル内のメンバーを、一括でコンパイルすることができます。全てCLPで作成しています。
  オブジェクトの生成先や、オブジェクトタイプを指定することも可能です。

  今後の展望として、メンバーの接頭辞を指定してコンパイルできるようにしたいです。


## Usage

  使用例
  CALL CRTPGM PARM('ソースライブラリー名' 'ソースファイル名' 'オブジェクトライブラリー' 'オブジェクトタイプ')

  ソースライブラリー名 - コンパイルするライブラリー
  ソースファイル名 - コンパイルするソースファイル名
  オブジェクトライブラリー名 - オブジェクトの生成先ライブラリー名。' 'で省略可能。
  オブジェクトタイプ - コンパイルしたいオブジェクトタイプ。' 'で省略可能。
                指定できるタイプは、'RPGLE', 'CLP', 'PF', 'LF', 'DSPF', 'PRTF'です。現状では、このタイプ以外のメンバーはコンパイルされません。


## Install

  データ転送なりコピペなり、好きな方法で。


## Licence

  FLOSS
  商用・非商用問わず、好きなように使って下さい。殆ど需要は無いと思いますが...。


## Author

  [facilita](https://github.com/facilita)
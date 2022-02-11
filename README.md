# Python 学習会用テキスト
本テキストは東京大学の授業で使われたテキストを修正したものです。
授業の対象は、全学部の後期課程の学生で、
他に工学部と情報理工学系研究科の知能社会情報学特別講義Ⅶで、Pythonプログラミング入門としても開講されました。
テキストは jupyter notebook として公開されていますが、教材講義動画が公開されていないようです。

## Pythonの入門サイト
オンラインで閲覧できるPythonの入門サイトをまとめました。

### Python入門
[Python入門](https://www.python.ambitious-engineer.com/introduction-index)<br>
[索引](https://www.python.ambitious-engineer.com/introduction-index)

#### Pythonの基礎
- はじめに
- Python3のインストール(Linux、Mac)
- Python3のインストール（Windows）
- Pythonの実行方法
- print関数
- コマンドライン引数

#### 変数の型
- 識別子
- 変数の基本
- 数値型の変数
- 基本的な数値の演算
- bool(真理値)型
- None型
- シーケンス
- list(リスト)型 初期化と基本操作
- list(リスト)型の更新と削除
- list(リスト)型のソート
- タプル(tuple)型
- range型
- str(文字列)型
- シーケンス共通演算
- set型の基本
- set型と集合演算
- dictionary(辞書)型
- イミュータブルオブジェクトとid関数
- 変数の型を判定する

#### 制御構文
- 比較演算
- if文(条件文)
- for文
- 辞書のループ処理
- リスト内包表記
- while文
- pass ブロック内で何も処理を行わない場合

#### 関数
- 関数の定義
- デフォルト引数
- キーワード引数
- 可変長引数
- global宣言
- 関数オブジェクト
- 内部関数（inner function）とnonlocal宣言
- ジェネレータ
- lambda式
- デコレータ
- 関数アノテーション

#### クラスとオブジェクト
- オブジェクトとは
- クラスの基本
- オブジェクトへの属性追加
- クラスオブジェクト
- クラス変数
- クラスメソッドとスタティックメソッド
- クラスの継承
- プライベートメンバ
- プロパティ
- クラスデコレータ
- 基本的な特殊メソッド
- ディスクリプタ
- __new__
- 演算の定義
- 変数の型を判定する その2 type関数

#### 例外
- 例外処理
- 例外を発生させる

#### ファイル入出力
- ファイルの読み書き
- ファイルシステムの操作

#### 文字列操作
- 文字列操作の基本
- 文字列の判定系メソッド
- 文字列のフォーマット（値の埋め込み）

#### モジュール
- モジュール
- __pycache__と.pycファイル
- モジュールの実行と__name__

#### 標準ライブラリ
- datetimeモジュールとdatetime型
- datetimeモジュールとdate型/time型
- jsonモジュール JSONのエンコードとデコード
- csvモジュール CSVファイルの読み書き
- reモジュール 正規表現
- configparser 設定ファイルの読み込み
- traceback スタックトレースの取得
- copyモジュール 浅いコピーと深いコピー

#### ログ
- logging 基本的な使い方
- logging ログの階層
- logging 設定ファイル

#### 単体テスト
- unittest 単体テスト入門 その1 基本的な使い方
- unittest 単体テスト入門 その2 テストパッケージとテストスイート

#### 組み込み関数
- 代表的な組み込み関数
- 数学系の組み込み関数
- map関数 リストの全て要素に対して同じ処理を行う
- filter関数 リストから条件を指定して抽出する
- zip関数 複数のリストを同時にループで処理する
- reduce関数 シーケンスの値を累積的に集約する
- 組み込み型の関数とstr
- hasattr 指定の属性を持つかどうかを検査する
- setattr属性の追加

### とほほのPython入門
[とほほのPython入門](https://www.tohoho-web.com/python/)

- 概要
 - Pythonとは
 - 参考リンク
 - インストール
 - Pythonの実行
 - 対話モード
 - Python 3
- 構文
 - Hello world!
 - 文・式
 - コメント(#)
 - インデント
 - エンコードルール(coding:)
- 数値・文字列・型
 - 整数(int)
 - 長整数(long)
 - 浮動少数点数(float)
 - 虚数(complex)
 - 論理値(bool)
 - 文字列(str)
 - Unicode文字列(unicode)とバイト列(bytes)
 - Shift_JIS/EUC/JISとの変換
 - エスケープシーケンス(\x)
 - 文字列のフォーマット(%)
- 変数・定数
 - 変数
 - 定数
 - ドキュメントストリング(__doc__)
- リスト・タプル・辞書
 - リスト(list)
 - タプル(tuple)
 - 辞書(dict)
 - リスト関数(map(), filter(), reduce())
 - リストの内包表記
 - セット(set)
- 演算子
 - 代数演算子(+, -, *, /, %, **, //)
 - ビット演算子(~, &, |, ^, <<, >>)
 - 代入演算子(=, +=, -=, *=, /=, %=, **=, //=, &=, |=, ^=, <<=, >>=)
 - 比較演算子(==, !=, <, >, <=, >=, is, is not, in, not in)
 - ブール演算子(and, or, not)
 - 条件演算(if else)
 - 文字列演算(+, *, [n:m])
- 制御構文
 - もし～ならば(if, else, elsif)
 - ～のあいだ(while, else)
 - ～のあいだ(for, in)
 - ループを抜ける(break)
 - ループを繰り返す(continue)
 - 例外処理(try, except, else, finally, raise)
 - with構文(with)
 - アサーション文(assert)
 - パス文(pass)
 - デリート文(del)
 - print文(print)
 - exec文(exec)
- 関数
 - 関数(def)
 - グルーバル変数(global)
 - ラムダ式(lambda)
 - イテレータ(iterator)
 - ジェネレータ(yield)
 - デコレータ(@)
- クラス
 - クラス(class)
 - クラス変数・インスタンス変数(attribute)
 - メソッド(method)
 - アクセス制限(_, __)
 - コンストラクタ(__init__)
 - デストラクタ(__del__)
 - 文字列化(__str__)
 - 継承(inheritance)
 - 親クラス(super())
 - 多重継承
 - クラス階層
- パッケージとモジュール
 - モジュール
 - パッケージ
 - インポート文(import)
 - パッケージ名(__package__)
 - ファイル名(__file__)
 - モジュール名(__name__)
 - ビルトインモジュール(__builtin__)
- Python関連ツール
 - ツール集
 - Sphinx

### Pythonプログラミング入門
[Pythonプログラミング入門](https://utokyo-ipp.github.io/)
▲で始まる項目は授業では扱いません。興味にしたがって学習してください。
ノートブック全体に▲が付いているものもありますので注意してください。
1-0. Colaboratoryによるノートブックの使い方
- Colaboratoryの立ち上げ
- ノートブックのアップロード
- 教材のオープン
- ノートブックのダウンロード
- ノートブックのアップロード（再び）
- ノートブックの作成
- ノートブックの操作
- セル
- セルの編集
- セルの挿入
- セルの実行が止まらないとき
- セルの操作
- ノートブックの参照
1-1. 数値演算
- 簡単な算術計算
- コメント
- 整数と実数
- 演算子の優先順位と括弧
- 算術演算子のまとめ
- 空白
- エラー
- 数学関数（モジュールのインポート）
1-2. 変数と関数の基礎
- 変数
- 関数の定義と返値
- ローカル変数
- print
- print と return
- コメントと空行
- 関数の参照の書き方
- ▲グローバル変数
1-3. 論理・比較演算と条件分岐の基礎
- if文による条件分岐
- 様々な条件
- 真理値を返す関数
- オブジェクト
- None
- ▲条件として使われる他の値
- ▲再帰
1-4. デバッグ
- 文法エラー：Syntax Errors
- 実行エラー：Runtime Errors
- 論理エラー：Logical Errors
- print によるデバッグ
- コーディングスタイル
- ▲assert文によるデバッグ
2-1. 文字列 (string)
- 文字列とインデックス
- 文字列とスライス
- 空文字列
- 文字列の検索
- ▲エスケープシーケンス
- バックスラッシュの表示と入力
- 文字列の連結
- 文字列とメソッド
- 文字列の比較演算
- 初心者によくある誤解 — 変数と文字列の混乱
2-2. リスト (list)
- リストとインデックス
- 多重リスト
- リストに対する関数・演算子・メソッド
- 破壊的（インプレース）な操作と非破壊的な生成
- リストを操作するメソッドなど
- タプル (tuple)
- 多重代入
- リストやタプルの比較演算
- for文による繰り返しとリスト・タプル
- for文による繰り返しと文字列
- for文によるリスト初期化の短縮記法
- ▲オブジェクトの等価性と同一性
2-3. 条件分岐
- インデントによる構文
- if … else による条件分岐
- if … elif … else による条件分岐
- ▲複数行にまたがる条件式
- if … elif … else における条件の評価
- or もしくは and で結合された条件の評価
- ▲3項演算子（条件式）
3-1. 辞書 (dictionary)
- 辞書のメソッド
- 辞書とリスト
3-2. 繰り返し
- for文による繰り返し
- for文による繰り返しと辞書
- range
- range とリスト
- for文の入れ子
- for文の計算量
- enumerate
- in
- while文による繰り返し
- 制御構造とreturn文
- break文
- continue文
- ▲for文とwhile文における else
- pass文
3-3. 関数
- 関数の定義
- 引数
- 返値
- 複数の引数
- 変数とスコープ
- ▲キーワード引数
- ▲引数の初期値
- ▲可変長引数
- ▲辞書型の可変長引数
- ▲引数の順番
- ▲変数としての関数
4-1. ファイル入出力の基本
- ファイルのオープン
- ファイルのクローズ
- 行の読み込み
- ファイル全体の読み込み
- 編集中のファイルの動作
- ファイルに対するwith文
- ファイルへの書き込み
- ファイルの読み書きにおける文字コード指定
- 改行文字の削除
4-2. イテレータ
- next
- for文による繰り返しとファイルオブジェクト
- iter
- イテラブル
- イテレータを返す enumerate
4-3. コンピュータにおけるファイルやディレクトリの配置
- カレントディレクトリ
- 相対パスと絶対パス
- 木構造によるデータ表現
5-1. モジュールの使い方
- モジュールのインポート
- from
- as
5-2. モジュールの作り方
- モジュールファイル
- 自作モジュールの使い方
5-3. NumPyライブラリ
- 配列の構築
- 配列要素を生成する構築関数
- 配列要素の操作
- 要素毎の演算
- よく使われる配列操作
- 配列の保存と復元
- ▲真理値配列によるインデックスアクセス
- ▲線形代数の演算
6-1. 内包表記
- リスト内包表記
- 内包表記の入れ子
- ▲条件付き内包表記
- ▲セット内包表記
- ▲辞書内包表記
- ▲ジェネレータ式
6-2. 高階関数
- max
- sorted
- ラムダ式
- リストからイテラブルへ
- map
- filter
6-3. クラス
- クラス定義
- 初期化と属性
- 継承
- 特殊メソッド
- 継承による振舞いの改変
- ▲with文への対応
7-1. pandasライブラリ
- シリーズとデータフレーム
- シリーズ (Series) の作成
- データフレーム (DataFrame) の作成
- CSVファイルからのデータフレームの作成
- データの参照
- データの条件取り出し
- 列の追加と削除
- 行の追加と削除
- データの並び替え
- データの統計量
- ▲データの連結
- ▲データの結合
- ▲データのグループ化
- ▲欠損値、時系列データの処理
7-2. scikit-learnライブラリ
- 機械学習について
- 教師あり学習
- 教師なし学習
- データ
- モデル学習の基礎
- 教師あり学習・分類の例
- 教師あり学習・回帰の例
- 教師なし学習・クラスタリングの例
- 教師なし学習・次元削減の例
- ▲Jupyter Notebook の使い方
- セル
- コマンドモード
- 編集モード
- （注意）Shift-Enterに反応がなくなったとき
- ▲セット (set)
- セットの組み込み関数
- 集合演算
- 比較演算
- セットのメソッド
- ▲再帰
- 再帰関数の例：接頭辞リストと接尾辞リスト
- 再帰関数の例：べき乗の計算
- 再帰関数の例：マージソート
- ▲簡単なデータの可視化
- matplotlib
- 折れ線グラフ
- 散布図
- 棒グラフ
- ▲CSVファイルの入出力
- CSV形式とは
- CSVファイルの読み込み
- CSVファイルに対するfor文
- CSVファイルに対するwith文
- CSVファイルの書き込み
- ▲Bokehライブラリ
- 線グラフ
- 散布図
- 棒グラフ
- ヒストグラム
- ヒートマップ
- グラフのファイル出力
- ▲Pythonスクリプトとコマンドライン実行
- コマンドライン実行の具体例
- コマンドライン引数
- モジュールのコマンドライン実行
- ソースファイル先頭部分にある宣言
- ▲Matplotlibライブラリ
- 線グラフ
- 散布図
- 棒グラフ
- ヒストグラム
- ヒートマップ
- グラフの画像ファイル出力
- ▲正規表現
- 正規表現の基本
- 文字クラス
- 正規表現に関する基本的な関数
- その他の反復演算
- メタ文字
- 正規表現のエスケープシーケンス
- 正規表現に関する関数とメソッド
- 索引

### @IT atmarkIT
[Python入門](https://atmarkit.itmedia.co.jp/ait/articles/1904/02/news024.html)
1. ［Python入門］Pythonってどんな言語なの？
2. ［Python入門］Hello Python：一番簡単なプログラムを作ってみよう
3. [［Python入門］数値と算術演算](https://atmarkit.itmedia.co.jp/ait/articles/1904/09/news016.html)
4. [［Python入門］変数とは](https://atmarkit.itmedia.co.jp/ait/articles/1904/12/news028.html)
5. [［Python入門］文字列の基本](https://atmarkit.itmedia.co.jp/ait/articles/1904/16/news013.html)
6. [［Python入門］文字列の操作](https://atmarkit.itmedia.co.jp/ait/articles/1904/19/news027.html)
7. [［Python入門］文字列の書式指定](https://atmarkit.itmedia.co.jp/ait/articles/1904/23/news015.html)
8. [［Python入門］コメント](https://atmarkit.itmedia.co.jp/ait/articles/1904/26/news026.html)
9. [［Python入門］if文による条件分岐](https://atmarkit.itmedia.co.jp/ait/articles/1905/07/news019.html)
10. [［Python入門］for文による繰り返し処理](https://atmarkit.itmedia.co.jp/ait/articles/1905/10/news023.html)
11. [［Python入門］while文による繰り返し処理](https://atmarkit.itmedia.co.jp/ait/articles/1905/14/news018.html)
12. [［Python入門］関数の基本](https://atmarkit.itmedia.co.jp/ait/articles/1905/17/news020.html)
13. [［Python入門］関数の引数](https://atmarkit.itmedia.co.jp/ait/articles/1905/21/news009.html)
14. [［Python入門］関数のローカル変数とスコープ](https://atmarkit.itmedia.co.jp/ait/articles/1905/24/news019.html)
15. [［Python入門］ローカル関数とラムダ式](https://atmarkit.itmedia.co.jp/ait/articles/1905/28/news017.html)
16. [［Python入門］リストの基本](https://atmarkit.itmedia.co.jp/ait/articles/1905/31/news015.html)
17. [［Python入門］リストの操作](https://atmarkit.itmedia.co.jp/ait/articles/1906/04/news009.html)
18. [［Python入門］リストと繰り返し処理](https://atmarkit.itmedia.co.jp/ait/articles/1906/11/news007.html)
19. [［Python入門］タプル](https://atmarkit.itmedia.co.jp/ait/articles/1906/14/news015.html)
20. [［Python入門］辞書](https://atmarkit.itmedia.co.jp/ait/articles/1906/19/news017.html)
21. [［Python入門］集合](https://atmarkit.itmedia.co.jp/ait/articles/1906/25/news015.html)
22. [［Python入門］モジュールの使い方](https://atmarkit.itmedia.co.jp/ait/articles/1907/02/news009.html)
23. [［Python入門］モジュールの作り方](https://atmarkit.itmedia.co.jp/ait/articles/1907/05/news022.html)
24. [［Python入門］パッケージ](https://atmarkit.itmedia.co.jp/ait/articles/1907/09/news010.html)
25. [［Python入門］Pythonのオブジェクトとは](https://atmarkit.itmedia.co.jp/ait/articles/1907/12/news019.html)
26. [［Python入門］オブジェクトの同一性、比較、文字列表現](https://atmarkit.itmedia.co.jp/ait/articles/1907/16/news023.html)
27. [［Python入門］Pythonの演算子まとめ](https://atmarkit.itmedia.co.jp/ait/articles/1907/23/news010.html)
28. [［Python入門］クラスの基礎知識](https://atmarkit.itmedia.co.jp/ait/articles/1907/26/news020.html)
29. [［Python入門］クラス変数／クラスメソッド／スタティックメソッド](https://atmarkit.itmedia.co.jp/ait/articles/1907/30/news021.html)
30. [［Python入門］クラスを使ってスタックとキューを作成する](https://atmarkit.itmedia.co.jp/ait/articles/1908/06/news015.html)
31. [［Python入門］クラスの継承](https://atmarkit.itmedia.co.jp/ait/articles/1908/09/news035.html)
32. [［Python入門］リストを継承してスタックを作成する](https://atmarkit.itmedia.co.jp/ait/articles/1908/20/news024.html)
33. [［Python入門］クラスのスコープとプライベートな属性](https://atmarkit.itmedia.co.jp/ait/articles/1908/23/news028.html)
34. [［Python入門］多重継承](https://atmarkit.itmedia.co.jp/ait/articles/1908/27/news027.html)
35. [［Python入門］多重継承とmixin](https://atmarkit.itmedia.co.jp/ait/articles/1909/03/news021.html)
36. [［Python入門］例外と例外処理の基礎](https://atmarkit.itmedia.co.jp/ait/articles/1909/06/news019.html)
37. [［Python入門］例外の送出と例外クラス](https://atmarkit.itmedia.co.jp/ait/articles/1909/10/news013.html)
38. [［Python入門］ファイル操作の基本](https://atmarkit.itmedia.co.jp/ait/articles/1909/17/news030.html)
39. [［Python入門］バイナリファイルの操作](https://atmarkit.itmedia.co.jp/ait/articles/1910/01/news020.html)
40. [［Python入門］pickleモジュールによるオブジェクトの直列化](https://atmarkit.itmedia.co.jp/ait/articles/1910/04/news018.html)
41. [［Python入門］shelveモジュールによるオブジェクトの永続化](https://atmarkit.itmedia.co.jp/ait/articles/1910/08/news019.html)
42. [［Python入門］urllib.requestモジュールによるWebページの取得](https://atmarkit.itmedia.co.jp/ait/articles/1910/15/news018.html)
43. [［Python入門］Beautiful Soup 4によるスクレイピングの基礎](https://atmarkit.itmedia.co.jp/ait/articles/1910/18/news015.html)
44. [［Python入門］ディレクトリ操作の基本](https://atmarkit.itmedia.co.jp/ait/articles/1910/25/news021.html)
45. [［Python入門］pathlib.Pathクラスによるパス操作](https://atmarkit.itmedia.co.jp/ait/articles/1910/29/news019.html)
46. [［Python入門］shutilモジュールによる高水準ファイル操作](https://atmarkit.itmedia.co.jp/ait/articles/1911/01/news026.html)
47. [［Python入門］ファイル操作と例外処理](https://atmarkit.itmedia.co.jp/ait/articles/1911/05/news020.html)
48. [［Python入門］イテレータとは](https://atmarkit.itmedia.co.jp/ait/articles/1911/12/news011.html)
49. [［Python入門］ジェネレータ関数とジェネレータイテレータの基礎](https://atmarkit.itmedia.co.jp/ait/articles/1911/19/news015.html)
50. [［Python入門］ジェネレータの高度な話題](https://atmarkit.itmedia.co.jp/ait/articles/1911/22/news018.html)
51. [［Python入門］デコレーターの基礎](https://atmarkit.itmedia.co.jp/ait/articles/1911/26/news018.html)
52. [［Python入門］docstringの書き方](https://atmarkit.itmedia.co.jp/ait/articles/1912/06/news025.html)

### python.jp
[ゼロからのPython入門講座](https://www.python.jp/train/index.html)
#### Python初体験
Colabの使い方と、Pythonの実行方法を学びます
- Python初体験
- Google Colab の準備
- はじめてのPython
- コードセルとテキストセル
- ばえるPython
- はたらくPython
- この章のまとめ
#### Python基礎の基礎
Pythonのデータと式の基礎を学びます
- Python基礎の基礎
- れんしゅうもんだい
- 整数と実数
- 変数
- コメント
- 関数
- モジュールとimport
#### 文字列と入出力
Pythonのテキストデータと簡単な入力・出力方法を学びます
- 文字列と入出力
- 文字列
- print() 関数
- input() 関数
- 文字列の演算子と数値
- メソッド
#### 条件式と分岐
if文を使って、データに応じた処理を行う方法を紹介します
- 条件式と分岐
- 比較演算子
- 文字列の比較
- if 文 による条件分岐
- else 節
- 比較以外の条件式
- elif 節
#### ブール型と論理演算子
論理演算の基礎を解説します
- ブール型と論理演算子
- ブール型
- 論理演算子
- and 演算子
- or 演算子
- not 演算子
#### while文による繰り返し
while文による処理の繰り返しを解説します
- while文によるループ
- break文による中断
- 代入文と等号
- continue文
#### 関数の定義
独自の関数の作成と、呼び出し方を学びます
- 関数の定義
- ローカル変数とグローバル変数
- 関数の呼び出し方
- オブジェクトとリスト
- リストを使って、一連のデータを操作する方法を紹介します
- Pythonの型とオブジェクト
#### リスト
リストの操作
- while文を使ったリストのループ処理
- for文によるループ
#### 辞書オブジェクト
辞書を使ったデータ検索を紹介します
- 辞書
- 辞書の操作
- in 演算子
#### タプルとコレクション
タプルオブジェクトの使い方を紹介します
- タプル
- コレクション
- シーケンス
- コレクションのアンパック
#### 演習
これまでに紹介した知識を使って、簡単なプログラムを書いてみましょう
- スイカ割りゲームを作ってみよう
- リファクタリング - マジックナンバーを避ける
- 適切なデータ型を使う
- 関数を活用する

## Let'sプログラミング
[Python入門](https://www.javadrive.jp/python/)
見出し
1. Pythonインストールと環境設定
2. Pythonプログラムの基本事項
3. Jupyter Notebookの使い方
4. 文字列
5. 数値
6. 変数の使い方
7. 条件分岐
8. 繰り返し処理
9. リスト
10. タプル
11. 辞書
12. 集合
13. ユーザー定義関数
14. 組み込み関数の使い方
15. Python正規表現
16. 日付と時刻
17. ファイルの管理


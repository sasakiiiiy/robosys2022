# robosys2022
# plusコマンド
![test](https://github.com/sasakiiiiy/robosys2022/actions/workflows/test.yml/badge.svg)
#何をするためのソフトか？
標準入力から読み込んだ数字を足す。
# 使うために必要なソフトウェアの入手方法
1.Python公式サイト（Windows）へアクセスする。
2.Stable Releases(安定版)をダウンロードする。
3.ダウンロードしたインストーラをダブルクリック--> インストールダイアログが表示される。
4.インストールダイアログの途中で "Add Python 3.X to Path" のチェックボックスにチェックを入れる。
5."Install Now" をクリックすると、インストールされる。
最後にplusコマンドを動かすのに必要なライブラリであるpythonのバージョン確認。
```bash
python -V
```
#主な使い方
```bash
seq 5 | ./plus
```
と打つと出力結果は15になる。
## 必要なソフトウェア
* Python
  * テスト済み: 3.7~3.10

## テスト環境
* Ubuntu


* このソフトウェアパッケージは、3条項BSDライセンスの下、再配布および使用が許可されます。
* ©　2022 Yuto Sasaki

#作成者の概要
* 佐々木悠斗
* メールアドレス:s21C1053MT@s.chibakoudai.jp

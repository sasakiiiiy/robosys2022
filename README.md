# robosys2022
# plusコマンド
![test](https://github.com/sasakiiiiy/robosys2022/actions/workflows/test.yml/badge.svg)
## 何をするためのソフトか？
標準入力から読み込んだ数字を足す。
## 必要なソフトウェア
* Python
  * テスト済み: 3.7~3.10
## 使うために必要なソフトウェアの入手方法
1. Python公式サイト（Windows）へアクセスする。
2. Stable Releases(安定版)をダウンロードする。
3. ダウンロードしたインストーラをダブルクリック--> インストールダイアログが表示される。
4. インストールダイアログの途中で "Add Python 3.X to Path" のチェックボックスにチェックを入れる。
5. "Install Now" をクリックすると、インストールされる。

最後にplusコマンドを動かすのに必要なソフトウェアであるpythonのバージョン確認。
```bash
python -V
```

## plusコマンドの取り扱い方法
1. Ubuntuを開く
2. ファイルを開く
```bash
vi <ファイル名>
```
3. ファイルにplusコマンドをいれる
```bash
import sys

ans = 0
for line in sys.stdin:
    try:
      ans += int(line)
    except:
      ans += float(line)

print(ans)
```
4. 実行権限の付与
```bash
chmod +x <ファイル名>
```
そうすることによって、./plusを扱えるようになる。
5. 最後に足したい行を入力して、実行させる。
* 例
```bash
seq 5 | ./plus
```
と打つと出力結果は15になる。

## テスト環境
* Ubuntu
  * 18.04
## 権利関係
* このソフトウェアパッケージは、3条項BSDライセンスの下、再配布および使用が許可されます。
* ©　2022 Yuto Sasaki

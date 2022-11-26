# robosys2022
# plusコマンド
![test](https://github.com/sasakiiiiy/robosys2022/actions/workflows/test.yml/badge.svg)
## 何をするためのソフトか？
標準入力から読み込んだ数字を足す。
## 必要なソフトウェア
* Python
  * テスト済み: 3.7~3.10

## plusコマンドの取り扱い方法
1. Ubuntuを開く
2. gitコマンドを用いてローカル環境にリポジトリをクローンする
```bash
git clone git@github.com:sasakiiiiy/robosys2022.git
```
3. 念のためplusファイルがあるか確かめる
```bash
ls
```
4. plusファイルがあったら、足したい行を入力して、実行させる。
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

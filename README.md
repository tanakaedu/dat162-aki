# デジタルアーツ東京　2016年度秋学期　2年生用リポジトリ

# 就活に向けての記事
- [paiza ITエンジニア・プログラマを目指す就活で押さえるべきポイント](http://paiza.jp/advice/student_advice)


# サイト紹介
- https://skima.jp/


# 15回目(9/16)
## 音ゲー
- MusicManagerとTempoを統合する
- audio.timeを直接つかうのをやめて、MusicManager.getTime()で、タイムを返す
- 再生時間がきたら、曲を再生
- 以上で、0拍目がタイミング通りに動くはず
- MusicManagerの曲データのタイミングで、blockを出現させる
- blockに、拍数から秒数を算出して渡す

![ホワイトボード](https://github.com/tanakaedu/dat162-aki/blob/master/img0909.jpg?raw=true)

# 14回目(9/9)
## 音ゲー
- Asset Storeから、 Action Game Music をインポートして、Enemy Spaceship_(moderate)を利用
- 著作権について：「著作権　文化祭」で検索
  - JASRAC http://www.jasrac.or.jp/info/school/
  - 以下の3つの条件のすべてに該当する場合は、演奏利用における著作権の手続きは必要ありません（著作権法38条）。
    - 営利を目的としていない
    - 名目を問わず、入場料をとらない
    - 演奏者（歌手やバンド）や指揮者など出演者へ報酬の支払いがない

1. サンプル曲を探す
2. 全体の秒数と拍数をカウント(前回のプログラム)
3. テンポのチェック
4. 仮のデータを作成(配列)
5. データから、音符の出現タイミングを逆算して、再生

---


# 13回目(9/2)
## 夏休みの宿題発表
- 指定のフォルダーに発表用データをコピー
- 持ち時間は一人10分

## 宿題内容
- 小作品を１本完成させる
  - ジャンル、使用言語は自由
    - Visual C# / Unity / DirectX / Java / Scratch / [プログラミングの必要なし！簡単にスマホアプリが開発できるツール9選](https://freelance.levtech.jp/guide/detail/38/?utm_content=bufferf4992&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
- 夏休み明けに以下をフォルダーにまとめてLANDISKで提出
  - すぐに実行できるデータ一式
  - プログラムや画像、音声など、ビルドに必要なデータ一式
  - WordかPowerPointで作成した作品紹介
    - タイトル
    - 動作環境
    - 開発環境
    - 起動方法
    - 使い方
    - 利用目的
    - ビルド方法
    - 参考にした書籍やWebページがあれば、それらのリスト

## 実習
- Unityちゃんの移動(とくにジャンプ)の動作改善を試みる


# デジタルアーツ東京　2016年度秋学期　2年生用リポジトリ

# 就活に向けての記事
- [paiza ITエンジニア・プログラマを目指す就活で押さえるべきポイント](http://paiza.jp/advice/student_advice)


# サイト紹介
- Unityインターハイ2016 https://inter-high.unity3d.jp/
- 面白そうなハード Arduboy http://ssci.to/2880


#　書籍紹介
まだ実際の本に目を通していないが、よさそうなので紹介。
- 北村 愛実 [Unity5の教科書 2D&3Dスマートフォンゲーム入門講座 (Entertainment&IDEA) ](https://www.amazon.co.jp/dp/4862463541/)
  - C#の入門からあるので復習向け。基本的な箇所からひっかかっていたらおススメ。
- Ben Tristem (著), Mike Geig (著) [24時間で学ぶ! Unity 5 基本操作と開発のコツ](https://www.amazon.co.jp/dp/4862463541/)
  - Unityの機能全体を紹介しながらゲームの開発までを凝縮。これからいよいよゲームを開発しようという人におススメ。数学や物理など、基本的な知識は本書では網羅できていないようなので、この本に書かれていることを全て理解できるようにするというのが、今後の目標の一つと言えるかもしれない。


# 4回目
- http://www.screenpresso.com/ でチュートリアル作成
  - monosnap はインストールが必要
 

# 2,3回目
- [Unityちゃんの操作性アップ](https://github.com/tanakaedu/dat161-aki/wiki/UnityChan%E3%81%AE%E6%93%8D%E4%BD%9C%E6%80%A7%E3%82%92%E3%82%88%E3%81%8F%E3%81%99%E3%82%8B)


# 1回目
## 音ゲー
- buttonの本体は動かさず、表示を子オブジェクトにしてそちらを動かす
- ミスの実装
- 曲データを乱数で姿勢


# 15回目(9/16)
## 音ゲー
- MusicManagerとTempoを統合する
- audio.timeを直接つかうのをやめて、MusicManager.getTime()で、タイムを返す
- 再生時間がきたら、曲を再生
- 以上で、0拍目がタイミング通りに動くはず
- 指定の拍を、曲の経過秒数に変換する関数 MusicManager.getTimeWithHaku() の作成
- MusicManagerの曲データのタイミングで、blockを出現させて、時間を設定する
- blockに、拍数から秒数を算出して渡す

![ホワイトボード](https://github.com/tanakaedu/dat162-aki/blob/master/img0909.jpg?raw=true)

### 紹介ページ
- イラストオーダーオーダーサービスサービスSKIMA https://skima.jp/
- IGDAジャパン ゲーム開発者推薦図書リスト(CEDEC2016)版 http://www.igda.jp/?p=4618


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


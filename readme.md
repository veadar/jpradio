#[Mac] 地上波ラジオをメニューバーから聴くアプリを作った

##作成動機とスクリーンショット

Macで作業する時にBGMとしてiPhoneのradikoでラジオを流すのだけれど、そのためだけにiPhoneを使うのはなんかもやっとするので、Macのアプリを作った。

![jpradio](https://raw.github.com/veadar/jpradio/17b6892eb2fa11cde652f3a43ba5dfcfee705560/screenshot.png)

##仕様

- [Radikoに加盟している日本全国のラジオ局](http://ja.wikipedia.org/wiki/Radiko#.E9.85.8D.E4.BF.A1.E5.AE.9F.E6.96.BD.E6.94.BE.E9.80.81.E5.B1.80.E3.81.A8.E5.AF.BE.E8.B1.A1.E5.9C.B0.E5.9F.9F)が聴取できる([jpradio.herokuapp](http://jpradio.herokuapp.com/)のおかげ)
- Flashレス (とことん[jpradio.herokuapp](http://jpradio.herokuapp.com/)のおかげ)
- 指定した地域の現在放送中の番組をRadikoから取得、リスト表示する番組表機能
- ラジオ局を登録すると起動時に自動再生
- 特に聞きたい局が決まっていない時に便利なランダム再生機能
- 動作確認：10.8.4

##注意点
我ながらとても便利なアプリだと自負していますが、radiko的に推奨されていない聴き方だと思います。

何か問題になってデータを利用させてもらっているサイト、[jpradio.herokuapp](http://jpradio.herokuapp.com/)がなくなってしまったらとても困るので、ひっそり楽しんでください。

##ダウンロード

Click Here → [Download](https://github.com/veadar/jpradio/releases)


##利用しているアイコンやサイト

- [jpradio.herokuapp](http://jpradio.herokuapp.com/)
- [IconArchive(利用アイコン)](http://www.iconarchive.com/show/real-vista-multimedia-icons-by-iconshock/radio-icon.html)
- [MenuBarAppleScript](http://memogakisouko.appspot.com/MenuBarAppleScript.html)
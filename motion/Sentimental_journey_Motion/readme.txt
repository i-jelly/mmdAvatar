【MMD】ささらまだ、１６だぁから〜♪【自称１６歳】のモーションです。
http://www.nicovideo.jp/watch/sm22662074

モーション解説動画は、
http://www.youtube.com/watch?v=BAdtbhMANyM



目次

1.トレースについて
2.モーションの読み込み位置（音源との同期）
3.モーションの種類
4.マイクの持たせ方、持ち替え方、位置修正
5.その他、おまけ
6.禁止事項


1.トレースについて

1981年発売の松本伊代さんのデビューシングルです。なるべく当時の
映像を参考にしました。ベストテン、トップテン、レッツゴーヤング、
夜のヒットスタジオ等。※YouTubeの振り付けマスターも参考にしま
したが、一部異なります。

本来は、伊代さんが有線マイクで、足元のケーブルを気にして振り付
けがぎこちない部分があります。ＭＭＤで有線マイクを再現するには、
ＰＭＤエディター等でモデルに組み込む必要があり、汎用性の観点か
らワイヤレスマイクに統一することとしました。
キャプテンの２人は元々ワイヤレスマイクです。


2.モーションの読み込み位置（音源との同期）

まずWAVファイルを読み込み、イントロの最初の一音から、１４〜
１５フレーム手前に読み込むのがベストです。

タイミングがズレるとせっかくの動画が台無しになるので、ここは
最大限の注意を払って調整してください。

MMDではWAVファイルの再生位置は動かせないので、モーションデータ
を前後に移動して調整します。


3.モーションの種類

モーションは、伊代さんのボーカルと、バックのキャプテン２人の
計３人分です。

尚、ここではキャプテンの２人は「画面右の」「画面左の」と表記
します。まぎらわしいので注意してください。

配布データは、フォルダ分けして「Vocal」「Screen_R」「Screen_L」
となります。
これらのモーションは、使用するモデルデータのボーン構成によって、
振る舞いが微妙に異なります。いくつか準備しました。

�@Vocal用・・・松本伊代さんのトレースです

　N_sasara_beta・・・N式ささらβ専用です。尚、ニコニコ動画で使用
　　　　　　　　　　したモデルは、手足長さ、顔、胸を改変してます。

　Chibi_Sasara・・・ちびささらｖ1.12用。16歳なのかは不明ｗ

　Normal・・・と式ミク合わせです。個人的に汎用性が高いと思います。
　　　　　　  ただし、と式ミクは配布終了のようです。残念＞＜。

　Normal_Wide_Step・・・歩幅を広げたもの。

　Lat_Miku・・・Lat式ミクver2.31合わせです。変更点：髪IK、マイク

　Mamama_Miku・・・ままま式Appearance Miku ver1.00合わせです。

　※Tda式も作ろうと思いましたが、調整が大変で棚上げしました。

�AScreen_R（画面右）用・・・キャプテン（山本恵子さん側）です。
�BScreen_L（画面左）用・・・キャプテン（北沢清子さん側）です。

　どちらも、NormalとWide_Stepがあります。
　Normalは、と式ミク合わせ。ula式ルカ、Lat式リン、レアに使用。
　Wide_Stepは、歩幅を拡大したもの。ままま式GUMI、同テトに使用。

　ちびつづみは、Wide_Stepを読み込んだ後、全フレームを指定し、
　MMDメニューから、編集＞ﾌﾚｰﾑ位置角度補正より、
　移動　X：0.65、Y:0.85、Z：0.85（回転はそのまま）を実行します。

キャプテン役モデルの立ち位置は、デフォルトで、
画面右が�]12.5、Y15.0、画面左は�]-12.5、Y15.0です。
全ての親ボーン内蔵の場合、自動的に配置されます。


4.マイクの持たせ方、持ち替え方、位置修正

私の場合、Ashさんのマイクセットver3よりお借りしました。
「Ash マイクセットver３」で検索してください。
paperguitar.comよりフリーDL可能です。
（いつもお世話になっております）

ここではこのマイクを持たせる方法を解説しておきます。
別のマイクを持たせたい場合は都度調整してください。

�@モデルを読み込みます。ここでは公式CULで説明。

�Aｶﾒﾗ・照明・ｱｸｾｻﾘにして
ｱｸｾｻﾘ操作＞読込

ダウンロードしたDATAより
Xアクセフォルダ＞
SM58風ワイアレスマイク.x

�B対象となるモデルとボーンを指定します

地面＞＞CUL　センター＞＞左中指３

�C数値を入力

　Ｙ：−０．３　Ｚ：０．１５
　Ｒｙ：１８０　　※その他は不変

�D　□表示にチェックを入れて、登録。

これで完了。全モデル共通です。
（咲音メイコを除く）

開始（ゼロ）フレームに読み込みます。

指先にくっついてますが、モーションを読み込めば
ちゃんと握ります。

�E画面右側のキャプテン役はマイク持ち替えがあります。

0フレームスタートの場合、
1690フレーム　右中指３
2005フレーム　左中指３
3885フレーム　右中指３
4198フレーム　左中指３

とボーン変更を登録してください。

�Fマイクは１モデルに１本必要です。
３人で躍らせる場合は、３本のマイクを読み込んでください。

ｱｸｾｻﾘ操作＞読込　の繰り返しです。
この動画では同時に計７本使用しています。

それぞれを各モデルのボーンに割り当てます。

�Gマイク位置の修正は、かなり大変な作業になります。
カメラ操作でアップにする場合などは気になるかもです。

簡単な方法としては、「左肩」ボーンを「global」モードで
左右ズレ＞＞Ｙ軸（黄色）
上下ズレ＞＞�]軸（赤色）
で調整します。


5.その他、おまけ

さとうささらのボーカルデータを同梱します。
CeVIO Creative Studio FREEをダウンロードして再生して下さい。
Othersフォルダ　sasaramada16.ccs

原曲に対しキー変更（ピッチ）+５。（Audacity v1.3.12βにて）

テンポは♪＝394としています。公式な数値は不明です。
原曲を解析したところ、98.5？ぐらいだったので、
CeVIOの分解能の低さ（最小1/32音符）をカバーするため、
4倍にしています。

また、適当なＭＩＤＩデータが見つからなかったので、
メロディラインは耳コピになっています。ご注意ください。

「しゃくり」表現のため、出だしの音程が低いです。

CeVIOからMusicXML（.xml）ファイルへのエクスポートが可能です。
使えるかどうかは不明です。

この「ささらソング」を個人が勝手に使うのは自由ですが、
著作権への配慮については自己責任でお願いします。

個人的には、この曲はかなり『インパクトの強い』ネタなので、
「ミクはまだ、１６だから〜」とか
「カルはまだ、１６だから〜」とか
「（ロリ）メイコまだ、１６だから〜」などを見てみたい。

公式には、MEIKOは「成人」で年齢不詳、
デビュー当時の咲音メイコは１６歳ということらしいです。

ちなみに、ＭＭＤ同梱の「咲音メイコ」をボーカルとして使い、
同梱の「咲音マイク」＝ガイコツマイクを使用する場合は、
横から声を拾うみたいなので、モーションも対応させています。

使い方は、まずNormal モーションを読み込んだ後に、
開始フレームにて、Othersフォルダの　meiko_mic_LH.vmd
をモーションとして読み込んで左手を上書きします。
咲音マイク.xは、アクセサリ操作から読み込んで、
左手首ボーンに割り当て、
X:−０．４、Y：−０．２５、Z：０．５
Rx:−２５.0　Ry:−４５．０、Rz:６０．０　とします。

さらに、想像をふくらませれば、

「リンはまだ、１４だから〜」
「グミはまだ、（ごにょごにょ）だから〜」（年齢不詳）
「ゆかりもう、１８だから〜」
「ルカはもう、ハタチなのよ〜」
「あたしなんてもう三十路超えよっ！」（テトさん３１歳）

などなど、ボカロPさんのイメージ次第で何でも作れそうです。


歌詞字幕ファイル同梱　AviUtl拡張編集用
sentimental16_854ｘ480.aup
sentimental16_1280ｘ720.aup


6.禁止事項

音源に原曲をそのまま使うのはやめましょう。

このモーションデータの再配布は禁止です。

エロ動画（裸、マイクロビキニ、超ローアングル）は禁止です。

改変・修正したデータを配布したい場合はご相談ください。

連絡先：nico_keke＠yahoo.co.jp
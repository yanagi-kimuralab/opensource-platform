# opensource-platform
![image](https://user-images.githubusercontent.com/93763065/211138959-c709bd07-9d78-4def-be3c-f00fe92557c6.png)

# オープンソースロボットプラットフォームとは
opensource-platformは、長岡技術科学大学木村研究室が開発・提供しているレスキュー対応ロボットのためのプラットフォームです。
本プラットフォームはすべてのハードウェアがオープンプラットフォームとして公開されています。

# 基本コンセプト
開発したプラットフォームは以下のコンセプトで開発されています。

・大学、高専生が製作可能であること
・大学、高専等の設備で製造可能であること
・様々な要求仕様に対応できること
・災害対応ロボット競技会などの実証実験に使用できること

# 基本仕様
オープンソースロボットプラットフォームの基本性能及びCADの書き方について以下に示します。

<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:x="urn:schemas-microsoft-com:office:excel"
xmlns="http://www.w3.org/TR/REC-html40">

<head>

<meta name=ProgId content=Excel.Sheet>
<meta name=Generator content="Microsoft Excel 15">
<link id=Main-File rel=Main-File
href="file:///C:/Users/KIMURA~1/AppData/Local/Temp/msohtmlclip1/01/clip.htm">
<link rel=File-List
href="file:///C:/Users/KIMURA~1/AppData/Local/Temp/msohtmlclip1/01/clip_filelist.xml">
<style>
<!--table
	{mso-displayed-decimal-separator:"\.";
	mso-displayed-thousand-separator:"\,";}
@page
	{margin:.75in .7in .75in .7in;
	mso-header-margin:.3in;
	mso-footer-margin:.3in;}
.font5
	{color:windowtext;
	font-size:6.0pt;
	font-weight:400;
	font-style:normal;
	text-decoration:none;
	font-family:游ゴシック, monospace;
	mso-font-charset:128;}
.font6
	{color:red;
	font-size:8.0pt;
	font-weight:400;
	font-style:normal;
	text-decoration:none;
	font-family:"ＭＳ Ｐゴシック", monospace;
	mso-font-charset:128;}
tr
	{mso-height-source:auto;
	mso-ruby-visibility:none;}
col
	{mso-width-source:auto;
	mso-ruby-visibility:none;}
br
	{mso-data-placement:same-cell;}
td
	{padding-top:1px;
	padding-right:1px;
	padding-left:1px;
	mso-ignore:padding;
	color:black;
	font-size:11.0pt;
	font-weight:400;
	font-style:normal;
	text-decoration:none;
	font-family:游ゴシック, monospace;
	mso-font-charset:128;
	mso-number-format:General;
	text-align:general;
	vertical-align:middle;
	border:none;
	mso-background-source:auto;
	mso-pattern:auto;
	mso-protection:locked visible;
	white-space:nowrap;
	mso-rotate:0;}
.xl63
	{font-size:8.0pt;
	font-family:"ＭＳ Ｐゴシック", monospace;
	mso-font-charset:128;
	text-align:center;
	border:.5pt solid windowtext;
	white-space:normal;}
.xl64
	{font-size:8.0pt;
	font-family:"ＭＳ Ｐゴシック", monospace;
	mso-font-charset:128;
	text-align:center;
	border:.5pt solid windowtext;}
.xl65
	{font-size:8.0pt;
	font-family:"ＭＳ Ｐゴシック", monospace;
	mso-font-charset:128;
	text-align:left;
	border:.5pt solid windowtext;
	white-space:normal;}
.xl66
	{font-family:"ＭＳ Ｐゴシック", monospace;
	mso-font-charset:128;
	text-align:center;
	border:.5pt solid windowtext;}
ruby
	{ruby-align:left;}
rt
	{color:windowtext;
	font-size:6.0pt;
	font-weight:400;
	font-style:normal;
	text-decoration:none;
	font-family:游ゴシック, monospace;
	mso-font-charset:128;
	mso-char-type:katakana;
	display:none;}
-->
</style>
</head>

<body link="#0563C1" vlink="#954F72">



性能表
--
名称 | 災害対応ロボット移動プラットフォーム
シャーシのみ(kg) | 30
バッテリーのみ(kg) | 3
総重量(kg) | 33
全長(mm) | 600
全幅(mm) | 500
全高(mm) | 215
全長(mm) | 800
最大走行速度(m/s) | 0.5
登坂能力(°) | 50°(階段)
角度付き平板(°) | 30°（べニア板）
フリッパー回転速度(r/s) | 0.1
段差乗り越え高さ(mm) | 170
搭載可能な重量(kg) | 10
連続稼働時間(min) | 40
移動方式 | クローラ
フリッパ | 4本独立サブクローラ付き
防水 | ＩＰｘ4
防塵 | IP6ｘ
想定加工環境 | 卓上CNCフライス盤
卓上３Dプリンタ
卓上ボール盤
その他仕様 | ・部品の材料は実物と同じものを指定している     ・既製品は部品名が製品の型番になっている     ・分解図機能を利用できる     ・サーフェスを用いて、情報を追加する部品が     　追加されている     ・イボゴムの硬度はベルトと同等か低くする






</body>

</html>


# 開発環境
Solidworks 2018
Vectric Cut 2D
Estlcam

その他使用ソフトはこちら

ご不明なことがあればこちらに連絡ください。
メール：stn.kimuralab@gmail.com

# ライセンス
opensource-platform is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License.

# 3Dモデルビューア
Autodesk Viewerを使用して、ブラウザ上で3Dモデルを閲覧・操作することができます。
アクセスは[こちら](https://autode.sk/3IsuZBB)から。


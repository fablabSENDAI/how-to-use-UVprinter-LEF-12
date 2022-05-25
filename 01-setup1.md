---
layout: default
title: 01.データの基本設定
nav_order: 2
---

# 01.データの基本設定
<br><br>

## 01.1 事前準備
<br>

RolandDGより、以下3つのスウォッチライブラリが用意されています。<br>

* **Roland Grapac Bri-o-coat Library.ai**
* **Roland Texture System Library.ai**
* **Roland VersaWorks.ai**

これらを以下のフォルダに入れて、Illustratorを再起動します。<br>

* **Windowsの場合**<br>
ProgramFiles ＞ Adobe ＞ Adobe Illustrator ＞ プリセット ＞ スウォッチ<br>
* **Mac OSXの場合**<br>
アプリケーション ＞ Adobe Illustrator ＞ プリセット ＞ ja_JP ＞ スウォッチ<br>

※FLATのIllustratorには既にスウォッチライブラリが読み込まれています。<br>
もしスウォッチライブラリデータを欲しい場合はスタッフへ相談してください。<br>
<br>
<br>
<br>

## 01.2 ドキュメント設定
<br>

Adobe Illustratorの新規ドキュメントからデータを作成する場合、以下のように設定します。<br>

<img src="assets/01-1.png" width="640" alt="hi" class="inline"/><br>
<br>

アートボードの幅と高さは、UVプリンタの**最大印刷範囲（305mm × 280mm）**に収まるよう、任意のサイズに設定します。<br>
カラーモードは**CMYK**を選択します。ラスタライズ効果は、数値を高くするほど綺麗に印刷されます。<br>
<br>
<br>
<br>

## 01.3 WHITEとGLOSSの割当て
<br>

UVプリンターではカラーインク（CMYKインク）だけでなく、特殊なインクを使うことができます。<br>
<br>

<img src="assets/01-2.png" width="480" alt="hi" class="inline"/><br>
<br>

* **WHITE：**白色のインク。着色だけでなく、カラーインクをプリントする前のベースにも使用します。
* **GLOSS：**無色透明なインク。カラーインクの上にプリントすることで、様々な質感を与えることができます。

**ウィンドウ ＞ スウォッチライブラリ ＞ Roland VersaWorks** をクリックしてスウォッチウィンドウを呼び出し、<br>
必要に応じてオブジェクトの色を**RDG_WHITE** や **RDG_GLOSS**に設定します。<br>
<br>
<br>
<br>

## 01.4 レイヤー分け
<br>

CMYK（カラー）インク、WHITEインク、GLOSSインクは、UVプリンタ専用ソフトウェアで<br>
個別に設定する必要があるため、Adobe Illustrator上でインク別にレイヤー分けをしておきます。<br>
<br>

<img src="assets/01-3.png" width="200" alt="hi" class="inline"/> <img src="assets/01-4.png" width="200" alt="hi" class="inline"/> <img src="assets/01-5.png" width="200" alt="hi" class="inline"/><br>

（左：GLOSSインクレイヤー／中：WHITEインクレイヤー／右：CMYK（カラー）インクレイヤー）<br>
<br>

<img src="assets/01-6.png" width="480" alt="hi" class="inline"/><br>
<br>

3種類の印刷用レイヤーに加えて、材料の位置合わせをするための枠レイヤーも用意しておきます。<br>
（レイヤーの表示順は問いません。）<br>
<br>

* **WHITE：**白色のインク。着色だけでなく、カラーインクをプリントする前のベースにも使用します。
* **GLOSS：**無色透明なインク。カラーインクの上にプリントすることで、様々な質感を与えることができます。

**ウィンドウ ＞ スウォッチライブラリ ＞ Roland VersaWorks** をクリックしてスウォッチウィンドウを呼び出し、<br>
必要に応じてオブジェクトの色を**RDG_WHITE** や **RDG_GLOSS**に設定します。<br>
<br>
<br>
<br>

## 01.5 アートボードとデータプリント位置の確認
<br>

<img src="assets/01-7.jpg" width="480" alt="hi" class="inline"/><br>
<br>

データは180度回転した状態で印刷されます。<br>
アートボードの左上がUVプリンタのベースプレートの右手前にくることから、<br>
Illustrator上のデザインとプリンタ上での印刷位置は上記のように対応します。

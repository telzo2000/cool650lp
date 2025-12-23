 　# Buildguide for cool650lp
<br>


## 0 部品の確認
<br>
Follow the BOM on github's readme.md to make sure that all the parts are available.
<br>
githubのreadme.mdのBOMに沿って、部品が全て揃っているかを確認してください。
<br>


## 1 ダイオードのはんだ付け

If the diode is already soldered, please skip this operation.
<br>
すでにダイオードのはんだ付けされている場合は、この作業を省略してください。
<br>
<br>
This work is done on the left and right keyboard boards respectively.
<br>
この作業は左右のキーボード基板でそれぞれ行います。
<br> 
Solder the diodes to the back of PCB.
<br>
PCBの裏面にダイオードのハンダ付けをします。
<br>
As expected, it is compatible with SMD type.
<br>
ダイオードは、SMDタイプに対応しています。
<br>
Diodes have polarity, so be careful about the direction in which they are installed.
<br>
ダイオードには極性がありますので、取り付ける向きに注意してください。
<br>

[ダイオード（SMD)のはんだ付けの動画](https://youtu.be/ODk16bd4XkA)
<br>

<br>

## 2  スイッチソケットのハンダ付け

cool650lp supports choc switch sockets.
<br>
cool650lpでは、chocのスイッチソケットに対応しています。
<br><br>
Solder the switch socket to the back of the keyboard board.
<br>
キーボード基板の裏面にスイッチソケットのハンダ付けをします。
<br>

[Switch socketハンダ付け動画](https://youtu.be/ZnbgaueMR4w?si=_JLjD--3HJJ5Pu7Q)


<br>

## 3 RP2040-Zeroのハンダ付け


<br>
次の動画を参考にしてハンダ付けをしてください。
<br>

[RP2040-Zeroのはんだ付け動画](https://youtu.be/FV4INvCWlU0?si=ENKXU5vA0EeIhCRw)

## 4　キースイッチの装着

Insert the key switch in the following order: top case, then PCB.
<br>
トップケース、PCBの順になるように、キースイッチを差し込んでください。
<br>
When inserting the key switch, make sure the pins are straight.
<br>
キースイッチを差し込む時、キースイッチのピンが真っ直ぐになっているか、確認してください。
<br>

## 5 ボトムケースの装着

Attach the bottom case to the underside of the PCB, with the bumpy side of the bottom case facing the PCB.
<br>
PCBの下面にボトムケースを装着します。ボトムケースには凹凸がある面が、PCBに向くようにしてください。
<br>
<br>
Insert eight 6mm M2 screws into the top case. Secure the bottom case with M2 nuts.
<br>
トップケース側から、M2ネジ6mmを８箇所差し込みます。ボトムケース側では、M2ナットで固定してください。
<br>
<br>



##  6　キーキャップの装着

Please attach your favorite keycap.
<br>
お好きなキーキャップを装着してください。
<br>

![](img/img00006.jpg)

## 7 動作確認について

Connect the keyboard to your PC with a USB cable, then press the reset button and boot button on the RP2040-Zero through the rectangular window in the top case.
<br>
PCとキーボードをUSBケーブルで繋ぎます。その後、トップケースにに開いた四角窓から、RP2040-Zeroのリセットボタン、ブートボタンを押します。
<br>
<br>

![](img/img00004.jpg)

Press and hold the left button and then press the right button to mount a folder on your PC.
<br>
ボタンは、左を押したまま、右を押すと、PCにフォルダがマウントされます。
<br>
<br>

Just drag and drop the uf2 file from [here](https://github.com/telzo2000/cool650lp/tree/main/firmware) into the mounted folder.
<br>

[ここ](https://github.com/telzo2000/cool650lp/tree/main/firmware)にあるuf2ファイルを、マウントされたフォルダにドラッグ&ドロップすれば大丈夫です。
<br>
<br>

## 8 完成

After attaching non-slip rubber to the bottom of the bottom case, it's done.
<br>

ボトムケースの底面に、滑り止めゴムを取り付けたら、完成です。
<br>
![](img/img00001.jpg)

Please enjoy a life with a better keyboard.
<br>
よりよいキーボードのある生活を楽しんでください。
<br>

![](img/img00002.jpg)



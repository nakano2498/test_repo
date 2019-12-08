# robosys_2019
LEDを点灯させるデバイスドライバ．
参考にしたページは次のリンクである．https://ryuichiueda.github.io/robosys2019/lesson7.html

下記のコマンドを送信するとLEDが点灯または消灯する．<br>
echo 0 /dev/myled0 →　LEDが消灯
echo 1 /dev/myled0 →　LEDが点灯
echo 2 /dev/myled0 →　LEDが点滅(0.5[s])

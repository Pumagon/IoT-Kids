# RGB LEDを使う
RGB LEDのRGBとは赤(red)緑(green)青(blue)の略で、この１つのLEDに３つ小さなLEDが付いています。通常RGBとは赤(red)緑(green)青(blue)の値をそれぞれ0から255(8bitもしくは1byte)まで設定でき、そこから約1677万色までの色を表すことが出来るのですが。raspberry piではこれを再現するためにPWMを使います。
# RGB LEDを接続する
まずRGB LEDを以下の用に繋げます。
![RGB LED_ブレッドボード](https://user-images.githubusercontent.com/81986311/216890125-45dff2c0-d047-40a3-9642-8af00716ac48.png)
左からGPIO2、GPIO3、GPIO4そしてGNDに繋げてください。
# RGB LEDをテストする
まずPWMを使う前に赤と青を組み合わせて紫を作ります。

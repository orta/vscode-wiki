Input method smoke test

The golden standard is Word

---
## [Windows] Japanese
* Add the Japanese input method
 * `Settings > Time & Language > Region & language > Add a language > Japanese`

* Focus VS Code and switch OS input method to Japanese and choose Hiragana:

    [[images/ime/windows-japanese-ime.png]]

* Type the following words: `sennsei` or `konnichiha` or `mikann`. Here is how Word looks like doing this:

    [[images/ime/windows-japanese-word.gif]]

---
## [Windows] Korean
* Add the Korean input method
 * `Settings > Time & Language > Region & language > Add a language > Korean`

* Focus VS Code and switch OS input method to Korean and choose Hangul:

    [[images/ime/windows-korean-ime.png]]

* Type `gksrmf` and press space. Here is how Word looks like doing this (it should be "한글"):

    [[images/ime/windows-korean-word1.gif]]

* Type `dkssudgktpdy` in a new file. Here is how Word looks like doing this:

    [[images/ime/windows-korean-word2.gif]]

---
## [Windows] Vietnamese with UniKey
* Download and Run [UniKey](http://www.unikey.org/bdownload.php#uk)
* Click the button with a down arrow:

    [[images/ime/windows-vietnamese-ime-1.png]]

* Get the following settings:

    [[images/ime/windows-vietnamese-ime-2.png]]

* Focus VS Code and click once UniKey's system tray entry (next to the date) to toggle on Vietnamese mode (get it to be a V):

    [[images/ime/windows-vietnamese-ime-3.png]]

* Type `Tooi` => it should transform to => Tôi. Here is how Word looks like doing this:

    [[images/ime/windows-vietnamese-word.gif]]

---
## [Windows] Chinese Test 1
* Add the Chinese (Simplified) input method
 * `Settings > Time & Language > Region & language > Add a language > Chinese (Simplified)`

* Focus VS Code and switch OS input method to Chinese and choose Chinese mode:

    [[images/ime/windows-chinese-ime.png]]

* Type `.` or `,` in full width form. They should be typed in immediately. Here is how Word looks like doing this:

    [[images/ime/windows-chinese-word.gif]]

---
## [Windows] Chinese Test 2
* Add the Chinese (Simplified) input method
 * `Settings > Time & Language > Region & language > Add a language > Chinese (Simplified)`

* Focus VS Code and switch OS input method to Chinese and choose Chinese mode and make sure the input method's name is Microsoft Pinyin:

    [[images/ime/windows-chinese-ime.png]]

* Type `ni` press `Space` and then `hao` and press `Space`. They should be typed in immediately. Here is how Word looks like doing this:

    [[images/ime/windows-chinese2-word.gif]]


---
## [Mac] Zhuyin Input Method (Chinese)
* `System Preferences > Keyboard > Input Sources > Add > Chinese, Tranditional > Zhuyin`

    [[images/ime/mac-zhuyin-setup1.png]]

* Focus VS Code and switch OS input method to Zhuyin (press Command + space)

    [[images/ime/mac-zhuyin-setup2.png]]

* Type `su3cl3` and press Enter. Here is how World looks like doing this (It should be "你好")

    [[images/ime/mac-zhuyin-word.gif]]

---
## [Mac] The hold input method
* Long press `e`
* A pop-up should appear
* Choose a different variant, like an `e` with an accute accent


---
## [Mac] The emoji inserter

---
## [Linux] Japanese
* Use [mozc](https://wiki.archlinux.org/index.php/Mozc)
* Information for [elementary](http://elementaryos.stackexchange.com/questions/271/how-can-i-enable-japanese-input)

---
Content created from:
* [#1168](https://github.com/Microsoft/vscode/issues/1168)
* [#2250](https://github.com/Microsoft/vscode/issues/2250)
* [#2374](https://github.com/Microsoft/vscode/issues/2374)
* [#5615](https://github.com/Microsoft/vscode/issues/5615)
* [#7997](https://github.com/Microsoft/vscode/issues/7997)

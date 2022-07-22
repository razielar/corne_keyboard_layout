# Corne keyboard-layout

Source README located [here](https://github.com/qmk/qmk_firmware)

1. [Layout](#layout)
2. [Brief description of the files](#brief)
3. [Compile qmk](#compile)
4. [Useful links to practice typing](#links)

## 1) <a id='layout'></a> Layout

### Key layout

<div align="center">
<img src="https://github.com/razielar/corne_keyboard_layout/blob/main/img/corne_layout.png" alt="logo"></img>
</div>

Keys-code located [here](https://config.qmk.fm/#/mechlovin/infinity875/LAYOUT_all). If a key is defined once, means either is the same key in the 4 layers or is not defined in other layers.  
TD= tap-dance.

### Led layout 

We have 6 back-leds, and 21 (7-27) front-leds. 

<div align="center">
<img src="https://github.com/razielar/corne_keyboard_layout/blob/main/img/corne_ledsNum.png" alt="logo"></img>
</div>


## 2) <a id='brief'></a> Brief description of the files

* **1)** `keymap.c`: (the most important file)

* **2)** `config.h`: defines which is the master, tap-dance time, rgb-brightness, all rbg-effects, etc. 

* **3)** `rules.mk`: basic configuration such as: enable tap-dance, rgb, oled-screen on, etc.

* **4)** `glcdfont.c`: fonts, we did not modified. 


## 3) <a id='compile'></a> Compile qmk

Click two times the reset-button (twice each for side).


``` bash
qmk flash -kb crkbd -km razielar
```

## 4) <a id='links'></a> Useful links to practice typing

* [English typing](https://www.colemak.academy/)
* [Code typing](https://www.speedcoder.net/lessons/py/1/)



# やること

- 教科書の37-53P, 75-二章末までをざっと目を通す
- 真似をしながら ROS 経由でMouseを自走させる
- 第三部の応用分野に最低一人一つ手を出し, ものにする
- 障害物走行ができる状態を作る

質問等ありましたら @yasu80 かコラボレータにどうぞ.

# Installation

```bash
$ cd <catkin_ws>/src
$ git clone --recursive https://github.com/CIR-KIT/raspi_mouse_pkg.git
```

Or same command is

```bash
$ cd <catkin_ws>/src
$ git clone https://github.com/CIR-KIT/raspi_mouse_pkg.git
$ cd raspi_mouse_pkg
$ git submodule init
$ git submocule update
```

# Ref
- [注意事項集](https://github.com/CIR-KIT/raspi_mouse_pkg/wiki )
- [公式サンプル](http://opencv.jp/sample/object_detection.html)

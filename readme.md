# Thumbnails

![](example.jpg)

## Installation

Installing dependencies can be a really painful experience, painful enough to scare you away.

You should install the following packages:

+ Python 3 (of course)
+ Pillow (PIL)
+ ffmpeg
+ PyAV

If you have managed to install all above, congratulations! Enjoy~!


## Usage

The only thing that is currently very much needed to configure is the font. You should carefully choose a truetype font,
something like `*.ttf` and put it in the current directory, specify the font name in `thumbnail.py`. Done!

You may notice that files are renamed and some temporary files are created when running the program. This is due to the
ridiculous bug in PyAV which nobody cares. I would really appreciate it if someone could repair this bug.

## 修改后使用要点

1 需要在py文件内指定font文件的绝对路径

2 运行后第一个输入处理的目录，第二个输入输出目录，会按照原有目录结构在输出目录下创建

3 可以自行修改大小以及不想要的信息

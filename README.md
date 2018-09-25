# legofy
Build pictures with LEGO®

![There should be an image here.](https://lineupr.com/images/157/9d185fd0b0ca44ece3fe01f8f24cdebc/a69c31db7c.jpeg)

### Install
Just get all packages with (make sure that you are using Python 3):

```bash
pip3 install -r requirements.txt
```

### Usage
The `legofy.py` script can be executed via
```bash
python3 legofy.py [options]
```

The options should be printed if you call `python3 legofy.py -h`

```
>>> python3 legofy.py -h
usage: legofy.py [-h] -i INPUT [-o OUTPUT] [-sm SMOOTH] [-s SIZE]
                 [-ms MAXSIZE] [-rgb RGB]

Legofy your image.

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT, --input INPUT
                        input image
  -o OUTPUT, --output OUTPUT
                        output xml file. Defaults to out.xml and overwrites
                        any previous output with the same name.
  -sm SMOOTH, --smooth SMOOTH
                        Smoothing factor for prefiltering. Increase for
                        removing artifacts. Can only be odd. Defaults to 1.
  -s SIZE, --size SIZE  Max size for the output image in pixels/studs.
                        Defaults to 32.
  -ms MAXSIZE, --maxsize MAXSIZE
                        Max size of an individual LEGO plate in studs.
                        Defaults to 12.
  -rgb RGB              If not zero, RGB is used for distances between pixels,
                        otherwise LAB. Defaults to 1.
```

Have fun legofying around!

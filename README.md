# Image Resizer Using Pyhton
So, I was working on this one project where I needed to place equal size images. To make it look good.

But doing one picture at a time is such a waste. So, I created this simple script to make this easy for me.

## Usage

```
image-resizer.py [-h] [--src source] [--dest destinantion]
                        [--size size [size ...]]
                        [--ext extension [extension ...]]

optional arguments:
  -h, --help            show this help message and exit
  --src source          Source folder of the Image files
  --dest destinantion   Destination folder of the Image files (Default: Source
                        folder)
  --size size [size ...]
                        Size of the new image(Width Height)
  --ext extension [extension ...]
                        Extensions of files to be resized (Default: jpg png).
						Supported extensions - Extensions Supported by OpenCV.
```

## Dependencies
Only dependecy is **OpenCV2**
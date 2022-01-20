# fry
Image deep-fryer for when you want to make something a JPEG for no reason.
## Usage
Running `fry` alone will lightly crisp the image in your clipboard. Giving an input and output file as arguments (eg. `fry image.png crispyimage.png` will use those instead of the clipboard. Using the `-i` flag and giving one output file (eg. `cat image.png | fry -i crispyimage.png` will use standard input. The `-d` flag can be used to numerically specify how deep you want to fry the image, ranging from 0 to 3 (eg. `fry -d 2`)
## Installation
Requires `xclip`, `imagemagick`, and a burning hatred for lossless compression.
Simply download the script using `git` or any other way to put text on your hard drive, then put the script in `~/.local/bin` or somewhere else to that effect.

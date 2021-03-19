# SMPL Viewer

A simple tool for rendering and manipulation of the parameteric 3D human
body model SMPL.

*Disclaimer: I am not affiliated with the authors of SMPL. If you need
help with the SMPL model please refer to: http://smpl.is.tue.mpg.de/.*

## First steps

Download and set up the SMPL model from here: http://smpl.is.tue.mpg.de/.

## Installation
```
git clone git@github.com:thmoa/smpl_viewer.git
cd smpl_viewer
ln -s <path to your smpl installation> smpl
pip install -r requirements.txt
```

## Troubleshooting

if the installtion of opendr fails using python3

install following libs: 
sudo apt install libosmesa6-dev

sudo apt-get install build-essential

sudo apt-get install libgl1-mesa-dev

sudo apt-get install libglu1-mesa-dev

sudo apt-get install freeglut3-dev

and run again: sudo pip install opendr

taken from: https://github.com/akanazawa/hmr/issues/82

## License
MIT

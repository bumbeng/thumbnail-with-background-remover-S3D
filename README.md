# thumbnail-with-background-remover-S3D

![new](https://github.com/bumbeng/thumbnail-with-background-remover-S3D/assets/111509593/1a7305c4-aa9a-4c48-a9ff-588afc7a6bdb)


Original-Code: https://github.com/fabiorinaldus399/gcode-tumbnail-generator-for-Simplify3D

Instructions to add background remover [WINDOWS ONLY]
- install OpenScad: https://openscad.org/downloads.html
- install Python: https://www.python.org/downloads/
- add my StlToImg.py file to StlToImg Folder
- add this line with *your*! location of StlToImg.py `python C:\Users\sasch\Desktop\StlToImg\StlToImg.py --gcodename "[output_filepath]" --codepath C:\Users\sasch\Desktop\StlToImg`

  Open cmd and install dependencies:
   - `py get-pip.py`
   - `pip install PyQt5 argparse pillow`

Change Image size
- add arguments: `--height 300 --width 300` (choose your preferred size)
  
#Note 
If you want to add more than one stl file to your buildplate you need to combine it in simplify then export this file and import the combined stl! So You can get an thumbnail of more than 1 stl.

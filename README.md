# Hongming's notes
## see the notes: win10_python3.5(keras)_python3.7(torch).docx if you want to install two pythons on win10, and one python using keras, another using torch

win10+pycharm+install geopandas, where I encountered the errors to install by using pip, the soluions are:
https://stackoverflow.com/questions/34427788/how-to-successfully-install-pyproj-and-geopandas

Under windows

As @Marcus Williams states:

Download Fiona and GDAL Windows Binaries corresponding your python environment (32, 64bit and 2.7 3.3 etc. (from http://www.lfd.uci.edu/~gohlke/pythonlibs/) and go in cmd with cd to directory where downloaded files are and install the .whl files using the command

pip install filename.whl
Finally:

pip install geopandas

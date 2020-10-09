# Hongming's notes
## see the notes: win10_python3.5(keras)_python3.7(torch).docx if you want to install two pythons on win10, and one python using keras, another using torch

(1) win10+pycharm+install geopandas, where I encountered the errors to install by using pip, the soluions are:
https://stackoverflow.com/questions/34427788/how-to-successfully-install-pyproj-and-geopandas

Under windows

As @Marcus Williams states:

Download Fiona and GDAL Windows Binaries corresponding your python environment (32, 64bit and 2.7 3.3 etc. (from http://www.lfd.uci.edu/~gohlke/pythonlibs/) and go in cmd with cd to directory where downloaded files are and install the .whl files using the command

pip install filename.whl
Finally:

pip install geopandas

In my case: I downloaded: GDAL‑3.0.4‑cp37‑cp37m‑win_amd64.whl, Fiona-1.8.13-cp37-cp37m-win_amd64.whl

first install GDAL, then Fiona, finally geopandas

(2) in my lab win10 computer with python3.7, I installed pysal 2.0.0 successfully

---------------------------------------------------------------------------------
(1) The shell to access linux machine: (i) SSH Secure Shell Client (ii) MobaXterm

Nuclei Segmentation Link:

https://jgamper.github.io/PanNukeDataset/




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

(2) CPU, GPU, SSD -> speeding up deep learning

## Pan-cancer nuclei segmentation and classification demo:
https://jgamper.github.io/PanNukeDataset/

## about sparseconvnet installation on our server

(1) download the github files from the website: https://github.com/facebookresearch/SparseConvNet
(2) run bash develop.sh, it may report the error: OSError: CUDA_HOME environment variable is not set. Please set it to your CUDA install root.
    solve the problem by the following the solution: https://blog.csdn.net/OOFFrankDura/article/details/113632416
    一次性:在命令行
    export CUDA_HOME=/usr/local/cuda-X.X

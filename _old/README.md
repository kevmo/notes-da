mkdir python-so && cd python-so # root project

mkdir data # this is where your raw and processed data will live

conda create --name PYTN python=3.6 # new virtual environment

source activate PYTN # activate new virtual environment

conda install numpy pandas matplotlib # install packages

jupyter notebook # navigate to localhost:8888 # start jupyter server

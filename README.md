This repository contains the files used while watching the the Cell Factory Design Tutorial.

Here are the steps I took to get to the point shown in Cobrapy_Practice.ipynb:

Equipment used was a MacBook Pro.

INSTALLING JUPYTER NOTEBOOK:

In the terminal, the following commands were used:

cd OneDrive

mkdir venv

cd venv

python3 -m venv

source bin/activate

pip3 install notebook

pip3 install cobra

pip3 install escher

pip3 install cameo

jupyter notebook

----- UP TO THIS POINT COBRAPY WAS WORKING BUT ESCHER WASN'T, THE ISSUE WAS FIXED BY UPDATING EVERYTHING: ------

python3 -m pip3 install --upgrade python
pip3 install --upgrade pip
pip3 install -U notebook
pip3 install -U cobrapy
pip3 install -U escher
pip3 install -U cameo

----- BY DOING THIS ESCHER STARTED WORKING BUT AN ERROR WAS SHOWN REGARDING THE CAMEO LIBRARY, DEBUGGING IS STILL IN PROCESS -----

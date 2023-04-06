## NOTE: PLEASE ENSURE YOU CHANGE THE DIRECTORY PATHS INSIDE THE PYTHON FILE IN ORDER TO MAKE SURE THE CODE CAN RUN ON YOUR MACHINE.
## THE DIRECTORIES USED IN THE FILE ARE FOR MY LOCAL MACHINE SO THEY WILL NOT WORK FOR YOU.

## using conda, create a new environment
>> conda create --name FinalProject python=3.9.16
>> conda activate FinalProject

## Packages to install
>> pip intall pandas
>> pip intall librosa
>> pip intall openpyxl
>> conda install tensorflow

## These were the only Packages we installed, all the other packages should come standard with Anconda.
## Also, this project was ran on VS code, but if you want to run it using the jupyter notebook on your browser, first install
## the following packages inside your Anconda environment.

>> conda install ipykernel
>> conda install nb_conda_kernels

## Once you have these installed these, run the folling command:

>> jupyter notebook

## from here simply navigate to the directory where the python notebook is located and open the notebook.
# checker_easyAI

1. Python installation and configuration 
You can use either method, but method (2) is preferred. 
 
(1) Using pip (recommended method) 

i. Download python for your operating system (OS), see here1 

ii. Installed downloaded file to your OS. 

iii. Validate that you have python install make sure that you have python by 
running the following command below. 

    python --version

It will print current version of your python interpreter.  
iv. Install pip with python, see here2 

    python -m pip install --upgrade pip 
v. Validate that you have pip install make sure that you have pip by running the 
following command below 

    python -m pip --version 

(2) Using Conda 

a. Download conda for you operating system, see here3 

b. Open terminal and check that conda is installed.  
Note: if you use Windows, you must search for “Anaconda Prompt” 

c. Create conda environment create conda environment and install python version 

3.8 (you can use any python version that is compatible with easyAI).  

    conda create -n py38 python=3.8
d. Activate conda environment 

    conda activate py38
e. Check that your conda environment is activated.  
There are many ways to check. One way is to run the following command. 

    conda info --envs
 
 
2. EasyAI installation 
Follow instructions in the easyAI GitHub repo: https://github.com/Zulko/easyAI  

    sudo python -m pip install easyAI
    
download the repository and navigate to the checker_easyAI folder on your computer

run the file:

    python p1_FAUKTudor2018.py
'''

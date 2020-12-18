# Algorithms-course-project
Purpose of the project:
UML shuttle algorithm 

* First you will have to download Gurobi on the computer. The steps are:

1) Downloading Anaconda (If you have Anaconda skip this step):

   - Download Anaconda through this URL: 
     https://www.anaconda.com/products/individual

   - Once downloaded open the package and the computer will prompt you with the directions to be taken to complete setup. 
   
2) The next step is to install the Gurobi package into Anaconda. You do this by first adding the Gurobi channel to your Anaconda channels and then installing the gurobi package from this channel.

   - From a terminal window issue the following command to add the Gurobi channel to your default search list,

     conda config --add channels http://conda.anaconda.org/gurobi

   - Now issue the following command to install the Gurobi package

     conda install gurobi
   
   - You can remove the Gurobi package at any time by issuing the command

     conda remove gurobi

3) Once you have downloaded gurobi, you need a license to run gurobi on your machine.
 
  - From a terminal window issue the following command

    grbgetkey 

  - Copy and paste any of the following keys 
   
    . b8012dd0-1fe6-11eb-a04c-020d093b5256
    . 2cdf5750-1fea-11eb-bd86-0a7c4f30bdbe
    . 95f9479e-20c3-11eb-9ec4-0a7c4f30bdbe

  - It will prompt you with the directory you would like to store the license file

    press y

4) Your laptop will now be able to run the gurobi optimizer


* Now to run our program please follow these steps:

1) Open Anaconda and launch the Jupyter Notebook. You will redirected you to your local browser. 

2) Please upload our notebook to Jupyter.

3) Double click on our file and you will be redirected to our program.

4) Run the program for further instructions. 

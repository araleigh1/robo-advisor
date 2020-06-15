# robo-advisor

Steps to setup the robo-advisor python program

1) Clone or download the repo from github (https://github.com/araleigh1/robo-advisor) with the README and Gitignore files (specific to Python) and save it to a local drive
2) Go to the directory in Gitbash or Terminal
3) In Gitbash, create a virtual environment in Conda by typing conda create -n stocks-env python =3.7
4) Activatae the virtal environment by typing conda activate stocks-env
5) Install the required packages by typing pip install -r requirements.txt
6) In Visual Studio Code, create a .env file in the robo-advisors folder
7) Go to AlphaAdvantage (https://www.alphavantage.co/) and signup for a unique API code
8) In the .env file, copy the message ALPHAVANTAGE_API_KEY="" and paste your unique API code within the quotes
9) In the data folder, create a CSV file called prices.csv
10) In the data folder, create a .gitignore file and paste the message below and delete the "()" around the hashtags

(#) data/.gitignore

(#) h/t: https://stackoverflow.com/a/5581995/670433

(#) ignore all files in this directory:
*

(#) except this gitignore file:
!.gitignore
11) In gitbash, type python app/robo_advisor.py to run the program
12) Type in a valid NYSE stock sybmol to pull the stock information
13) Happy trading!
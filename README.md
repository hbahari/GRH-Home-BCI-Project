# GRH-Home-BCI-Project

This directory includes the files required to build GRH-Home-BCI application. This application is meant for generating keyboard key-presses utilizing inputs from Emotiv Brain-Computer Interface (BCI) software. "User" information (Client-ID, Secret, and User-ID) need to be changed for each user.  

in order to use this app:

1- you will need to install the dependencies listed in requirements.txt file.

pip3 install -r requirements.txt

2- you will need to aquire a unique "Client ID" and "Client Secret" from Emotiv Cortex websit which will be tied to your Emotiv Cortex account and credentials. 

3- after entering your client id and secret in the required fields in main.py . you can build the model. pyinstaller is recommended

This application is primarily used by Glenrose Rehabilitation Hospital for its Home-BCI program 

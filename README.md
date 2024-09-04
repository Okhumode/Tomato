# Tomato script process
## First gain  super user permissions by running the command below
```sh
sudo su
```
### 1. Open Your VPS
```sh
cd Tomato
```
### 2a. navigate to data folder
```sh
cd data
```
### 2b. edit your config.py file, input your API ID and HASH into it. ensure that your API HASH is within the paranthesis that was provided e.g

"19a5e2a0395cb7eaa6c9d1940595a5a4"

The API ID should not be in parenthesis
```sh
nano config.py
``` 
### 3a. After editing your config.py file, save it:
CTRL O

ENTER 

CTRL X
### 3b. Go to the previous directory 
```sh
cd ..
```
### 4. Install requirementsts
```sh
python install.py
```
### 5. Run main.py
```sh
python main.py
```
### 6. Create a session
```sh
1
```
Enter a name for your session input any name you like

ENTER

enter your telegram phone number, include your country code while typing it. e.g 2348145698452

ENTER

check your telegram app for otp and input it

ENTER
ENTER 
### 7. Create a screen
```sh
screen -R Tomato
```
### 8. Run main.py again
```sh
python main.py
```
### 9. Run clicker
```sh
2
```
CTRL AD
### 10. Close the VPS and open and run the next script

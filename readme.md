# Aux Project 1 -  Shell Scripting
In this project, you need to onboard 20 new Linux users onto a server. Create a shell script that reads a csv file that contains the first name of the users to be onboarded.
* Create the project folder called Shell
```
mkdir Shell
```
* Open the names.csv file
```
vim names.csv
```

![](./aux-project-images/mkdir.png)

* Insert some random names into it. (One name per line)

## Shell Script 
* The script you created should read the CSV file, create each user on the server, and add to an existing group called developers (You will need to manually create this group ahead).

* Ensure that your script will first check for the existence of the user on the system, before it will attempt to create it.

* Ensure that the user that is being created also has a default home folder

![](./aux-project-images/ScreenShot_5_1_2022_9_45_04_AM.png)

* Ensure that each user has a .ssh folder within its HOME folder. If it does not exist, then create it.

![](./aux-project-images/ScreenShot_5_1_2022_9_43_35_AM.png)

* For each user’s SSH configuration, create an authorized_keys file and ensure it has the public key of your current user.

![](./aux-project-images/ScreenShot_5_1_2022_9_43_50_AM.png)


Here is a [DEMO](https://clipchamp.com/watch/5OcqPU6aeZi) of the entire process
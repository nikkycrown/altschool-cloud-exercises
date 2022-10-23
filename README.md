This is a private repo for my Altschool Cloud Exercises.

# ifconfig result

![Screenshot (3)](https://user-images.githubusercontent.com/109033746/195026255-e4ccae10-5012-4fce-bc58-2c57cad88b2c.png)

# linux commands
* $id - shows the user identity
* $free - displays memory and swap usage
* $cal - show the current month calendar

![Screenshot (5)](https://user-images.githubusercontent.com/109033746/195029259-e0243754-e37a-467d-8dba-6f35778cd01d.png)

* $compgen -c - used to reference all available commands
![Screenshot (6)](https://user-images.githubusercontent.com/109033746/195031972-a584a9bd-fdd3-415c-af90-1a4f2b9066ab.png)

* $history - lists most recent coommands
![Screenshot (7)](https://user-images.githubusercontent.com/109033746/195033425-c866a75b-2fcb-4cea-8b3a-579e05300fb1.png)

* $ compgen -a - used to reference all available aliases
* $ compgen -d - used to reference all available functions
![Screenshot (8)](https://user-images.githubusercontent.com/109033746/195034475-2e321c16-30a8-488d-ae32-7f8f675dd7fa.png)

* $alias c=clear - sets clear alias to be c. Clears the screen/terminal
![Screenshot (9)](https://user-images.githubusercontent.com/109033746/195035475-a58cac9c-c6e4-4a9a-a79b-86c9d36d3a82.png)

* $timedatectl - shows more details about date and time
* $exit - exits out of directory
![Screenshot (13)](https://user-images.githubusercontent.com/109033746/195036343-14c28c02-1af1-4bfd-8230-eef7ce090903.png)

# Timezone changed to Africa/Lagos

![Screenshot (12)](https://user-images.githubusercontent.com/109033746/195037911-fa167102-ffd6-42f8-a443-8eec1bd352f9.png)

# i learnt how to create groups, users and generate ssh keys.
* content of /etc/passwd
* content of /etc/group
* content of /etc/sudoers

![Screenshot (18)](https://user-images.githubusercontent.com/109033746/195040157-7876ae17-a781-4a10-a785-4b696063141a.png)
![Screenshot (16)](https://user-images.githubusercontent.com/109033746/195040292-443f6005-9481-4b6a-9f2f-78e82e2d5c16.png)
![Screenshot (17)](https://user-images.githubusercontent.com/109033746/195040497-c5c45f6e-a9f6-4252-8bd4-2660ff0e2d7c.png)

# i learnt how to use the add-apt-repository command and installed PHP 7.4 on my linux machine using the ppa.ondrej/php package repo
* $php -v
* /etc/apt/sources.list

![Screenshot (20)](https://user-images.githubusercontent.com/109033746/195042611-15920e44-179a-4c41-9108-f55c0d834b9a.png)
![Screenshot (21)](https://user-images.githubusercontent.com/109033746/195042881-237dd4b5-911a-4ddc-acd4-1ba6f5a82500.png)

# Exercise 6
* git config -l
* git remote -v
* git log

![Screenshot (23)](https://user-images.githubusercontent.com/109033746/197366540-996ca326-0186-439f-ba33-2c51f2fc1efe.png)
![Screenshot (24)](https://user-images.githubusercontent.com/109033746/197366650-9a9ed585-0853-4248-8987-137d4eded7d3.png)
![Screenshot (26)](https://user-images.githubusercontent.com/109033746/197366664-454688da-db9c-48e7-84fc-57a6b0fea85b.png)

# I created a bash script to run at every hour, saving system memory (RAM) usage to a specified file and at midnight, it sends the content of the file to a specified email address :
* content of script
* cronjob
* sample of email sent and attached file :

![Screenshot (30)](https://user-images.githubusercontent.com/109033746/197367161-8e40591c-e7b8-454b-9408-9894fc48af0c.png)
![Screenshot (27)](https://user-images.githubusercontent.com/109033746/197367170-c52475a5-0986-487f-99f1-d06e6d0a2c2c.png)
![Screenshot (33)](https://user-images.githubusercontent.com/109033746/197367202-04e2261f-36c6-460a-9608-31b1954070eb.png)
![Screenshot (34)](https://user-images.githubusercontent.com/109033746/197367216-5021a771-3b2a-4402-ab62-e5ee1cb6e768.png)

# IP addressing exercise
## Given IP - 193.16.20.35/29 :
### * Netmask = 11111111.11111111.11111111.11111000 - 255.255.255.248
### * Wildcard = 7 (255-248)
### * Network IP = 193.16.20.32
### * Number of Host = 6
### * Range of IP address = 193.16.20.33 (HostMin) - 193.16.20.38 (HostMax)
### * Broadcast IP = 193.16.20.39

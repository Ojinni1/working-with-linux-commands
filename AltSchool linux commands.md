# Assignment 
Your login name: altschool i.e., home directory /home/altschool. 
The home directory contains the following sub-directories: code, tests, personal, misc Unless otherwise specified, you are running commands from the home directory.
a.Change directory to the tests directory using absolute pathname
b.Change directory to the tests directory using relative pathname
c.Use echo command to create a file named fileA with text content ‘Hello A’ in the misc directory
d.Create an empty file named fileB in the misc directory
e.Copy contents of fileA into fileC
f.Move contents of fileB into fileD
g.Create a tar archive called misc.tar for the contents of misc directory h.Compress the tar archive to create a misc.tar.gz file
I. Create a user and force the user to change his/her password upon login
J. Lock a users password
K. Create a user with no login shell
L. Disable password based authentication for ssh
M. Disable root login

# Solution
### A. create a user named Altschool
![useradd](./images/useradd.png)

This image shows how i created AltSchool user into out home directory

###  give our User(AltSchool) a password
![userpasswd](./images/givinguserpasswd.png)

This image depicts how i give the user a password, each time i login its going to require this password

### Adding our user(AltSchool to sudoers group)
![addingosudoers](./images/adding%20altschool%20to%20sudoers%20-%20Copy.png)

as this can be optional i choose to add the user to sudoers at this stage

### switch to the user
![switchtouser](./images/switching%20to%20altschool%20user.png)

now have switched to AltSchool User

### creating the directories
![creatingdirectories](./images/creating%20the%20files.png)

this image depicts how i created the directories as instructed

### Changing the directory to tests using absolute pathname 
![absolutepathname](./images/absolute%20pathname.png)

this image depicts chnaging directory to tests using absolute path

### Changing the directory to tests using relative pathname
![relativepathname](./images/relative%20pathname.png)

this image depicts chnaging directory to tests using absolute path

### using echo command to create a fileA with content in the misc directory
![fileAwithcontent](./images/fileA%20and%20content.png)

the image above shows how we can use echo command to create a file with content in it

### creating an empty fileB in the misc directory
![fileB](./images/empty%20fileB.png)

the image above shows how we can use echo command to create a file with no content in it

### Copying contents from fileA to fileC
![Copyingcontent](./images/copying%20fileA%20into%20fileC%20-%20Copy.png)

the image above shows how we can copy content from fileA into fileC, the ls only list the files withing the misc directory for us to be sure we have the said file copied

### moving content from fileB to fileD
![movingfiles](./images/moving%20fileB%20into%20fileB.png)

the image above shows how we can move content from fileB into fileD the ls only list the files within the misc directory for us to be sure we have the said file moved

### creating a tar archive
![tararchive](./images/tar%20archieve.png)

### to compress the tar archieve to create misc.tar.gz file
![gzip](./images/gzip.png)


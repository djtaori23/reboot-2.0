# Problem #4
## Share and files and folder 

* #### Create two users name Jack and Jill  from command line.
* #### Create all the data under home directory of each users.
* #### Login with Jack user and create a file name  Jack.txt using vim editor and write "hello jack".
* #### From jack user also create two directories name Jack1 & Jack2.
* #### Now login from Jill user and create a file. Jill.txt using vim editor and write "hey jill".
* #### From Jill also create two directoires named Jill1 & Jill2.
* #### Swap these files and directories in between users.
#### IMPORTANT : To swap don't use root account.

## Solutions:

### i) Create two users name Jack and Jill  from command line.
### Answer:
```
sudo useradd Jack
```
>> New User 'Jack' is created.
```
sudo passwd Jack
```
>> Password is set-up for the user.
```
sudo useradd Jill
```
>> New User 'Jill' is created.
```
sudo passwd Jill
```
>> Password is set-up for the user.
<img src="images/4.1.png">

### ii) Login with Jack user and create a file named Jack.txt using vim editor and write "hello jack".
### Answer:
```
su - Jack -> Password:
```
>> Logged into 'Jack'
```
vim Jack.txt
```
>>File would be opened in vim
now, press `i`(it will take you in Insert Mode) and then type `hello jack`. After that press `esc` and type `:wq` and press `enter`, it will save your file and will return to terminal.
<img src="images/4.2.png">

### iii) From jack user also create two directories named Jack1 & Jack2.
### Answer:
```
mkdir Jack1 Jack2
```
`ls` (this will show you directories are made.)

`logout` (to logout of account 'Jack')

<img src="images/4.3.png">

### iv) Now login from Jill user and create a file named Jill.txt using vim editor and write "hey jill".
### Answer:
```
su - Jill -> Password:
```
>> Logged into 'Jill'
```
vim Jill.txt
```
>>File would be opened in vim
now, press `i`(it will take you in Insert Mode) and then type `hey jill`. After that press `esc` and type `:wq` and press `enter`, it will save your file and will return to terminal.
<img src="images/4.4.png">

### v) From Jill also create two directoires named Jill1 & Jill2. 
### Answer:
```
mkdir Jill1 Jill2
```
`ls` (this will show you directories are made.)

`logout` (to logout of account 'Jill')

<img src="images/4.5.png">

### vi) Swap these files and directories in between users.

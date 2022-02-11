# Streamlining ssh Configuration

## File/Editor

![Image](Config.png)
>Created a new file using windows built-in notepad.

Before using the command ```~\.ssh\config``` I had to create a new file Config that held my Host, User, and Identity files. 

## ssh Command Login

![Image](ALI.png)
>ssh command logging into account using alias, **ieng6**

I then logged in using the command ```ssh ieng6``` instead of using the command ```ssh cs15lwi22arf@ieng6.ucsd.edu.``` 


## scp Command Copy File

![Image](copy.png)
>scp command copying file into account using alias

After I was able to log in using ```ssh ieng6```, I then copied the config file from my computer to the server using the command ```scp config ieng6:~/```. Once it was copied over, I longed into my ieng6 account again and called ```dir``` to assure it made it into my account.

# salt_pepper
Brute force encrypted file with cipher and pass

### Usage 
```
Usage: salt-pepper [-f SOURCE FILE] [-p PASS ] [-t]

Brute force encrypted file with cipher and pass

Main options: 
	-f	encrypted source file 
	-p	passphrase 
	
More options:
	-t 	test results to find Unicode text file	
	-h	display help
	-v	display version
```
All files are saved in the **FLAGS** directory. 

### Example
```
./salt-pepper -f salted-file -p "PASSWORD" -t
```
> The `-t` option allows you to check if a file is in Unicode format.

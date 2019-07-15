# salt_pepper
Brute force encrypted file with cipher and pass.

## Usage 
```
Usage: salt-pepper [-f SOURCE FILE] [-p PASS ] [-t]

Brute force encrypted file with cipher and pass

Main options:
	-f	encrypted source file 
	-p	passphrase 
	
More options:
	-t 	test results
	-u	return Unicode text file
	-a	return ASCII text file
	-h	display help
	-v	display version
```
All files are saved in the **FLAGS** directory. 

## Recovery 
To retrieve the script and give it execution rights, it's easy to use the following commands:
```
git clone https://github.com/penthium2/salt_pepper.git ; cd salt_pepper ; chmod u+x salt-pepper
```
## Example
Test all possible algorihtms and then display the number of files that correspond to the **ascii** or **unicode** format.
```
./salt-pepper -f salted-file -p "PASSWORD" -t
```
Display the file in Unicode format:
```
./salt-pepper -f salted-file -p "PASSWORD" -u
```

---
Suggestions/improvements
[welcome](https://github.com/penthium2/salt_pepper/issues)!

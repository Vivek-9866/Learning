# **BANDIT LEVELS**
# Recommendation:
-"Try to solve the level on your own. It is the only true way to learn. Use the lesson learnt section for each level to understand the command that would be useful to complete that level. If you are still stuck, go through the walk-through for the level".

# What is bandit :
it is a game based tool it would be fun when you work with Good mood.......HAHA
A game where you:
solve security puzzles, hack systems legally, find hidden passwords..

Each level:
.find password, ..use Linux commands, ...jump tp next level
Search → Read → Think → Crack → Next

## Commands "::"
  # command               # Used                                # where we use                                                #why we use.....
   1.mkdir                 .- creating new folder                   .- projects/storing files                                      .- to organise files

   
   2.rmdir                  .- delete directory                     . - ex: rm file.txt                                            .- removing unwanted folders

   
   3.touch                   - create file                            - ex: touch notes.txt                                          .- create empty file

   
   4.chmod                  - Change permissions                    .- Real use 1.Scripts,Secure password files                      .- Control who can read/write/execute
   
                                                                    .-ex:chmod 777 file.txt
                                                                    
   5.cp                       - copy file                               - ex:cp file.txt /home/user/                                    .- backup or dupilcate
   

   6.mv file.txt folder/      .- move/cut file                         -ex:mv old.txt new.txt                                          .- Move OR rename
   

   7.cp -r folder1 folder2     .- copy directory                        - ex:cp -r folder1 folder2                                      .-  copy entire folder with files

   8. mv folder1 /home/user/    .-move directory                         -----------                                                   . - same as files
   
   9. "*"                        .- Select all files                   - ex:rm * ,cp * backup/                                            . - Wildcard → select everything

   
   10. find                       . - Find required file               - ex: find / -name password.txt                                 . - Search hidden or specific files

   
   11.grep "password" file.txt     --------                               .- search inside files
   

   12. nano file.txt                .- Edit suing Nano                    -----------                                              .- Edit text easily inside terminal

# Here some important keys:
CTRL + O → save ,
CTRL + X → exit ,
CTRL + K → cut line.

   ## Now we can start  doing Levels.... Be carefull doing the levels....chill Bro $$      

                        


 ## level-0
- username - bandit0
- password - bandit0
- connect -
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
 ## level-1
- username - bandit1
- password 
```
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```
## Commands:
- ls- check the how many Files are there.
- Cat-To read the content of the file type.
- Find- it tell the what are there in that.

- connect -
 ```
 ssh bandit1@bandit.labs.overthewire.org -p 2220
```
- <img width="1447" height="305" alt="image" src="https://github.com/user-attachments/assets/6e661437-b4ce-4077-a39c-b47a54a16ca9" />


  ## level-2
- username - bandit2
- password -
 ```
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```
 ## Commands:
- the file name is- ‘ -’.
- "."=type in './-'

- connect -
```
ssh bandit2@bandit.labs.overthewire.org -p 2220
```

 ## level-3
- username - bandit3
- password
   ```
   MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
   ```
## Commands:
- The name of the file is ‘spaces in this filename’. When you try to cat out the filename as is, since there are spaces in the name of the file, the command assumes each word separated by space to be a separate file.
- du - estimate file space usage.

 ## level-4
- username - bandit4
- password
   ```
   2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
   ```


- connect -
```
ssh bandit4@bandit.labs.overthewire.org -p 2220
```

 ## level-5
- username - bandit5
- password
   ```
   4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
   ```
## commands:
- ls -la
- cd inhere/
- ls
- file ./*
- cat ./-file07
- ssh bandit5@localhost

- - connect -
```
ssh bandit5@bandit.labs.overthewire.org -p 2220
```
 ## level-6
- username - bandit6
- password
   ```
   HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
   ```
## Commands: Type one by one
- ls
- cd inhere/
- ls
- find . -size 1033c
- cat ./maybehere07/.file2
- ssh bandit6@localhost

- - connect -
```
ssh bandit6@bandit.labs.overthewire.org -p 2220
```

 ## level-7
- username - bandit7
- password
   ```
   morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
   ```
## Commands:
- find / -user bandit7 -group bandit6 -size 33c
- cat /var/lib/dpkg/info/bandit7.password
- ssh bandit7@localhost
- - connect -
```
ssh bandit7@bandit.labs.overthewire.org -p 2220
```
 ## level-8
- username - bandit8
- password
   ```
   dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
   ```
## Commands:
-  man - an interface to the system reference manuals
-  ls
- cat data.txt | grep millionth
- ssh bandit8@localhost
- - connect -
```
ssh bandit8@bandit.labs.overthewire.org -p 2220
```

  ## level-9
- username - bandit9
- password
   ```
   4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
   ```
## Commands:
- cat data.txt | sort | uniq -u
- ssh bandit9@localhost
- - connect -
```
ssh bandit9@bandit.labs.overthewire.org -p 2220
```
  ## level-10
- username - bandit10
- password
   ```
   FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
   ```
## Commands:
- - ls
- strings data.txt | grep ==
- ssh bandit10@localhost
- - connect -
```
ssh bandit10@bandit.labs.overthewire.org -p 2220
```
  ## level-11
- username - bandit8
- password
   ```
   dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
   ```
## Commands:
-ls
- cat data.txt | base64 --decode
- ssh bandit11@localhost
- - connect -
```
ssh bandit11@bandit.labs.overthewire.org -p 2220
```
  ## level-12
- username - bandit12
- password
   ```
   7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

   ```
## Commands:
- ls
- cat data.txt | tr a-zA-Z n-za-mN-ZA-M
- ssh bandit12@localhost
- - connect -
```
ssh bandit12@bandit.labs.overthewire.org -p 2220
```
  ## level-13
- username - bandit13
- password
   ```
   FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
   ```
## Commands:
- ls
- cd /tmp/inigo12
- ls
- file data.txt
- xxd -1 data.txt data1
- cat data.txt
- xxd -r data.txt > data01
- ls
- cat data09
- - connect -
```
ssh bandit13@bandit.labs.overthewire.org -p 2220
```

-  ## level-14
- username - bandit14
- password -
   ```
   MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
   ```
## Commands:
- 
- - connect -
```
ssh bandit14@bandit.labs.overthewire.org -p 2220
```

-  ##level-15
- username - bandit15
- password
   ```
   8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
   ```
- - connect -
```
ssh bandit15@bandit.labs.overthewire.org -p 2220
```
<img width="551" height="168" alt="image" src="https://github.com/user-attachments/assets/16b2d6a2-b21d-49ef-8ed2-b2fac3f4fb37" />


-  ##level-1
- username - bandit1
- password
   ```
   
   ```
#Commands:
- 
- - connect -
```
ssh bandit13@bandit.labs.overthewire.org -p 2220
```

-  ##level-1
- username - bandit1
- password
   ```
   
   ```
#Commands:
- 
- - connect -
```
ssh bandit13@bandit.labs.overthewire.org -p 2220
```

-  ##level-1
- username - bandit1
- password
   ```
   
   ```
#Commands:
- 
- - connect -
```
ssh bandit13@bandit.labs.overthewire.org -p 2220
```

-  ##level-1
- username - bandit1
- password
   ```
   
   ```
#Commands:
- 
- - connect -
```
ssh bandit13@bandit.labs.overthewire.org -p 2220
```

-  ##level-1
- username - bandit1
- password
   ```
   
   ```
#Commands:
- 
- - connect -
```
ssh bandit13@bandit.labs.overthewire.org -p 2220
```

-  ##level-1
- username - bandit1
- password
   ```
   
   ```
#Commands:
- 
- - connect -
```
ssh bandit13@bandit.labs.overthewire.org -p 2220
```




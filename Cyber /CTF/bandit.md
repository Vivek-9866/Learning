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
  - # command               # Used                                # where we use                                                #why we use.....
  
   - 1.mkdir                 .- creating new folder                   .- projects/storing files                                      .- to organise files

   
   - 2.rmdir                  .- delete directory                     . - ex: rm file.txt                                            .- removing unwanted folders

   
   - 3.touch                   - create file                            - ex: touch notes.txt                                          .- create empty file

   
   - 4.chmod                  - Change permissions                    .- Real use 1.Scripts,Secure password files                      .- Control who can   read/write/execute
   
                                                                    
   - 5.cp                       - copy file                               - ex:cp file.txt /home/user/                                    .- backup or dupilcate
   

   - 6.mv file.txt folder/      .- move/cut file                         -ex:mv old.txt new.txt                                          .- Move OR rename
   

 - 7.cp -r folder1 folder2     .- copy directory                        - ex:cp -r folder1 folder2                                 .-  copy entire folder with files

  
## Here some important keys:
- CTRL + O → save
- CTRL + X → exit
- CTRL + K → cut line.

# Here some basic commands
## Navigation:
- pwd                → Show current directory
- ls                 → List files
- ls -l              → Detailed list
- ls -a              → Show hidden files
- cd folder          → Enter folder
- cd ..              → Go back one directory
- cd ~               → Go to home directory
- ## File & Folder Management:
- mkdir folder       → Create folder
- rmdir folder       → Remove empty folder
- rm file            → Delete file
- rm -r folder       → Delete folder
- cp file1 file2     → Copy file
- mv file1 file2     → Move/rename file
- touch file         → Create empty file
- ## File Viewing:
- cat file           → Show file content
- less file          → View large file
- head file          → First 10 lines
- tail file          → Last 10 lines
- tail -f file       → Live log view
- ## Permissions:
- whoami             → Current user
- chmod 755 file     → Change permission
- chown user file    → Change owner
- sudo command       → Run as admin
- ## Search:
- find / -name file          → Find file
- grep "text" file           → Search inside file
- grep -r "text" folder      → Search in folder
-  "*"                        .- Select all files   

- ip a               → Show IP address
- ping google.com    → Check internet
- ## Terminal Shortcuts:
- Ctrl + C     → Stop command
- Ctrl + Z     → Pause command
- Ctrl + L     → Clear screen
- Tab          → Auto-complete
- history      → Command history


   ## Now we can start  doing Levels.... Be carefull bro doing the levels....chill Bro $$      

                        
## start one by one

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
- du-disk usage: du shows the actual disk space allocated on disk (in blocks), not just the file size.
- readme → maybe 16 KB (4 blocks)
- directory → maybe 4 KB
- Total ≈ 20 KB
- ## Linux does not store files byte by byte on disk. It stores data in blocks.
- ## 1 block = 4 KB

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

- In Linux, the command ./ is used to run a program (script or executable file) from the current directory.
- 🔹 What does ./ mean?
-  → represents the current directory
-  / → separates directories
-  So ./filename means:
-  👉 “Run the file named filename that is located in the current directory.”

- connect -
```
ssh bandit2@bandit.labs.overthewire.org -p 2220
```

 ## level-3
- username - bandit3
- How it come:
- bandit2@bandit:~$ ls
- --spaces in this filename--
- bandit2@bandit:~$ cat -- --spaces\ in\ this\ filename--
- MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
- password
   ```
   MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
   ```

 - connect -
```
ssh bandit3@bandit.labs.overthewire.org -p 2220
```
## Commands:
- The name of the file is ‘spaces in this filename’. When you try to cat out the filename as is, since there are spaces in the name of the file, the command assumes each word separated by space to be a separate file.
- ## why we use "--" this one for cat command,
- because.. cat -- --spaces\ in\ this\ filename--
- means:
- First -- → tells cat to stop parsing options
- Second part → actual filename

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




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

 <img width="1447" height="305" alt="image" src="https://github.com/user-attachments/assets/6e661437-b4ce-4077-a39c-b47a54a16ca9" />

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

  ## level-2
- username - bandit2
- password -
 ```
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```


## commands:
- the file name is- ‘ -’.
- "."=type in './-'

- In Linux, the command ./ is used to run a program (script or executable file) from the current directory.
- 🔹 What does ./ mean?
-  → represents the current directory
-  / → separates directories
-  So ./filename means:
-  👉 “Run the file named filename that is located in the current directory.” 



  <img width="382" height="96" alt="image" src="https://github.com/user-attachments/assets/d12bf6c9-80c8-49ec-ada1-37a568ae3aee" />




- connect -
```
ssh bandit2@bandit.labs.overthewire.org -p 2220
```

 ## level-3
- username - bandit 3
- password
   ```
   MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
   ```

<img width="772" height="157" alt="image" src="https://github.com/user-attachments/assets/bd7b9179-82a9-451a-858f-77f3e11b786b" />

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

  ## commands:
- ls
- cd inhere/
- ls
- ls -al
- cat ...hidden-for-you

  <img width="947" height="346" alt="image" src="https://github.com/user-attachments/assets/a9b14cbf-e52f-47fa-a8ca-1574b45ad13d" />


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
- file identifies the type/content of a file (text file, binary file, directory, etc.).
./* means "all files and folders in the current directory", so the command checks every item in the
- cat ./-file07


  <img width="977" height="800" alt="image" src="https://github.com/user-attachments/assets/a52c142c-b6db-452c-bd34-eecaf1c07eaf" />




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
   - - connect -
```
ssh bandit6@bandit.labs.overthewire.org -p 2220
```

## commnds:
- ls
- cd inhere/
- ls
- find . -size 1033c
- cat ./maybehere07/.file2

<img width="1052" height="297" alt="image" src="https://github.com/user-attachments/assets/392d4e8e-75ca-4e52-95ab-9705b85fe44c" />




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

  - - connect -
```
ssh bandit7@bandit.labs.overthewire.org -p 2220
```
## Commands: Type one by one
- find / -user bandit7 -group bandit6 -size 33c (find / → Search the entire filesystem starting from the root (/).
-user bandit7 -group bandit6 -size 33c → Show only files owned by user bandit7, belonging to group bandit6, and having an exact size of 33 bytes (c = bytes).)

- cat /var/lib/dpkg/info/bandit7.password
 - ssh bandit7@localhost


 <img width="462" height="561" alt="image" src="https://github.com/user-attachments/assets/fe8baa9f-d477-4fbe-b66d-e1059a57dfe5" />
 
 <img width="761" height="485" alt="image" src="https://github.com/user-attachments/assets/228c6bde-0f85-46d7-ae12-cb0729052b5a" />


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

   - - connect -
```
ssh bandit8@bandit.labs.overthewire.org -p 2220
```


## Commands:
- ls
- cat data.txt | grep millionth (grep millionth → Searches the displayed text and shows only the line(s) containing the word "millionth".)

- ssh bandit8@localhost


<img width="455" height="172" alt="image" src="https://github.com/user-attachments/assets/3cbccda7-3765-4b7c-a712-c6fe9a513abd" />


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

  - - connect -
```
ssh bandit9@bandit.labs.overthewire.org -p 2220
```

## Commands:

- cat data.txt | sort | uniq -u

  <img width="430" height="122" alt="image" src="https://github.com/user-attachments/assets/181517e6-a48b-4662-a66e-d8cdbe66f575" />

## explanation:
- sort → Arranges all lines in alphabetical order.
- uniq -u → Shows only the lines that appear exactly once (removes duplicates).

- ssh bandit9@localhost

  ## level-10
- username - bandit10
- password
   ```
   FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
   ```

  - - connect -
```
ssh bandit10@bandit.labs.overthewire.org -p 2220
```

## Commands:
ls
strings data.txt | grep =
ssh bandit10@localhost

## explaination:
- strings data.txt → Extracts and displays readable text from a file (useful for binary files).
- grep = → Searches for and shows only the lines containing the = character.

- In one sentence: This command extracts readable text from data.txt and displays only the lines that contain an = sign.


<img width="437" height="237" alt="image" src="https://github.com/user-attachments/assets/4528a48f-eec7-457d-beb6-f3249f845b2c" />



- ssh bandit10@localhost

  ## level-11
- username - bandit8 
- password
   ```
   dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
   ```
## Commands:
-ls
- cat data.txt | base64 --decode

## explanation:
- cat data.txt → Reads and displays the contents of data.txt.
- base64 --decode → Decodes the Base64-encoded text back into its original readable form.
- In one sentence: This command reads Base64-encoded data from data.txt and converts it back to the
  <img width="457" height="120" alt="image" src="https://github.com/user-attachments/assets/838e8052-47d6-411a-b047-db451c6487a6" />

  
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

  ## explanantion:
- cat data.txt → Reads and outputs the contents of data.txt.
- tr (translate) → Replaces characters from the first set (a-zA-Z) with the corresponding characters in the second set (n-za-mN-ZA-M).
- This performs ROT13 encoding/decoding, shifting each letter by 13 positions (A↔N, B↔O, a↔n, b↔o).
  
- ssh bandit12@localhost

  <img width="581" height="97" alt="image" src="https://github.com/user-attachments/assets/67e244d8-df9d-48db-9c8f-17741eeca638" />

- - connect -
```
ssh bandit12@bandit.labs.overthewire.org -p 2220
```
  - ## OR:

- And we can password in another way also like fist type :
- ls
- cat data.txt
- after that comes like thiss = Gur cnffjbeq vf 7k16JArUVv5LxVuJfsSVdbbtaHGlw9D4
  
- copy this one and open cyberchef.io after paste in that input space next in search bar   search in Rot13 then your password is shown in output...😉

  
  ## level-13
- username - bandit13
- password
   ```
   FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
   ```
## Commands:
## commands with clear explanation::

- You’re working on Level 12 → 13 of OverTheWire Bandit — this level is about repeatedly decoding and extracting compressed files hidden inside other files.

- I’ll explain each command, what it does, why you used it, and where it’s used in real life — in very simple lines.

- 1️⃣ ls

- What it does: Lists files in the current folder.
- Why here: To see what files are present.
- Where used: Anytime you want to check folder contents.

- 2️⃣ mkdir /tmp/jithu

- What it does: Creates a new directory (folder).
- Why here: /tmp is writable. Bandit home folders often have restrictions.
- Where used: When you need a new workspace folder.

- 3️⃣ cp data.txt /tmp/jithu

- What it does: Copies a file.
- Why here: To work safely on a copy of the original file.
- Where used: Backup files before editing or testing.

- 4️⃣ cd /tmp/jithu

- What it does: Changes directory.
- Why here: To move into your working folder.
- Where used: Navigating between folders.

- 5️⃣ file data.txt

- What it does: Tells you the file type.
- Why here: To check what kind of data is inside.
- Where used: When you don’t know a file’s format.

- 6️⃣ xxd -r data.txt > data

- What it does:

- xxd = hex dump tool

-  -r = reverse (convert hex back to binary)

- Why here: The file was hex-encoded. You converted it back to binary.
- Where used: When dealing with encoded or raw binary data.

- 7️⃣ mv data data2.gz

- What it does: Renames or moves a file.
- Why here: After checking file type, you rename it with correct extension (.gz).
- Where used: Renaming files properly before extracting.

- 8️⃣ gzip -d data2.gz

- What it does: Decompresses gzip file.
- Why here: File was gzip compressed.
- Where used: Extract .gz files.

- 9️⃣ bzip2 -d data3.bz

- What it does: Decompresses bzip2 file.
- Why here: File was bzip2 compressed.
- Where used: Extract .bz2 files.

- 🔟 tar -xf data5.tar

- What it does: Extracts tar archive.
-  -x = extract
- -f = file
- Why here: File was a tar archive.
- Where used: Extract .tar files.

- 1️⃣1️⃣ Repeating Pattern

- You kept doing:

- file → check type

- mv → rename correctly
- decompress (gzip -d or bzip2 -d)
- if tar → tar -xf
- Because the file was compressed multiple times inside each other.
- This level teaches:

- Always check file type before extracting.

- 1️⃣2️⃣ cat data9

- What it does: Displays file content.
- Why here: Final file was ASCII text (the password).
- Where used: Viewing small text files.

- 🔁 What Actually Happened
- The file was:
- Hex → Gzip → Bzip2 → Gzip → Tar → Tar → Bzip2 → Tar → Gzip → Text
- You carefully unpacked each layer.



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

- <img width="595" height="502" alt="image" src="https://github.com/user-attachments/assets/94df8ea0-bdcb-4bb7-8417-eb27af4e9cf3" />

- after exit that ssh level and type like this

-   <img width="712" height="697" alt="image" src="https://github.com/user-attachments/assets/ee3f9179-8d07-4098-907d-572d0547a755" />

- <img width="640" height="646" alt="image" src="https://github.com/user-attachments/assets/5d8245e8-8b31-47f4-b3ef-e28fe9cdbc52" />

- after this you directlly login in bandit 14 here you get the password....

-   <img width="502" height="70" alt="image" src="https://github.com/user-attachments/assets/e0e85d7b-0cc2-4cc5-aec3-8135ffe4e8fb" />


- - connect -
```
ssh bandit14@bandit.labs.overthewire.org -p 2220
```

-  ## level-15
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

<img width="592" height="117" alt="image" src="https://github.com/user-attachments/assets/6bb3de3c-3438-4710-922e-c767bc05ff76" />


- or type like this:
- bandit14@bandit:~$ cat /etc/bandit_pass/bandit14 | nc localhost 30000

- explain:   cat – Reads the content of a file and prints it to the terminal (standard output).
- /etc/bandit_pass/bandit14 – The file path that contains the password for Bandit level 14.
- | (pipe) – Sends the output of the first command (cat) as input to the next command.
- nc – Runs Netcat, a tool used to send or receive data over network connections.
- localhost – Refers to the current machine (IP address 127.0.0.1).
- 30000 – The port number where a service is running and waiting to receive the password.
  
- Correct!
- 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo


-  ## level-16
- username - bandit16
- password
   ```
   kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
   ```
#Commands:
-  echo "8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo"
-   echo "8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo" | openssl s_client -connect localhost:30001 -ign_eof

-  echo "..." → Prints the password/text and sends it to the next command through the pipe (|).
- openssl s_client → Creates an SSL/TLS client connection to communicate securely with a server.
- -connect localhost:30001 → Connects to port 30001 on the local machine (localhost).
- -ign_eof → Keeps the connection open even after echo finishes sending the text.

Purpose: Sends the password securely to the SSL service running on localhost:30001 and waits for the server's response (such as the next Bandit password).
- - connect -
```
ssh bandit16@bandit.labs.overthewire.org -p 2220
```
<img width="987" height="742" alt="image" src="https://github.com/user-attachments/assets/4ee076aa-358c-4e16-839d-a9f9413b78b8" />


  ## level-17
- username - bandit1
- password
   ```
   EReVavePLFHtFlFsjn3hyzMlvSuSAcRD

   ```
#Commands:
- The Corrected Command Sequence
- Here is your updated sequence. Run these while logged into bandit16:

- Step 1: Get the Key

- Connect to the SSL port:
- "openssl s_client -connect localhost:31790 -quiet"

- Paste the bandit16 password and press Enter.

- Carefully copy the entire RSA private key output, from -----BEGIN RSA PRIVATE KEY----- all the way down to -----END RSA PRIVATE KEY-----.

- Step 2: Save the Key in a Writable Directory

- idi vere terminal lo cheye( after do it in another terminal)

- Create your own temporary folder:
 - "mkdir /tmp/bhanu_workspace"
- Move into that folder:
- "cd /tmp/bhanu_workspace"

- Create the key file:
- "nano bandit17.key"
- Paste the RSA key, save (Ctrl+O, Enter), and exit (Ctrl+X).

- Step 3: Secure the Key and Log In
Lock down the permissions so SSH accepts it:
- "chmod 600 bandit17.key"

- Log in to bandit17 from your current session (using localhost is easiest since you are already inside the Bandit network):
- "ssh -i bandit17.key bandit17@bandit.labs.overthewire.org -p 2220"

- after login to bandit 17 to type this command get level 17 password:
- "cat /etc/bandit_pass/bandit17" 
- - connect -
```
ssh bandit17@bandit.labs.overthewire.org -p 2220
```
<img width="761" height="705" alt="image" src="https://github.com/user-attachments/assets/10d74b6f-e7db-487b-a7bf-7731fb867222" />

<img width="1196" height="737" alt="image" src="https://github.com/user-attachments/assets/84ab3539-bb0e-4eda-bcb3-b6b274da912d" />

<img width="687" height="347" alt="image" src="https://github.com/user-attachments/assets/ea65282f-ca8b-4d16-bc46-385730f39d27" />


  ## level-18
- username - bandit1
- password
   ```
   x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO
   ```
#Commands:
- diff passwords.old passwords.new
- "diff = finds and displays differences between two files or directories."
- - connect -
```
ssh bandit18@bandit.labs.overthewire.org -p 2220
```

<img width="605" height="316" alt="image" src="https://github.com/user-attachments/assets/b470c610-f63e-4781-a90e-421b7dc2b3a0" />


  ## level-19
- username - bandit1
- password
   ```
   cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8
   ```
#Commands:
-  ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme
-  after this lits comes like this:"bandit18@bandit.labs.overthewire.org's password: " in this type level 18 password after that u got level 19 password
- - connect -
```
ssh bandit19@bandit.labs.overthewire.org -p 2220
```


<img width="842" height="722" alt="image" src="https://github.com/user-attachments/assets/c0d46ffb-2e02-45fc-9432-839938462b25" />

<img width="871" height="646" alt="image" src="https://github.com/user-attachments/assets/0f486e1e-1bb2-4a9c-b3b6-a835ddd075f3" />


 ## level-20
- username - bandit1
- password
   ```
   0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO
   ```
#Commands:here the commands line by line
- bandit19@bandit:~$ ls
- bandit20-do
- bandit19@bandit:~$ file bandit20-do
- bandit20-do: setuid ELF 32-bit LSB executable, Intel 80386, version 1 (SYSV), dynamically linked, interpreter /lib/ld-linux.so.2, - BuildID[sha1]=38f1351d0068ccbbace0e437f34859de85e63025, for GNU/Linux 3.2.0, not stripped
- "bandit19@bandit:~$ ./bandit20-do cat /etc/bandit_pass/bandit20"
- 0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO


- "./bandit20-do"

- "./ means run a program from the current directory."
- "bandit20-do is a special executable file provided in this level."
- "It runs commands with the permissions of user bandit20."
- - connect -
```
ssh bandit20@bandit.labs.overthewire.org -p 2220
```
<img width="597" height="167" alt="image" src="https://github.com/user-attachments/assets/e790791f-e6ca-42d0-9ba4-34a1bb3ebbbf" />

  ## level-21
- username - bandit21
- password
   ```
   EeoULMCra2q0dSkYj561DX7s1CpBuOBt
   ```
#Commands:
- ls
- ./suconnect
- "echo "pervious level password type here" | nc -l -p 4545 &"
- "./suconnect 4545"



- echo: Prints the text (your password) so it can be sent to the next command.

- nc (netcat): A networking tool used to send or receive data across network connections.

- "-l: Tells netcat to listen for an incoming connection rather than starting one.

- "-p: Specifies the port number (like 4545) to use for the connection.

- "&: Runs the command in the background so you can keep using the terminal.

- "./: Tells Linux to look for and run a file in your current directory.

- suconnect: The specific "SetUID" program that checks your password and gives the flag.



<img width="1377" height="296" alt="image" src="https://github.com/user-attachments/assets/f2e0eb38-e65a-495c-a502-570b3abf0c3c" />


- - connect -
```
ssh bandit21@bandit.labs.overthewire.org -p 2220
```


  ## level-22
- username - bandit22
- password
   ```
   tRae0UfB9v0UzbCdn9cY0gQnds9GF58Q
   ```
#Commands:
- bandit21@bandit:~$ ls /etc/cron.d/
- behemoth4_cleanup  cronjob_bandit22  cronjob_bandit24  leviathan5_cleanup    otw-tmp-dir
- clean_tmp          cronjob_bandit23  e2scrub_all       manpage3_resetpw_job  sysstat
- bandit21@bandit:~$ cat /etc/cron.d/cronjob_bandit22
- @reboot bandit22 /usr/bin/cronjob_bandit22.sh &> /dev/null
- * * * * * bandit22 /usr/bin/cronjob_bandit22.sh &> /dev/null
- bandit21@bandit:~$ cat /usr/bin/cronjob_bandit22.sh
- #!/bin/bash
- chmod 644 /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
- cat /etc/bandit_pass/bandit22 > /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
- bandit21@bandit:~$ cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
- "tRae0UfB9v0UzbCdn9cY0gQnds9GF58Q"

<img width="1352" height="216" alt="image" src="https://github.com/user-attachments/assets/efcbd1b0-5780-48e8-8a1e-c4d01dd67666" />


- explain:
- cron: A service that runs commands automatically at set times.
- cron.d/: The folder holding the schedules for these tasks.
- /etc/: Folder for system configuration files.
- /usr/bin/: Folder where executable scripts are kept.
- .sh: A Shell Script file (a list of commands).
- /tmp/: A folder for temporary files.

- - connect -
```
ssh bandit22@bandit.labs.overthewire.org -p 2220
```


-  ##level-23
- username - bandit23
- password
   ```
   0Zf11ioIjMVN551jX3CmStKLYqjk54Ga
   ```
#Commands:
- "bandit22@bandit:~$ cd /etc/cron.d"
- "bandit22@bandit:/etc/cron.d$ ls"
- behemoth4_cleanup  cronjob_bandit22  cronjob_bandit24  leviathan5_cleanup    otw-tmp-dir
- clean_tmp          cronjob_bandit23  e2scrub_all       manpage3_resetpw_job  sysstat
- "bandit22@bandit:/etc/cron.d$ cat cronjob_bandit23"
- @reboot bandit23 /usr/bin/cronjob_bandit23.sh  &> /dev/null
- * * * * * bandit23 /usr/bin/cronjob_bandit23.sh  &> /dev/null
- "bandit22@bandit:/etc/cron.d$ cat /usr/bin/cronjob_bandit23.sh"
- #!/bin/bash
- myname=$(whoami)
- mytarget=$(echo I am user $myname | md5sum | cut -d ' ' -f 1)
- echo "Copying passwordfile /etc/bandit_pass/$myname to /tmp/$mytarget"

- cat /etc/bandit_pass/$myname > /tmp/$mytarget
- "bandit22@bandit:/etc/cron.d$ mytarget=$(echo I am user bandit23 | md5sum | cut -d ' ' -f 1)"
- "bandit22@bandit:/etc/cron.d$ cat /tmp/$mytarget"
- 0Zf11ioIjMVN551jX3CmStKLYqjk54Ga


<img width="1311" height="337" alt="image" src="https://github.com/user-attachments/assets/00bc1908-4e70-4564-a155-29ab89263427" />
 ## explain:
- cron
- Cron is a Linux service that automatically runs commands or scripts at scheduled times (every minute, hour, day, etc.).
- cron.d → A directory where scheduled cron jobs are stored; files inside it tell the system what commands to run and when.
- cronjob_bandit23 → A specific cron job file that contains the schedule and command executed automatically for the bandit23 user.

  
- - connect -
```
ssh bandit23@bandit.labs.overthewire.org -p 2220
```



  ## level-24
- username - bandit24
- password
   ```
   gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8
   ```
#Commands:
- bandit23@bandit:~$ ls
- bandit23@bandit:~$ cd /etc/cron.d/
- bandit23@bandit:/etc/cron.d$ ls
- bandit23@bandit:/etc/cron.d$ cat cronjob_bandit24
- bandit23@bandit:/etc/cron.d$ cat /usr/bin/cronjob_bandit24.sh
- bandit23@bandit:/etc/cron.d$ cd /var/spool/bandit24
- bandit23@bandit:/var/spool/bandit24$ ls
- foo
- bandit23@bandit:/var/spool/bandit24$ cd /var/spool/bandit24/foo
- bandit23@bandit:/var/spool/bandit24/foo$ echo "cat /etc/bandit_pass/bandit24 > /tmp/certa_test" > certa6.sh
- bandit23@bandit:/var/spool/bandit24/foo$ chmod 777 certa6.sh
- bandit23@bandit:/var/spool/bandit24/foo$ ls certa6.sh
- ls: cannot access 'certa6.sh': No such file or directory
- bandit23@bandit:/var/spool/bandit24/foo$ ls
- ls: cannot open directory '.': Permission denied
- bandit23@bandit:/var/spool/bandit24/foo$ cat /tmp/certa_test
- gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8

<img width="1356" height="762" alt="image" src="https://github.com/user-attachments/assets/4e2712da-477b-480f-9a7e-13070aa202c5" />


- - connect -
```
ssh bandit24@bandit.labs.overthewire.org -p 2220
```



 ## level-25
- username - bandit25
- password
   ```
   iCi86ttT4KSNe1armKiwbQNmB3YJP3q4
   ```
#Commands:
- bandit24@bandit:~$ cd !$
- cd /tmp/inigo24
- bandit24@bandit:/tmp/inigo24$ for i in {0000..5000};do echo gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8 $i>>list1;done
- bandit24@bandit:/tmp/inigo24$ for i in {5001..9999};do echo gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8 $i>>list2;done
- bandit24@bandit:/tmp/inigo24$ cat list1 | nc localhost 30002 | uniq
- I am the pincode checker for user bandit25. Please enter the password for user bandit24 and the secret pincode on a single line, separated by a space.
- Wrong! Please enter the correct current password and pincode. Try again.
- ^C
- bandit24@bandit:/tmp/inigo24$ cat list2 | nc localhost 30002 | uniq
- I am the pincode checker for user bandit25. Please enter the password for user bandit24 and the secret pincode on a single line, separated by a space.
- Wrong! Please enter the correct current password and pincode. Try again.
- Correct!
- The password of user bandit25 is iCi86ttT4KSNe1armKiwbQNmB3YJP3q4

<img width="952" height="292" alt="image" src="https://github.com/user-attachments/assets/be488d44-37d1-4bf0-8c54-d7c096f3e6f7" />


- "!"— In shells like Bash, it’s used for history expansion (recalling previous commands).
- "$" — Represents a variable prefix (e.g., $HOME) or the shell prompt symbol for a normal user.

- - connect -
```
ssh bandit25@bandit.labs.overthewire.org -p 2220
```



  ## level-26
- username - bandit26
- password
   ```
   s0773xxkk0MXfdqOfPRVr9L3jJBUOgCZ
   ```
#Commands:
- 🔹 1. Login to bandit25
- ssh bandit25@bandit.labs.overthewire.org -p 2220
- 🔹 2. Check files
- ls
- 🔹 3. Show SSH key
- cat bandit26.sshkey
  
- 👉 Copy the full key (BEGIN → END)

- 🔹 4. Exit to Kali
- exit
- 🔹 5. Create key file in Kali
- nano bandit26.sshkey

- 👉 Paste key → Save

- 🔹 6. Set permission
- chmod 600 bandit26.sshkey
- 🔹 7. Make terminal SMALL
- stty rows 5 cols 40f
- 🔹 8. Connect using key
- ssh -i bandit26.sshkey bandit26@bandit.labs.overthewire.org -p 2220

- Don't type a command immediately.

- For Bandit 26, the trick is:

- Make your terminal window very small (reduce its height).
- Connect again with the SSH command.
- When the text opens in more, press:
  
- 🔹 9. When screen pauses → press
- v
- 🔹 10. Inside vi
- :set shell=/bin/bash
- :shell
- 🔹 11. Get password
- cat /etc/bandit_pass/bandit26
  - connect -
```
ssh bandit26@bandit.labs.overthewire.org -p 2220
```
<img width="885" height="780" alt="image" src="https://github.com/user-attachments/assets/b73adc48-3e31-4911-911f-162518135969" />

<img width="687" height="166" alt="image" src="https://github.com/user-attachments/assets/ed225a4e-041d-4464-b8b2-83ee32dae8c7" />

<img width="682" height="142" alt="image" src="https://github.com/user-attachments/assets/0e6f5acc-2cc2-4cfc-bacb-e914d64ce00a" />

  ## level-27
- username - bandit27
- password
   ```
   upsNCc7vzaRDx6oZC6GiR6ERwe1MowGB
   ```
#Commands:
- You already did:

- bandit26@bandit:~$ cat /etc/bandit_pass/bandit26

- 👉 That part is DONE (you already know that password)

- 🎯 NOW do this (next steps)
- 🔹 1. Check files
- ls

- 👉 You should see:

- bandit27-do
- 🔹 2. Use that file
- ./bandit27-do ls
- 🔹 3. Get next password
- ./bandit27-do cat /etc/bandit_pass/bandit27
- 🎉 That output = password for bandit27
- 🔹 4. Exit
- exit
- 🔹 5. Login to next level

- From Kali:

- ssh bandit27@bandit.labs.overthewire.org -p 2220

- 👉 Paste the password you just got
- - connect -
```
ssh bandit27@bandit.labs.overthewire.org -p 2220
```


  ## level-28
- username - bandit28
- password
   ```
   Yz9IpL0sBcCeuG7m9uQFt8ZNpS4HZRcN
   ```
# Commands:
- Open your Kali terminal (do not log into bandit27 for this).

- Go to a temporary working directory by typing:

- cd /tmp

- Create a new random folder:

- mktemp -d

- Enter that folder using:

- cd <folder-name>
- Clone the Git repository using:
- git clone ssh://bandit27-git@bandit.labs.overthewire.org:2220/home/bandit27-git/repo
- When it asks for a password, enter the bandit27 password.

- After cloning is complete, go into the repository:

- cd repo

- List the files:

- ls

- Open the README file:

- cat README
- The text inside this file is the password for bandit28.


<img width="882" height="732" alt="image" src="https://github.com/user-attachments/assets/dd914958-cf1b-4a09-8100-9be364ab74ff" />

- - connect -
```
ssh bandit28@bandit.labs.overthewire.org -p 2220
```


  ## level-29
- username - bandit29
- password
   ```
   4pT1t5DENaYuqnqvadYs1oE4QLCdjmJ7
   ```
#Commands:
- 🔹 1. Open Kali terminal

- 👉 Do NOT use bandit server

- 🔹 2. Go to temporary directory
- cd /tmp

- 👉 This is a safe place to work

- 🔹 3. Create a random folder
- mktemp -d

- 👉 Creates a unique folder like:

- /tmp/tmp.XYZ123
- 🔹 4. Enter the folder
- cd /tmp/tmp.XYZ123

- 👉 OR shortcut:

- cd $(mktemp -d)
- 🔹 5. Clone the Git repository
- git clone ssh://bandit28-git@bandit.labs.overthewire.org:2220/home/bandit28-git/repo

- 👉 Enter password: bandit28 password

- 🧠 Meaning:
- git clone = download repository from server
- 🔹 6. Go inside repository
- cd repo
- 🔹 7. Read the file
- cat README.md

- 👉 Output:
- password: xxxxxxxx (hidden)
 - ❌ Not useful

- 🔹 8. Check Git history
- git log
- 🧠 Meaning:
- Shows all previous versions (commits)
- 🔹 9. Select an older commit

- Example:

- d0cf2ab7dd7ebc6075b59102a980155268f0fe8f

- 👉 (the one before “fix info leak”)

- 🔹 10. View old version of file
- git show d0cf2ab7dd7ebc6075b59102a980155268f0fe8f
- 🧠 Meaning:
- Shows how file looked in past
- 🎉 Result

- 👉 You will see:

- password: xxxxxxxxx

- ✔ This is bandit29 password

- 🔹 11. Login to next level
- ssh bandit29@bandit.labs.overthewire.org -p 2220

<img width="817" height="712" alt="image" src="https://github.com/user-attachments/assets/79c987c3-4250-4aa7-b5e6-41264be1f008" />

<img width="1025" height="812" alt="image" src="https://github.com/user-attachments/assets/7e1aff07-8818-4e67-b29b-46cd04ff78fe" />



- Command	Meaning
- mktemp -d	= create safe folder
- git clone =	download repo
- git log =	show history
- git show =	show old version
- cat = 	read file
- - connect -
```
ssh bandit29@bandit.labs.overthewire.org -p 2220
```


  ## level-30
- username - bandit30
- password
   ```
   qp30ex3VLz5MDG1n91YowTv4Q8l7CDZL
   ```
#Commands:
- 🔹 1.
- cd /tmp
- 👉 Moves to temporary directory (safe place to work)

- 🔹 2.
- cd $(mktemp -d)
- 👉 Creates a random folder and enters it (private workspace)

- 🔹 3.
- git clone ssh://bandit29-git@bandit.labs.overthewire.org:2220/home/bandit29-git/repo
- 👉 Downloads the repository from server
- 👉 Enter bandit29 password

- 🔹 4.
- cd repo
- 👉 Moves inside downloaded project folder

- 🔹 5.
- cat README.md
- 👉 Reads file → password is hidden ❌

- 🔹 6.
- git branch -a
- 👉 Shows all branches (different versions of project)

- 🔹 7.
- git checkout dev
- 👉 Switches to dev branch (another version)

- 🔹 8.
- cat README.md
- 👉 Reads file again → password is visible ✅

- 🔹 9.
- ssh bandit30@bandit.labs.overthewire.org -p 2220
- 👉 Login to next level using found password

  <img width="772" height="700" alt="image" src="https://github.com/user-attachments/assets/4b821b9d-52d3-479c-ba60-f00b1b2f6f4b" />

<img width="882" height="702" alt="image" src="https://github.com/user-attachments/assets/8f31d0d9-4316-45cf-98bf-8e7bb201f459" />


<img width="731" height="671" alt="image" src="https://github.com/user-attachments/assets/34fc4786-1c30-417f-9499-ac4eb3983ca3" />



- - connect -
```
ssh bandit30@bandit.labs.overthewire.org -p 2220
```

 ## level-31
- username - bandit31
- password
   ```
   fb5S2xb7bRyFmAvQYQGEqsbhVyJqhnDy
   ```
#Commands:
- 1.
- cd /tmp

- 👉 Go to temporary directory (safe place)

- 🔹 2.
- cd $(mktemp -d)

- 👉 Create and enter a random folder

- 🔹 3.
- git clone ssh://bandit30-git@bandit.labs.overthewire.org:2220/home/bandit30-git/repo

- 👉 Clone repository
- 👉 Enter bandit30 password

- 🔹 4.
- cd repo

- 👉 Enter project folder

- 🔹 5.
- ls

- 👉 Check files (nothing useful ❌)

 -🔹 6.
- git tag

- 👉 Show tags (special hidden versions)

- 🔹 7.

- 👉 You will see: secret
- 🔹 8.
- git show secret
- 👉 Show hidden content inside tag


<img width="997" height="760" alt="image" src="https://github.com/user-attachments/assets/c58be003-a475-464b-8072-50134d49f16b" />


- - connect -
```
ssh bandit31@bandit.labs.overthewire.org -p 2220
```

## here both level passwords are there they are connected
 ## level-32 & 33
- username - bandit32 & 33
- password 32
   ```
   3O9RfhqyAlVBEZpVb6LYStshZoqoSx5K
   ```
   
   -  password 33
   ```
   tQdtbs5D5i2vJwkO8mEyYEyTL8izoeJ0
   ```
#Commands:
- 📘 Bandit 31 → 32 (How to find password)
- 🔹 1.
- cd /tmp

- 👉 Move to temporary directory (safe workspace)

- 🔹 2.
- cd $(mktemp -d)

- 👉 Create and enter random folder

- 🔹 3.
- git clone ssh://bandit31-git@bandit.labs.overthewire.org:2220/home/bandit31-git/repo

- 👉 Download repository
- 👉 Enter bandit31 password

- 🔹 4.
- cd repo

- 👉 Enter project folder

- 🔹 5.
- cat README.md

- 👉 Shows instruction:
- 👉 create file with text “May I come in?”

- 🔹 6.
- echo "May I come in?" > key.txt

- 👉 Create file with required content

- 🔹 7.
- git add -f key.txt

- 👉 Force add file (because .gitignore blocks .txt files)

- 🔹 8.
- git commit -m "add key"

- 👉 Save changes in git

- 🔹 9.
- git push origin master

- 👉 Upload file to server
- 👉 Enter bandit31 password

- 🎉 Result

- 👉 You get:

- 3O9RfhqyAlVBEZpVb6LYStshZoqoSx5K

- ✔ This is bandit32 password

- 📘 Bandit 32 → 33 (Next level)
- 🔹 10.
- ssh bandit32@bandit.labs.overthewire.org -p 2220

- 👉 Login using bandit32 password

- 🔹 11.
 -WELCOME TO THE UPPERCASE SHELL
- >>

 - 👉 Commands become uppercase ❌

- 🔹 12.
- $0

- 👉 Open normal shell (bypass uppercase)

- 🔹 13.
- cat /etc/bandit_pass/bandit33

- 👉 Read next password

- 🎉 Result
- tQdtbs5D5i2vJwkO8mEyYEyTL8izoeJ0

- ✔ This is bandit33 password

- 📘 Bandit 33 (Final)
- 🔹 14.
- ssh bandit33@bandit.labs.overthewire.org -p 2220

- 👉 Login to final level

- 🔹 15.

- 👉 Enter password:

- tQdtbs5D5i2vJwkO8mEyYEyTL8izoeJ0
- 🎉 Output

- 👉 You finished Bandit 🎯


<img width="906" height="736" alt="image" src="https://github.com/user-attachments/assets/3804c3d2-e025-41ec-9895-727a15091195" />


<img width="946" height="737" alt="image" src="https://github.com/user-attachments/assets/2d2f64e8-43d7-4da6-a914-987963a9d621" />

<img width="886" height="731" alt="image" src="https://github.com/user-attachments/assets/5f443570-ad49-49fa-94e1-363e09b23106" />

<img width="896" height="782" alt="image" src="https://github.com/user-attachments/assets/845f4b5b-066d-4b2b-b159-d14e719cd4dc" />


<img width="897" height="537" alt="image" src="https://github.com/user-attachments/assets/04d95718-a07b-46f2-9f99-e1315a4c8b3a" />


- 🧠 Final Summary
- Level 31 → push file → get password
- Level 32 → bypass shell → get password
- Level 33 → final login

  
- - connect -
```
ssh bandit33@bandit.labs.overthewire.org -p 2220
```

<img width="700" height="312" alt="image" src="https://github.com/user-attachments/assets/9ed33630-b671-4cf7-9682-3b8b00abb3a7" />


<img width="751" height="195" alt="image" src="https://github.com/user-attachments/assets/b999f934-fea4-49f1-b470-cc3d448400ce" /> 

  
- - connect -
```
ssh bandit1@bandit.labs.overthewire.org -p 2220
```


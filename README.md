# OphCrack

Ophcrack is a free GUI based Windows password cracker based on rainbow tables. That works on linux and windows.

### What can it do?

1. Using downloadable wordlists it can:
2. Crack LM (LAN manager) and NTLM (New Technology LAN Manager) hashes.
3. Brute force simple passwords
4. export CSV's
and more...


This is a tool that NCL likes to use and give challenges on, mainly in the password cracking section. I know crazy that they use something other than md5.

## How to install

Here is Ophcrack's official download link for windows
[Here](https://ophcrack.sourceforge.io/download.php?type=ophcrack)


### For linux
install how you would a normal application. 
```
sudo apt install ophcrack
```
run with
```
ophcrack
```
Ophcracks GUI should appear.

![image](https://github.com/JoshuaHartz/Intro-To-Ophcrack/assets/102620766/9bb11370-817b-4087-8e95-2d8085d96010)


## How to use.

Most likely you will be given hashes, they will look somewhat like.
```
c23a90751cdd619b6cea564742e1e4bf33006ba41:cb8086049ec4736c
```
Note the semicolon in the middle of the hash. Its a dead giveaway.

Now whats a hash cracking program good for if we dont have rainbowtables/wordlists. Luckily ophcrack provides a metric TON of rainbow tables that you can use. In short a rainbow table is a set of reversed hashes used to crack other hashes.

Due to limitations to storage size I cant upload the rainbow tables but I can however tell you how to craft them.

You will want these as the bare minimum:
1. tables_vista_free
2. tables_xp_free_fast
3. tables_xp_free_small
4. Vistal Special
5. XP special

You can find everything [here](https://sourceforge.net/projects/ophcrack/files/tables/)

For some, you will have to download the contents one by one and put them into a folder manually. It will take some time but its worth. 

Then once your folder is built and has all of its tables you can upload them by clicking the tables tab in ophcrack. 





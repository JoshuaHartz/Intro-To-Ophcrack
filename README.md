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

They have a section on source forge with all the tables for you but some of them arent fully downlaodable and you kinda have to build them yourself, but luckily I had nothing better to do and I made them for you, which I will attach here to this repo. 







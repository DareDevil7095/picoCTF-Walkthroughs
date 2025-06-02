# Big Zip - picoGym Exclusive

- [CTF Details](#ctf-details)
- [Solution](#solution)
- [References](#references)

## CTF Details
![Image Alt](https://github.com/DareDevil7095/picoCTF-Walkthroughs/blob/main/General_Skills/picoGym_Exclusive/Screenshots/Big_Zip_CTF.png?raw=true)
Challenge link: [https://play.picoctf.org/practice/challenge/322](https://play.picoctf.org/practice/challenge/322)

## Solution

- Copy the <b>"Download zip file"</b> link and go to the Linux terminal where we can download the zip file using the <b>"wget"</b> command.

<b>Command to download zip file:</b>

```
wget https://artifacts.picoctf.net/c/503/big-zip-files.zip
```
<b>Note:</b> <i>This copied link might change with time, so do not copy it from this walkthrough.</i>

![alt text](Big_Zip_wget.png)

After downloading the zip file, we can list the files in our directory using the <b>ls</b> command to make sure it is there...

- Next, we need to extract the files to find the flag. To do that we can use the <b>unzip</b> command.

<b>Command to unzip the <i>big-zip-files</i> file:</b>
```
unzip big-zip-files.zip 
```

# Shell command

사용자의 명령(ex. pwd)을 해석하여 대신 실행해주는 프로그램

---
#### pwd
- used to show present working directory. 
```
($ pwd)
```
#### cd
- change directory

#### ls 
- list files and directories
- used to list the contents of directory.

```
# List the files in the working directory
$ ls 
$ ls / bin
$ ls -l 
$ ls -l / etc / bin
$ ls -la ..
```
#### Manipulation
1. cp : copy files and directories
```
$ cp A B
$ cp -i A B
$ cp A dir1
$ cp -R dir1 dir2
```
2. mv : move files and directories or rename them
```
$ file1 file2
$ -i file1 file2
$ file1 file2 dir1
$ dir1 dir2
```
3. rm : delete files and directories
```
rm file1 file2
rm -i file1 file2
rm -r dir1 dir2
```
4. mkdir : make a new directory

5. Wildcard
: Searching filenames like MS Excel


#### Tip
Autocompletion ==> Press **tap** key

Using past command ==> Press **up arrow** key
Cleaning all commands ==> typing **clear**
Help commend ==> typing **$ help cd** or **$ man cp**
Exiting terminal ==> typing **$ exit**

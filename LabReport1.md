# Lab Report 1
## Name: Daniel J. Groten > PID: A17704281
### 1) Command with no arguments.
Terminal:
`danie@Suzuki MINGW64 ~/Downloads/cse11-pa8-starter-main/lecture1 (main)
$ cd messages

danie@Suzuki MINGW64 ~/Downloads/cse11-pa8-starter-main/lecture1 (main)
$ ls messages
Hello.class  Hello.java  messages/  README

danie@Suzuki MINGW64 ~/Downloads/cse11-pa8-starter-main/lecture1 (main)
$ cat messages
 `
Absolute Path:
`/Downloads/cse11-pa8-starter-main/lecture1` (same absolute path for all three commands)
Explanations:
For `cd`, I received no output because the command is not supposed to yield any output. It is only supposed to change the directory of the terminal which is what it did. Since I gave it no specific directory, it would automatically assume I desired the default directory of my computer. This is not an error.
For `ls`, I received the output of all the files and folders in the current directory. This is not an error.
For `cat`, it appeared that the terminal became stuck, not outputting anything but refusing to allow me to input something else. I believe this is because the command needs a specific file to read, but since I didn't pass it one it became stuck. This is an error because it freezes the terminal.
### 2) Command with a directory as an argument.
Terminal:
`danie@Suzuki MINGW64 ~/Downloads/cse11-pa8-starter-main/lecture1 (main)
$ cd messages

danie@Suzuki MINGW64 ~/Downloads/cse11-pa8-starter-main/lecture1 (main)
$ ls messages
en-us.txt  es-mx.txt  zh-cn.txt

danie@Suzuki MINGW64 ~/Downloads/cse11-pa8-starter-main/lecture1 (main)
$ cat messages
cat: messages: Is a directory`
Absolute Path:
`/Downloads/cse11-pa8-starter-main/lecture1` (same absolute path for all three commands)
Explanations:
For `cd`, I received no output because the command is not supposed to yield any output. It is only supposed to change the directory of the terminal which is what it did. Since I gave it the directory of `messages`, it changed the directory to `/Downloads/cse11-pa8-starter-main/lecture1/messages`. This is not an error.
For `ls`, I received the output of all the files and folders in the directory `messages`. This is not an error.
For `cat`, I received the output saying that `messages` is a directory. This is because `cat` needs a specific file to read, it does not take a directory. While this is not the way this method is supposed to be used, this is not an error as the creators have predicted people may accidentally use a directory instead of a file and created a message for that situation.
### 3) Command with a file as an argument.
Terminal:
`danie@Suzuki MINGW64 ~/Downloads/cse11-pa8-starter-main/lecture1 (main)
$ cd README
bash: cd: README: Not a directory
danie@Suzuki MINGW64 ~/Downloads/cse11-pa8-starter-main/lecture1 (main)
$ ls README
README

danie@Suzuki MINGW64 ~/Downloads/cse11-pa8-starter-main/lecture1 (main)
$ cat README
To use this program:

javac Hello.java
java Hello messages/en-us.txt`
Absolute Path:
`/Downloads/cse11-pa8-starter-main/lecture1` (same absolute path for all three commands)
Explanations:
For `cd`, I received the output saying that `messages` is a directory. This is because `cat` needs a specific file to read, it does not take a directory. While this is not the way this method is supposed to be used, this is not an error as the creators have predicted people may accidentally use a directory instead of a file and created a message for that situation.
For `ls`, I received the name of the file. This is not an error.
For `cat`, I received the contents of the file. This is working exactly as intended as `cat` is supposed to read the contents of the file it is given. This is not an error.

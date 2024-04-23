# Lab Report 1
## Name: Daniel J. Groten | PID: A17704281
### 1) Command with no arguments.
**Terminal:**

Command: `$ cd`

Output: (no output)

Command: `$ ls`

Output: `Hello.class  Hello.java  messages/  README`

Command: `$ cat`

Output: (no output, frozen terminal)

**Absolute Path:**

`~/Downloads/cse11-pa8-starter-main/lecture1` (same absolute path for all three commands)





**Explanations:**

For `cd`, I received no output because the command is not supposed to yield any output. It is only supposed to change the directory of the terminal which is what it did. Since I gave it no specific directory, it would automatically assume I desired the home directory. This is not an error.

For `ls`, I received the output of all the files and folders in the current directory. This is not an error.

For `cat`, it appeared that the terminal became frozen, not outputting anything but refusing to allow me to input something else. I believe this is because the `cat` command caused the terminal to become stuck in an infinite loop. This is not an error.

### 2) Command with a directory as an argument.

**Terminal:**

Command: `$ cd messages`

Output: (no output)

Command: `$ ls messages`

Output: `en-us.txt  es-mx.txt  zh-cn.txt`

Command: `$ cat messages`

Output: `cat: messages: Is a directory`

**Absolute Path:**

`~/Downloads/cse11-pa8-starter-main/lecture1` (same absolute path for all three commands)

**Explanations:**

For `cd`, I received no output because the command is not supposed to yield any output. It is only supposed to change the directory of the terminal which is what it did. Since I gave it the directory of `messages`, it changed the directory to `~/Downloads/cse11-pa8-starter-main/lecture1/messages`. This is not an error.

For `ls`, I received the output of all the files and folders in the directory `messages`. This is not an error.

For `cat`, I received the output saying that `messages` is a directory. This is because `cat` needs a specific file to read, it does not take a directory. While this is not the way this method is supposed to be used, this is not an error as the creators have predicted people may accidentally use a directory instead of a file and created a message for that situation.

### 3) Command with a file as an argument.

**Terminal:**

Command: `$ cd README`

Output: `bash: cd: README: Not a directory`

Command: `$ ls README`

Output: `README`

Command: `$ cat README`

Output: 
```
To use this program:

javac Hello.java
java Hello messages/en-us.txt
```

**Absolute Path:**

`~/Downloads/cse11-pa8-starter-main/lecture1` (same absolute path for all three commands)

**Explanations:**

For `cd`, I received the output saying that `messages` is a directory. This is because `cat` needs a specific file to read, it does not take a directory. While this is not the way this method is supposed to be used, this is not an error as the creators have predicted people may accidentally use a directory instead of a file and created a message for that situation.

For `ls`, I received the name of the file. This is not an error.

For `cat`, I received the contents of the file. This is working exactly as intended as `cat` is supposed to read the contents of the file it is given. This is not an error.

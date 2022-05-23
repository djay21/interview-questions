##### Basic:


1. ###### What is Linux?

**Answer:** Linux is an operating system based on UNIX and was first introduced by Linus Torvalds. It is based on the Linux Kernel and can run on different hardware platforms manufactured by Intel, MIPS, HP, IBM, SPARC, and Motorola. Another popular element in Linux is its mascot, a penguin figure named Tux.

2.###### What is the difference between UNIX and LINUX?

**Answer:** Unix originally began as a propriety operating system from Bell Laboratories, which later on spawned into different commercial versions. On the other hand, Linux is free, open source and intended as a non-propriety operating system for the masses.

3) What is BASH?
BASH is short for Bourne Again SHell. It was written by Steve Bourne as a replacement to the original Bourne Shell (represented by /bin/sh). It combines all the features from the original version of Bourne Shell, plus additional functions to make it easier and more convenient to use. It has since been adapted as the default shell for most systems running Linux.

4) What is Linux Kernel?

The Linux Kernel is a low-level systems software whose main role is to manage hardware resources for the user. It is also used to provide an interface for user-level interaction.

5) What is LILO?

LILO is a boot loader for Linux. It is used mainly to load the Linux operating system into main memory so that it can begin its operations.

6) What is a swap space?

Swap space is a certain amount of space used by Linux to temporarily hold some programs that are running concurrently. This happens when RAM does not have enough memory to hold all programs that are executing.

7) What is the advantage of open source?

Open source allows you to distribute your software, including source codes freely to anyone who is interested. People would then be able to add features and even debug and correct errors that are in the source code. They can even make it run better and then redistribute these enhanced source code freely again. This eventually benefits everyone in the community.

8 ) What are the basic components of Linux?

Just like any other typical operating system, Linux has all of these components: kernel, shells and GUIs, system utilities, and an application program. What makes Linux advantageous over other operating system is that every aspect comes with additional features and all codes for these are downloadable for free.

9) Does it help for a Linux system to have multiple desktop environments installed?

In general, one desktop environment, like KDE or Gnome, is good enough to operate without issues. It’s all a matter of preference for the user, although the system allows switching from one environment to another. Some programs will work in one environment and not work on the other, so it could also be considered a factor in selecting which environment to use.

10) What is the basic difference between BASH and DOS?

The key differences between the BASH and DOS console lie in 3 areas:

– BASH commands are case sensitive while DOS commands are not;

– Under BASH, / character is a directory separator and \ acts as an escape character. Under DOS, / serves as a command argument delimiter and \ is the directory separator

– DOS follows a convention in naming files, which is 8 character file name followed by a dot and 3 characters for the extension. BASH follows no such convention.

11) What is the importance of the GNU project?

This so-called Free software movement allows several advantages, such as the freedom to run programs for any purpose and freedom to study and modify a program to your needs. It also allows you to redistribute copies of software to other people, as well as the freedom to improve software and have it released for the public.


12) Describe the root account.
The root account is like a systems administrator account and allows you full control of the system. Here you can create and maintain user accounts, assigning different permissions for each account. It is the default account every time you install Linux.

13) What is CLI?

CLI is short for Command Line Interface. This interface allows the user to type declarative commands to instruct the computer to perform operations. CLI offers greater flexibility. However, other users who are already accustomed to using GUI find it difficult to remember commands including attributes that come with it.

14) What is GUI?

GUI, or Graphical User Interface, make use of images and icons that users click and manipulate as a way of communicating with the computer. Instead of having to remember and type commands, the use of graphical elements makes it easier to interact with the system, as well as adding more attraction through images, icons, and colors.

15) How do you open a command prompt when issuing a command?

To open the default shell (which is where the command prompt can be found), press Ctrl-Alt-F1. This will provide a command line interface (CLI) from which you can run commands as needed.

16) How can you find out how much memory Linux is using?

From a command shell, use the “concatenate” command: cat /proc/meminfo for memory usage information. You should see a line starting something like Mem: 64655360, etc. This is the total memory Linux thinks it has available to use.

You can also use commands

free - m

vmstat

top

htop
to find current memory usage

17) What is a typical size for a swap partition under a Linux system?

The preferred size for a swap partition is twice the amount of physical memory available on the system. If this is not possible, then the minimum size should be the same as the amount of memory installed.

18) What are symbolic links?

Symbolic links act similarly to shortcuts in Windows. Such links point to programs, files or directories. It also allows you instant access to it without having to go directly to the entire pathname.

19) Does the Ctrl+Alt+Del key combination work on Linux?

Yes, it does. Just like Windows, you can use this key combination to perform a system restart. One difference is that you won’t be getting any confirmation message and therefore, a reboot is immediate.

20) How do you refer to the parallel port where devices such as printers are connected?

Whereas under Windows you refer to the parallel port as the LPT port, under Linux you refer to it as /dev/lp . LPT1, LPT2 and LPT3 would therefore be referred to as /dev/lp0, /dev/lp1, or /dev/lp2 under Linux.

21) Are drives such as hard drive and floppy drives represented with drive letters?

No. In Linux, each drive and device have different designations. For example, floppy drives are referred to as /dev/fd0 and /dev/fd1. IDE/EIDE hard drives are referred to as /dev/hda, /dev/hdb, /dev/hdc, and so forth.


22) How do you change permissions under Linux?
Assuming you are the system administrator or the owner of a file or directory, you can grant permission using the chmod command. Use + symbol to add permission or – symbol to deny permission, along with any of the following letters: u (user), g (group), o (others), a (all), r (read), w (write) and x (execute). For example, the command chmod go+rw FILE1.TXT grants read and write access to the file FILE1.TXT, which is assigned to groups and others.

23) In Linux, what names are assigned to the different serial ports?

Serial ports are identified as /dev/ttyS0 to /dev/ttyS7. These are the equivalent names of COM1 to COM8 in Windows.

24) How do you access partitions under Linux?

Linux assigns numbers at the end of the drive identifier. For example, if the first IDE hard drive had three primary partitions, they would be named/numbered, /dev/hda1, /dev/hda2 and /dev/hda3.

25) What are hard links?

Hard links point directly to the physical file on disk, and not on the pathname. This means that if you rename or move the original file, the link will not break since the link is for the file itself, not the path where the file is located.

26) What is the maximum length for a filename under Linux?

Any filename can have a maximum of 255 characters. This limit does not include the path name, so therefore the entire pathname and filename could well exceed 255 characters.

27)What are filenames that are preceded by a dot?

In general, filenames that are preceded by a dot are hidden files. These files can be configuration files that hold important data or setup info. Setting these files as hidden makes it less likely to be accidentally deleted.


28) Explain virtual desktop.
This serves as an alternative to minimizing and maximizing different windows on the current desktop. Using virtual desktops can clear the desktop when you can open one or more programs. Rather than minimizing/restoring all those programs as needed, you can simply shuffle between virtual desktops with programs intact in each one.

29) How do you share a program across different virtual desktops under Linux?

To share a program across different virtual desktops, in the upper left-hand corner of a program window look for an icon that looks like a pushpin. Pressing this button will “pin” that application in place, making it appear in all virtual desktops, in the same position onscreen.

30) What does a nameless (empty) directory represent?

This empty directory name serves as the nameless base of the Linux file system. This serves as an attachment for all other directories, files, drives, and devices.

31) What is the pwd command?

The pwd command is short for print working directory command.

Example:

pwd
Output:

/home/guru99/myDir
32) What are daemons?

Daemons are services that provide several functions that may not be available under the base operating system. Its main task is to listen for service request and at the same time to act on these requests. After the service is done, it is then disconnected and waits for further requests.

33) How do you switch from one desktop environment to another, such as switching from KDE to Gnome?

Assuming you have these two environments installed, just log out from the graphical interface. Then at the login screen, type your login ID and password and choose which session type you wish to load. This choice will remain your default until you change it to something else.

34) What are the kinds of permissions under Linux?

There are 3 kinds of permissions under Linux:- Read: users may read the files or list the directory- Write: users may write to the file of new files to the directory- Execute: users may run the file or lookup a specific file within a directory

35) How does case sensitivity affect the way you use commands?

When we talk about case sensitivity, commands are considered identical only if every character is encoded as is, including lowercase and uppercase letters. This means that CD, cd, and Cd are three different commands. Entering a command using uppercase letters, where it should be in lowercase, will produce different outputs.

36) What are environmental variables?

Environmental variables are global settings that control the shell’s function as well as that of other Linux programs. Another common term for environmental variables is global shell variables.

37) What are the different modes when using vi editor?

There are 3 modes under vi:- Command mode – this is the mode where you start in- Edit mode – this is the mode that allows you to do text editing- Ex mode – this is the mode wherein you interact with vi with instructions to process a file

38) Is it possible to use shortcuts for a long pathname?

Yes, there is. A feature known as filename expansion allows you do this using the TAB key. For example, if you have a path named /home/iceman/assignments directory, you would type as follows: /ho[tab]/ice[tab]/assi[tab] . This, however, assumes that the path is unique and that the shell you’re using supports this feature.

39) What is redirection?
Redirection is the process of directing data from one output to another. It can also be used to direct an output as an input to another process.

40) What is grep command?

grep a search command that makes use of pattern-based searching. It makes use of options and parameters that are specified along with the command line and applies this pattern in searching the required file output.

41) What could be the problem when a command that was issued gave a different result from the last time it was used?

One highly possible reason for getting different results from what seems to be the same command has something to do with case sensitivity issues. Since Linux is case sensitive, a command that was previously used might have been entered in a different format from the present one. For example, to lists all files in the directory, you should type the command ls, and not LS. Typing LS will either result in an error message if there is no program by that exact name exist or may produce a different output if there is a program named LS that performs another function.

42) What are the contents of /usr/local?

It contains locally installed files. This directory matters in environments where files are stored on the network. Specifically, locally-installed files go to /usr/local/bin, /usr/local/lib, etc.). Another application of this directory is that it is used for software packages installed from source, or software not officially shipped with the distribution.

43) How do you terminate an ongoing process?

Every process in the system is identified by a unique process id or pid. Use the kill command followed by the pid to terminate that process. To terminate all process at once, use kill 0.

44) How do you insert comments in the command line prompt?

Comments are created by typing the # symbol before the actual comment text. This tells the shell to completely ignore what follows. For example “# This is just a comment that the shell will ignore.”

45) What is command grouping and how does it work?

You can use parentheses to group commands. For example, if you want to send the current date and time along with the contents of a file named OUTPUT to a second file named MYDATES, you can apply command grouping as follows: (date cat OUTPUT) > MYDATES

46) How do you execute more than one command or program from a single command line entry?

You can combine several commands by separating each command or program using a semicolon symbol. For example, you can issue such a series of commands in a single entry:

ls –l cd .. ls –a MYWORK which is equivalent to 3 commands: ls -l cd.. ls -a MYWORK
**Note that this will be executed one after the other, in the order specified.

47) Write a command that will look for files with an extension “c”, and has the occurrence of the string “apple” in it.

Answer:

 Find ./ -name "*.c" | xargs grep –i "apple"
48) Write a command that will display all .txt files, including its individual permission.

Answer:

ls -al *.txt
49) Write a command that will do the following:

-look for all files in the current and subsequent directories with an extension c,v
-strip the,v from the result (you can use sed command)
-use the result and use a grep command to search for all occurrences of the word ORANGE in the files.

Find ./ -name "*.c,v" | sed 's/,v//g' | xargs grep "ORANGE"
50) What, if anything, is wrong with each of the following commands?

a) ls -l-s
b) cat file1, file2
c) ls – s Factdir

Answers:
a) there should be space between the 2 options: ls -l -s
b) do not use commas to separate arguments: cat file1 file2
c) there should be no space between hyphen and option label: ls –s Factdir

51) What is the command to calculate the size of a folder?

To calculate the size of a folder uses the command du –sh folder1.

52) How can you find the status of a process?

Use the command

ps ux

53) How can you check the memory status?

You can use the command

free -m to display output in MB

free -g to display output in GB

54) Explain how to color the Git console?

To color the Git console, you can use the command git config—global color.ui auto. In the command, the color.ui variable sets the default value for a variable such as color.diff and color.grep.

55) How can you append one file to another in Linux?

To append one file to another in Linux you can use command cat file2 >> file 1. The operator >> appends the output of the named file or creates the file if it is not created. While another command cat file 1 file 2 > file 3 appends two or more files to one.

56) Explain how you can find a file using Terminal?

To find a file you have to use a command, find . –name “process.txt” . It will look for the current directory for a file called process.txt.

57) Explain how you can create a folder using Terminal?

To create a folder, you have to use command mkdir. It will be something like these: ~$ mkdir Guru99

58) Explain how you can view the text file using Terminal?

To view the text file, go to the specific folder where the text files are located by using the command cd and then type less filename.txt.

59) Explain how to enable curl on Ubuntu LAMP stack?

To enable curl on Ubuntu, first, install libcurl, once done use following command sudo/etc/init .d /apache2 restart or sudo service apache2 restart.

60) Explain how to enable root logging in Ubuntu?

The command which enables root logging is

#sudo sh-c ‘echo “greater-show-manual-login=true” >>/etc/lightdm/lightdm.conf’

61) How can you run a Linux program in the background simultaneously when you start your Linux Server?

By using nohup. It will stop the process receiving the NOHUP signal and thus terminating it you log out of the program which was invoked with. & runs the process in the background.


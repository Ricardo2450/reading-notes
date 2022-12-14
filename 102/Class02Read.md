# **The Coder's Computer**

There are many different text editors for one to use to code like text edit, notepad, atom, visual code, etc. Each has their pro's and con's. Some my come with code completion or syntax highlighting. While others may be bare but can be upgraded by adding from the many extensions available. The most important part is picking the "best" one all depends on your personal choice. Each person is different so what you may find helpful, someone else see's it as a horrible option. So just pick what feeling right for you and that will get the job done.

>_cheat sheet_

-To open the terminal in mac, just go to Applications than to Utilities. You can also search up terminal in spotlight.

-When you enter commands, they are actually stored in a history. You can traverse this history using the up and down arrow keys.

-pwd (Print Working Directory)- tells you what your current or present working directory is.

-LS (short for list)- will just do a plain listing of our current location.

-Square brackets ( [ ] )- mean that those items are optional, we may run the command with or without them.

-There are 2 types of paths we can use, **absolute** and **relative**.
  
* **Absolute** paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )
  
* **Relative** paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.

\- (Tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents

\- . (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).

\- .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

\- cd (stands for change directory)- If you run the command cd without any arguments then it will always take you back to your home directory.

\- file -
obtain information about what type of file a file or directory is.

\- ls -a List the contents of a directory, including hidden files.

\- Everything is a file under Linux
Even directories.

\- Linux is an extensionless system
Files can have any extension they like or none at all.

\- Linux is case sensitive
Beware of silly typos.

>## Links to more info about

* [The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)
* [Basic Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php)
* [About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

[Return to home page](../README.md)
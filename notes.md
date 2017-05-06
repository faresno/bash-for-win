# Helpful notes for using Bash for Windows

## File System Sharing:

[As of 11/17/2016](https://blogs.msdn.microsoft.com/commandline/2016/11/17/do-not-change-linux-files-using-windows-apps-and-tools/) do NOT use windows apps to modify Linux files.  You can use Linux apps to modify windows files.

* Windows location of Linux File System:
  ```$env:localappdata\lxss```

* Accesing windows file system from within bash:
  * ```ls /mnt/c/```  lists contenst of root folder in the C: drive 

## Refernces

* [WSL](https://msdn.microsoft.com/en-us/commandline/wsl/faq)


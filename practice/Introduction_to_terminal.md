The terminal, also known as the command-line interface (CLI), is a text-based interface in which you can interact with your computer's operating system using commands. It provides a way to execute various commands and perform tasks without relying on a graphical user interface (GUI).

The terminal is a powerful tool that allows you to perform a wide range of tasks efficiently, such as:

    1. Navigation: yu can navigate inside the file system, you can move between directories, list directory contents, create and delete files and directories, and manage file permissions.

    2. Running programs: You can execute programs and scripts, launch applications, and manage running processes.

    3. Text manipulation: You can create, view and edit text files, concatenate and filter text, search for patterns using regular expressions, and redirect input and output.

    4. System management: You can manage system services, install and update software packages, configure system settings, and monitor system resources.

    Navigation:
        to change directory: 
          cd practice_directory
        list files and directories: 
          ls Documents
        navigate to other directories: 
	  cd Documents
        create a directory: 
 	  mkdir cool_project1
        remove a file: 
 	  rm filetoremove.txt
        remove a directory: 
	  rmdir cool_project1

    File Operations:
        create a new file: 
	  touch newfile.txt
        view file contents: 
          cat myfile.txt
        copy a file: 
	  cp myfile.txt de backup.txt
        move or rename a file: 
	  mv myfile.txt newmyfile.txt

    System Information:
        display system information: 
	  uname -a.
        view disk usage: 
	  df -h.
        show current date and time: 
	  date

    Process Management:
        list running processes: 
	  ps aux
        Terminate a process: 
	  kill 1234
        Background a process: 
	  sleep 10 & echo "hello world"
.

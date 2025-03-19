

# Introduction - Day 1

Welcome to the #90DaysOfDevOps Challenge with the #TrainWithShubham Community! Today, we begin our journey into the world of DevOps. Here’s what you need to do:

1. **Fork this Repository:**
   - Go to the repository on GitHub and fork it to your own account. This will allow you to track your progress and contribute.

2. **Start with a DevOps Roadmap:**
   - Watch the introductory video on DevOps: [DevOps Roadmap](https://youtu.be/g_QHuGq3E2Y?si=fR9K56-JevZTfrBK)

3. **Write a LinkedIn Post or a Small Article:**
   - Share your understanding of DevOps based on the video and your research. Cover the following points:

     - **What is DevOps:**
       
       
     - **What is Automation, Scaling, and Infrastructure:**
       
       
     - **Why DevOps is Important:**
       
       

4. **Engage with the Community:**
   - Share your LinkedIn post or article link in the community forum or on social media using the hashtags #90DaysOfDevOps and #TrainWithShubham.
   - Read and comment on posts from other participants to foster a collaborative learning environment.


# Day 2 Basic Linux 

## Basic linux commands

### Listing commands
```ls option_flag arguments ```--> list the sub directories and files avaiable in the present directory

Examples:

- ``` ls -l ```--> list the files and directories in long list format with extra information
- ```ls -a ```--> list all including hidden files and directory
- ```ls *.sh``` --> list all the files having .sh extension.

- ```ls -i ``` --> list the files and directories with index numbers inodes
- ``` ls -d */``` --> list only directories.(we can also specify a pattern)

### Directoy commands
- ```pwd``` --> print work directory. Gives the present working directory.

- ```cd path_to_directory``` --> change directory to the provided path

- ```cd ~ ``` or just  ```cd ``` --> change directory to the home directory

- ``` cd - ``` --> Go to the last working directory.

- ``` cd ..``` --> change directory to one step back.

- ``` cd ../..``` --> Change directory to 2 levels back.

- ``` mkdir  directoryName``` --> to make a directory in a specific location

Examples:
```
mkdir newFolder              # make a new folder 'newFolder'

mkdir .NewFolder              # make a hidden directory (also . before a file to make it hidden)

mkdir A B C D                  #make multiple directories at the same time

mkdir /home/user/Mydirectory   # make a new folder in a specific location

mkdir -p  A/B/C/D              # make a nested directory
```



# Day 3 Task: Basic Linux Commands with a Twist

Task: What are the Linux commands to

1. View the content of a file and display line numbers.
2. Change the access permissions of files to make them readable, writable, and executable by the owner only.
3. Check the last 10 commands you have run.
4. Remove a directory and all its contents.
5. Create a `fruits.txt` file, add content (one fruit per line), and display the content.
6. Add content in `devops.txt` (one in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava. Then, append "Pineapple" to the end of the file.
7. Show the first three fruits from the file in reverse order.
8. Show the bottom three fruits from the file, and then sort them alphabetically.
9. Create another file `Colors.txt`, add content (one color per line), and display the content.
10. Add content in `Colors.txt` (one in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey. Then, prepend "Yellow" to the beginning of the file.
11. Find and display the lines that are common between `fruits.txt` and `Colors.txt`.
12. Count the number of lines, words, and characters in both `fruits.txt` and `Colors.txt`.

Reference: [Linux Commands for DevOps Used Day-to-Day](https://www.linkedin.com/pulse/linux-commands-devops-used-day-to-day-activit-chetan-/)

[← Previous Day](../day02/README.md) | [Next Day →](../day04/README.md)




# Basic Linux Commands - Day 3

Task 1: View the content of a file and display line numbers.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%201.png)

Task 2: Change the access permissions of files to make them readable, writable, and executable by the owner only.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%202.png)

Task 3: Check the last 10 commands you have run.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%203.png)

Task 4: Remove a directory and all its contents.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%204.png)

Task 5: Create a `fruits.txt` file, add content (one fruit per line), and display the content.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%205.png)

Task 6: Add content in `devops.txt` (one in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava. Then, append "Pineapple" to the end of the file.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%206.png)
![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%2066.png)

Task 7: Show the first three fruits from the file in reverse order.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%207.png)

Task 8: Show the bottom three fruits from the file, and then sort them alphabetically.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%208.png)

Task 9: Create another file `Colors.txt`, add content (one color per line), and display the content.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%209.png)

Task 10: Add content in `Colors.txt` (one in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey. Then, prepend "Yellow" to the beginning of the file.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%2010.png)

Task 11: Find and display the lines that are common between `fruits.txt` and `Colors.txt`.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%2011.png)

Task 12: Count the number of lines, words, and characters in both `fruits.txt` and `Colors.txt`.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day03/image/task%2012.png)



# Day 4 Task: Basic Linux Shell Scripting for DevOps Engineers

## What is Kernel?

The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system.

## What is Shell?

A shell is a special user program that provides an interface for users to interact with operating system services. It accepts human-readable commands from users and converts them into instructions that the kernel can understand. The shell is a command language interpreter that executes commands read from input devices such as keyboards or from files. It starts when the user logs in or opens a terminal.

## What is Linux Shell Scripting?

Linux shell scripting involves writing programs (scripts) that can be run by a Linux shell, such as bash (Bourne Again Shell). These scripts automate tasks, perform system administration tasks, and facilitate the interaction between users and the operating system.

**Tasks:**

- Explain in your own words and with examples what Shell Scripting means for DevOps.
- What is `#!/bin/bash`? Can we write `#!/bin/sh` as well?
- Write a Shell Script that prints `I will complete #90DaysOfDevOps challenge`.
- Write a Shell Script that takes user input, input from arguments, and prints the variables.
- Provide an example of an If-Else statement in Shell Scripting by comparing two numbers.

**Were the tasks challenging?**

These tasks are designed to introduce you to basic concepts of Linux shell scripting for DevOps. Share your experience and solutions on LinkedIn and let me know how it went! :)

**Article Reference:** [Click here to read basic Linux Shell Scripting](https://devopscube.com/linux-shell-scripting-for-devops/)

**YouTube Video:** [EASIEST Shell Scripting Tutorial for DevOps Engineers](https://www.youtube.com/watch?v=_-D6gkRj7xc&list=PLlfy9GnSVerQr-Se9JRE_tZJk3OUoHCkh&index=3)

[← Previous Day](../day03/README.md) | [Next Day →](../day05/README.md)




# Day 4 Answers: Basic Linux Shell Scripting for DevOps Engineers

Task 1: Explain in your own words and with examples what Shell Scripting means for DevOps.
- 'Shell Scripting is writing a series of commands in a script file to automate tasks in the Unix/Linux shell. For DevOps, shell scripting is crucial for automating repetitive tasks, managing system configurations, deploying applications, and integrating various tools and processes in a CI/CD pipeline. It enhances efficiency, reduces errors, and saves time.'

Example: Automating server setup
![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day04/image/task%201.png)
![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day04/image/task%2011.png)

Task 2: What is `#!/bin/bash`? Can we write `#!/bin/sh` as well?
- `#!/bin/bash` is called a "shebang" line. It indicates that the script should be run using the Bash shell.
  - `#!/bin/bash`: Uses Bash as the interpreter. It supports advanced features like arrays, associative arrays, and functions.
  - `#!/bin/sh`: Uses the Bourne shell. It’s more POSIX-compliant and is generally compatible with different Unix shells.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day04/image/task%202.png)

Task 3: Write a Shell Script that prints `I will complete #90DaysOfDevOps challenge`.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day04/image/task%203.png)

Task 4: Write a Shell Script that takes user input, input from arguments, and prints the variables.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day04/image/task%204.png)

Task 5: Provide an example of an If-Else statement in Shell Scripting by comparing two numbers.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day04/image/task%205.png)



# Day 5 Task: Advanced Linux Shell Scripting for DevOps Engineers with User Management

If you noticed that there are a total of 90 sub-directories in the directory '2023' of this repository, what did you think? How did I create 90 directories? Manually one by one, using a script, or a command?

All 90 directories were created within seconds using a simple command:

`mkdir day{1..90}`

### Tasks

1. **Create Directories Using Shell Script:**
   - Write a bash script `createDirectories.sh` that, when executed with three arguments (directory name, start number of directories, and end number of directories), creates a specified number of directories with a dynamic directory name.
   - Example 1: When executed as `./createDirectories.sh day 1 90`, it creates 90 directories as `day1 day2 day3 ... day90`.
   - Example 2: When executed as `./createDirectories.sh Movie 20 50`, it creates 31 directories as `Movie20 Movie21 Movie22 ... Movie50`.

   Notes: You may need to use loops or commands (or both), based on your preference. [Check out this reference: Bash Scripting For Loop](https://www.geeksforgeeks.org/bash-scripting-for-loop/)

2. **Create a Script to Backup All Your Work:**
   - Backups are an important part of a DevOps Engineer's day-to-day activities. The video in the references will help you understand how a DevOps Engineer takes backups (it can feel a bit difficult but keep trying, nothing is impossible).
   - Watch [this video](https://youtu.be/aolKiws4Joc) for guidance.

   In case of doubts, post them in the [Discord Channel for #90DaysOfDevOps](https://discord.gg/hs3Pmc5F).

3. **Read About Cron and Crontab to Automate the Backup Script:**
   - Cron is the system's main scheduler for running jobs or tasks unattended. A command called crontab allows the user to submit, edit, or delete entries to cron. A crontab file is a user file that holds the scheduling information.
   - Watch this video for reference: [Cron and Crontab](https://youtu.be/aolKiws4Joc).

4. **Read About User Management:**
   - A user is an entity in a Linux operating system that can manipulate files and perform several other operations. Each user is assigned an ID that is unique within the system. IDs 0 to 999 are assigned to system users, and local user IDs start from 1000 onwards.
   - Create 2 users and display their usernames.
   - [Check out this reference: User Management in Linux](https://www.geeksforgeeks.org/user-management-in-linux/).

5. **Post Your Progress:**
   - Post your daily work on LinkedIn and let me know how it went! Writing an article about your experience is highly encouraged.

**Were the tasks challenging?**

These tasks are designed to push your skills and introduce you to advanced concepts in Linux shell scripting and user management. Share your experience and solutions on LinkedIn and let me know how it went!

[← Previous Day](../day04/README.md) | [Next Day →](../day06/README.md)




# Day 5 Answers: Advanced Linux Shell Scripting for DevOps Engineers with User Management

### Tasks

1. **Create Directories Using Shell Script:**
   - Write a bash script `createDirectories.sh` that, when executed with three arguments (directory name, start number of directories, and end number of directories), creates a specified number of directories with a dynamic directory name.
   - Example 1: When executed as `./createDirectories.sh day 1 90`, it creates 90 directories as `day1 day2 day3 ... day90`.
   - Example 2: When executed as `./createDirectories.sh Movie 20 50`, it creates 31 directories as `Movie20 Movie21 Movie22 ... Movie50`.

   **Answer**
   
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day05/image/task%201.png)
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day05/image/task%201-2.png)
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day05/image/task%201-3.png)   

2. **Create a Script to Backup All Your Work:**
   - Backups are an important part of a DevOps Engineer's day-to-day activities. The video in the references will help you understand how a DevOps Engineer takes backups (it can feel a bit difficult but keep trying, nothing is impossible).

   **Answer**
   
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day05/image/task%202.png)
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day05/image/task%202-1.png)

3. **Read About Cron and Crontab to Automate the Backup Script:**
   - Cron is the system's main scheduler for running jobs or tasks unattended. A command called crontab allows the user to submit, edit, or delete entries to cron. A crontab file is a user file that holds the scheduling information.

   **Answer**
   
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day05/image/task%203.png)   
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day05/image/task%203-1.png) 

4. **Read About User Management:**
   - A user is an entity in a Linux operating system that can manipulate files and perform several other operations. Each user is assigned an ID that is unique within the system. IDs 0 to 999 are assigned to system users, and local user IDs start from 1000 onwards.
   - Create 2 users and display their usernames.

   **Answer**
   
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day05/image/task%204.png)

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/).



# Day 6 Task: File Permissions and Access Control Lists

### Today is more on Reading, Learning, and Implementing File Permissions

The concept of Linux file permission and ownership is important in Linux. Today, we will work on Linux permissions and ownership, and perform tasks related to both.

## Tasks

1. **Understanding File Permissions:**
   - Create a simple file and run `ls -ltr` to see the details of the files. [Refer to Notes](https://github.com/LondheShubham153/90DaysOfDevOps/tree/master/2023/day06/notes)
   - Each of the three permissions are assigned to three defined categories of users. The categories are:
     - **Owner:** The owner of the file or application.
       - Use `chown` to change the ownership permission of a file or directory.
     - **Group:** The group that owns the file or application.
       - Use `chgrp` to change the group permission of a file or directory.
     - **Others:** All users with access to the system (outside the users in a group).
       - Use `chmod` to change the other users' permissions of a file or directory.
   - Task: Change the user permissions of the file and note the changes after running `ls -ltr`.

2. **Writing an Article:**
   - Write an article about file permissions based on your understanding from the notes.

3. **Access Control Lists (ACL):**
   - Read about ACL and try out the commands `getfacl` and `setfacl`.
   - Task: Create a directory and set specific ACL permissions for different users and groups. Verify the permissions using `getfacl`.

4. **Additional Tasks:**
   - **Task:** Create a script that changes the permissions of multiple files in a directory based on user input.
   - **Task:** Write a script that sets ACL permissions for a user on a given file, based on user input.

5. **Understanding Sticky Bit, SUID, and SGID:**
   - Read about sticky bit, SUID, and SGID.
   - Task: Create examples demonstrating the use of sticky bit, SUID, and SGID, and explain their significance.

6. **Backup and Restore Permissions:**
   - Task: Create a script that backs up the current permissions of files in a directory to a file.
   - Task: Create another script that restores the permissions from the backup file.

In case of any doubts, post them on the [Discord Community](https://discord.gg/hs3Pmc5F).

**Happy Learning!**

[← Previous Day](../day05/README.md) | [Next Day →](../day07/README.md)



# Day 6 Answers: File Permissions and Access Control Lists

### Tasks

1. **Understanding File Permissions:**
   - Create a simple file and run `ls -ltr` to see the details of the files.
   - Each of the three permissions are assigned to three defined categories of users. The categories are:
     - **Owner:** The owner of the file or application.
       - Use `chown` to change the ownership permission of a file or directory.
     - **Group:** The group that owns the file or application.
       - Use `chgrp` to change the group permission of a file or directory.
     - **Others:** All users with access to the system (outside the users in a group).
       - Use `chmod` to change the other users' permissions of a file or directory.
   - Task: Change the user permissions of the file and note the changes after running `ls -ltr`.

   **Answer**
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day06/image/task1.png)

2. **Writing an Article:**
   - Write an article about file permissions based on your understanding from the notes.

   **Answer**

      - **Understanding File Permissions in Linux**
        - File permissions in Linux are critical for maintaining security and proper access control. They define who can read, write, and execute a file or directory. Here, we explore the concepts and commands related to file permissions.

      - **Basic Permissions**
        - Permissions in Linux are represented by a three-digit number, where each digit represents a different set of users: owner, group, and others.

        - **Highest Permission:** `7` (4+2+1)
        - **Maximum Permission:** `777`, but effectively `666` for files due to security reasons, meaning no user gets execute permission.
        - **Effective Permission for Directories:** `755`
        - **Lowest Permission:** `000` (not recommended)
        - **Minimum Effective Permission for Files:** `644` (default umask value of `022`)
        - **Default Directory Permission:** Includes execute permission for navigation

      - **Categories of Users**
        - Each of the three permissions are assigned to three defined categories of users:

        - **Owner**: The owner of the file or application.
          - Command: `chown` is used to change the ownership of a file or directory.
        - **Group**: The group that owns the file or application.
          - Command: `chgrp` is used to change the group permission of a file or directory.
        - **Others**: All users with access to the system.
          - Command: `chmod` is used to change the permissions for other users.

      - **Special Permissions**        
        - **SUID (Set User ID)**: If SUID is set on an executable file and a normal user executes it, the process will have the same rights as the owner of the file being executed instead of the normal user (e.g., `passwd` command).
        - **SGID (Set Group ID)**: If SGID is set on any directory, all subdirectories and files created inside will inherit the group ownership of the main directory, regardless of who creates them.
        - **Sticky Bit**: Used on folders to avoid deletion of a folder and its contents by other users though they have write permissions. Only the owner and root user can delete other users' data in the folder where the sticky bit is set.

3. **Access Control Lists (ACL):**
   - Read about ACL and try out the commands `getfacl` and `setfacl`.
   - Task: Create a directory and set specific ACL permissions for different users and groups. Verify the permissions using `getfacl`.

   **Answer**
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day06/image/task3.png)

4. **Additional Tasks:**
   - **Task:** Create a script that changes the permissions of multiple files in a directory based on user input.

   **Answer**
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day06/image/task4.png)

   - **Task:** Write a script that sets ACL permissions for a user on a given file, based on user input.

   **Answer**
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day06/image/task4-1.png)

5. **Understanding Sticky Bit, SUID, and SGID:**
   - Read about sticky bit, SUID, and SGID.
     - Sticky bit: Used on directories to prevent users from deleting files they do not own.
     - SUID (Set User ID): Allows users to run an executable with the permissions of the executable's owner.
     - SGID (Set Group ID): Allows users to run an executable with the permissions of the executable's group.
   - Task: Create examples demonstrating the use of sticky bit, SUID, and SGID, and explain their significance.

   **Answer**
     - Sticky bit:
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day06/image/task5.png)
     - SUID:
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day06/image/task5-1.png)
     - SGID:
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day06/image/task5-2.png)

6. **Backup and Restore Permissions:**
   - Task: Create a script that backs up the current permissions of files in a directory to a file.

   **Answer**
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day06/image/task6.png)

   - Task: Create another script that restores the permissions from the backup file.

   **Answer**
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day06/image/task6-1.png)



# Day 7 Task: Understanding Package Manager and Systemctl

### What is a Package Manager in Linux?

In simpler words, a package manager is a tool that allows users to install, remove, upgrade, configure, and manage software packages on an operating system. The package manager can be a graphical application like a software center or a command line tool like apt-get or pacman.

You’ll often find me using the term ‘package’ in tutorials and articles. To understand a package manager, you must understand what a package is.

### What is a Package?

A package is usually referred to as an application but it could be a GUI application, command line tool, or a software library (required by other software programs). A package is essentially an archive file containing the binary executable, configuration file, and sometimes information about the dependencies.

### Different Kinds of Package Managers

Package managers differ based on the packaging system but the same packaging system may have more than one package manager.

For example, RPM has Yum and DNF package managers. For DEB, you have apt-get, aptitude command line-based package managers.

## Tasks

1. **Install Docker and Jenkins:**
   - Install Docker and Jenkins on your system from your terminal using package managers.

2. **Write a Blog or Article:**
   - Write a small blog or article on how to install these tools using package managers on Ubuntu and CentOS.

### Systemctl and Systemd

Systemctl is used to examine and control the state of the “systemd” system and service manager. Systemd is a system and service manager for Unix-like operating systems (most distributions, but not all).

## Tasks

1. **Check Docker Service Status:**
   - Check the status of the Docker service on your system (ensure you have completed the installation tasks above).

2. **Manage Jenkins Service:**
   - Stop the Jenkins service and post before and after screenshots.

3. **Read About Systemctl vs. Service:**
   - Read about the differences between the `systemctl` and `service` commands.
   - Example: `systemctl status docker` vs. `service docker status`.

   For reference, read [this article](https://www.howtogeek.com/devops/how-to-check-if-the-docker-daemon-or-a-container-is-running/#:~:text=Checking%20With%20Systemctl&text=Check%20what%27s%20displayed%20under%20%E2%80%9CActive,running%20sudo%20systemctl%20start%20docker%20).

### Additional Tasks

4. **Automate Service Management:**
   - Write a script to automate the starting and stopping of Docker and Jenkins services.

5. **Enable and Disable Services:**
   - Use systemctl to enable Docker to start on boot and disable Jenkins from starting on boot.

6. **Analyze Logs:**
   - Use journalctl to analyze the logs of the Docker and Jenkins services. Post your findings.

#### Post about your progress and invite your friends to join the #90DaysOfDevOps challenge.

[← Previous Day](../day06/README.md) | [Next Day →](../day08/README.md)



# Day 7 Answers: Understanding Package Manager and Systemctl

## Tasks

1. **Install Docker and Jenkins:**
   - Install Docker and Jenkins on your system from your terminal using package managers.

   **Answer**
     - **First-Installing Docker**
       - Update the package list and install required packages:
         ```bash
            sudo apt update
            sudo apt install apt-transport-https ca-certificates curl software-properties-common 
       - Add Docker’s official GPG key:
         ```bash
            curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -          
       - Add the Docker APT repository:
         ```bash
            sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
       - Update the package list again:
         ```bash
            sudo apt update
       - Install Docker:
         ```bash
            sudo apt install docker-ce
       - Check Docker installation:
         ```bash
            sudo systemctl status docker

     - **Installing Jenkins**
       - Add the Jenkins repository key to the system:
         ```bash
            curl -fsSL https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
       - Add the Jenkins repository:
         ```bash
            sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
       - Update the package list:
         ```bash
            sudo apt update
       - Install Jenkins:
         ```bash
            sudo apt install jenkins
       - Start Jenkins:
         ```bash
            sudo systemctl start jenkins
       - Note:
         - First, check whether JAVA is installed or not.
           ```bash
              java -version
         - If you have not installed
           ```bash
              sudo apt install default-jre

   Output
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day07/image/task1.png)

   Output (Jenkins-UI)
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day07/image/task1-2.png)

2. **Write a Blog or Article:**
   - Write a small blog or article on how to install these tools using package managers on Ubuntu and CentOS.

   **Answer**
   1. Introduction:
      - Briefly introduce Docker and Jenkins.
      - Mention the operating systems (Ubuntu and CentOS) covered.
   2. Installing Docker on Ubuntu:
      - List the steps as detailed above.
   3. Installing Docker on CentOS:
      - Provide similar steps adjusted for CentOS.
   4. Installing Jenkins on Ubuntu:
      - List the steps as detailed above.
   5. Installing Jenkins on CentOS:
      - Provide similar steps adjusted for CentOS.

### Systemctl and Systemd

Systemctl is used to examine and control the state of the “systemd” system and service manager. Systemd is a system and service manager for Unix-like operating systems (most distributions, but not all).

## Tasks

1. **Check Docker Service Status:**
   - Check the status of the Docker service on your system (ensure you have completed the installation tasks above).

   **Answer**
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day07/image/task5.png)

2. **Manage Jenkins Service:**
   - Stop the Jenkins service and post before and after screenshots.

   **Answer**
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day07/image/taskj2.png)

3. **Read About Systemctl vs. Service:**
   - Read about the differences between the `systemctl` and `service` commands.
   - Example: `systemctl status docker` vs. `service docker status`.

   **Answer**
    - Understanding the `systemctl` and `service` Commands
      - Both `systemctl` and `service` commands are used to manage system services in Linux, but they differ in terms of usage, functionality, and the system architectures they support.
      - **`systemctl` Command**
        - `systemctl` is a command used to introspect and control the state of the `systemd` system and service manager. It is more modern and is used in systems that use `systemd` as their init system, which is common in many contemporary Linux distributions.
        - Examples:
          - Check the status of the Docker service:
            ```bash
               sudo systemctl status docker    
          - Start the Jenkins service:
            ```bash
               sudo systemctl start jenkins 
          - Stop the Docker service:
            ```bash
               sudo systemctl stop docker
          - Enable the Jenkins service to start at boot:
            ```bash
               sudo systemctl enable jenkins
             
      - **`service` Command**
        - 'service' is a command that works with the older 'init' systems (like SysVinit). It provides a way to start, stop, and check the status of services. While it is still available on systems using 'systemd' for backward compatibility, its usage is generally discouraged in favor of 'systemctl'.
        - Examples:
          - Check the status of the Docker service:
            ```bash
               sudo service docker status    
          - Start the Jenkins service:
            ```bash
               sudo service jenkins start
          - Stop the Docker service:
            ```bash
               sudo service docker stop

      - **Key Differences**
        - 1 System Architecture:
          - `systemctl` works with `systemd`.
          - `service` works with SysVinit and is compatible with `systemd` for backward compatibility.    
        - 2 Functionality:
          - `systemctl` offers more functionality and control over services, including management of the service's state (start, stop, restart, reload), enabling/disabling services at boot, and querying detailed service status.
          - `service` provides basic functionality for managing services, such as starting, stopping, and checking the status of services.
        - 3 Syntax and Usage:
          - `systemctl` uses a more unified syntax for managing services.
          - `service` has a simpler and more traditional syntax.

### Additional Tasks

4. **Automate Service Management:**
   - Write a script to automate the starting and stopping of Docker and Jenkins services.

   **Answer**
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day07/image/task4.png)

5. **Enable and Disable Services:**
   - Use systemctl to enable Docker to start on boot and disable Jenkins from starting on boot.

   **Answer**
    - Enable Docker to start on boot:
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day07/image/task5.png)

    - Disable Jenkins from starting on boot:
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day07/image/task5-1.png)

6. **Analyze Logs:**
   - Use journalctl to analyze the logs of the Docker and Jenkins services. Post your findings.

   **Answer**
    - Docker Logs:
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day07/image/task6.png)

    - Jenkins Logs:
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day07/image/task6-1.png)


# Day 8 Task: Shell Scripting Challenge

### Task 1: Comments
In bash scripts, comments are used to add explanatory notes or disable certain lines of code. Your task is to create a bash script with comments explaining what the script does.

### Task 2: Echo
The echo command is used to display messages on the terminal. Your task is to create a bash script that uses echo to print a message of your choice.

### Task 3: Variables
Variables in bash are used to store data and can be referenced by their name. Your task is to create a bash script that declares variables and assigns values to them.

### Task 4: Using Variables
Now that you have declared variables, let's use them to perform a simple task. Create a bash script that takes two variables (numbers) as input and prints their sum using those variables.

### Task 5: Using Built-in Variables
Bash provides several built-in variables that hold useful information. Your task is to create a bash script that utilizes at least three different built-in variables to display relevant information.

### Task 6: Wildcards
Wildcards are special characters used to perform pattern matching when working with files. Your task is to create a bash script that utilizes wildcards to list all the files with a specific extension in a directory.

## Submission Instructions:
- Create a single bash script that completes all the tasks mentioned above.
- Add comments at appropriate places to explain what each part of the script does.
- Ensure that your script is well-documented and easy to understand.
- To submit your entry, create a GitHub repository and commit your script to it.

**Good luck with Day 8 of the Bash Scripting Challenge! Tomorrow, the difficulty will increase as we move on to more advanced concepts. Happy scripting!**

[← Previous Day](../day07/README.md) | [Next Day →](../day09/README.md)



# Day 8 Answers: Shell Scripting Challenge

## Tasks

1. **Comments**
   - In bash scripts, comments are used to add explanatory notes or disable certain lines of code. Your task is to create a bash script with comments explaining what the script does.

   **Answer**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day08/image/task1.png)

2. **Echo**
   - The echo command is used to display messages on the terminal. Your task is to create a bash script that uses echo to print a message of your choice.

   **Answer**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day08/image/task2.png)

3. **Variables**
   - Variables in bash are used to store data and can be referenced by their name. Your task is to create a bash script that declares variables and assigns values to them.

   **Answer**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day08/image/task3.png)

4. **Using Variables**
   - Now that you have declared variables, let's use them to perform a simple task. Create a bash script that takes two variables (numbers) as input and prints their sum using those variables.

   **Answer**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day08/image/task4.png)  

5. **Using Built-in Variables**
   - Bash provides several built-in variables that hold useful information. Your task is to create a bash script that utilizes at least three different built-in variables to display relevant information.

   **Answer**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day08/image/task5.png)     

6. **Wildcards**
   - Wildcards are special characters used to perform pattern matching when working with files. Your task is to create a bash script that utilizes wildcards to list all the files with a specific extension in a directory.

   **Answer**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day08/image/task6.png)     

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)   



# Day 9 Task: Shell Scripting Challenge Directory Backup with Rotation


## Challenge Description

Your task is to create a bash script that takes a directory path as a command-line argument and performs a backup of the directory. The script should create timestamped backup folders and copy all the files from the specified directory into the backup folder.

Additionally, the script should implement a rotation mechanism to keep only the last 3 backups. This means that if there are more than 3 backup folders, the oldest backup folders should be removed to ensure only the most recent backups are retained.

> The script will create a timestamped backup folder inside the specified directory and copy all the files into it. It will also check for existing backup folders and remove the oldest backups to keep only the last 3 backups.

## Example Usage

Assume the script is named `backup_with_rotation.sh`. Here's an example of how it will look,
also assuming the script is executed with the following commands on different dates:

1. First Execution (2023-07-30):

```
$ ./backup_with_rotation.sh /home/user/documents
```

Output:

```
Backup created: /home/user/documents/backup_2023-07-30_12-30-45
Backup created: /home/user/documents/backup_2023-07-30_15-20-10
Backup created: /home/user/documents/backup_2023-07-30_18-40-55
```

After this execution, the /home/user/documents directory will contain the following items:

```
backup_2023-07-30_12-30-45
backup_2023-07-30_15-20-10
backup_2023-07-30_18-40-55
file1.txt
file2.txt
...
```

2. Second Execution (2023-08-01):

```
$ ./backup_with_rotation.sh /home/user/documents
```

Output:

```
Backup created: /home/user/documents/backup_2023-08-01_09-15-30
```

After this execution, the /home/user/documents directory will contain the following items:

```
backup_2023-07-30_15-20-10
backup_2023-07-30_18-40-55
backup_2023-08-01_09-15-30
file1.txt
file2.txt
...
```

In this example, the script creates backup folders with timestamped names and retains only the last 3 backups while removing the older backups.

## Submission Instructions

Create a bash script named backup_with_rotation.sh that implements the Directory Backup with Rotation as described in the challenge.

Happy Learning

[← Previous Day](../day08/README.md) | [Next Day →](../day10/README.md)


Add comments in the script to explain the purpose and logic of each part.

Submit your entry by pushing the script to your GitHub repository.

Congratulations on completing Day 2 of the Bash Scripting Challenge! The challenge focuses on creating a backup script with rotation capabilities to manage multiple backups efficiently. Happy scripting and backing up!



# Day 9 Answers: Shell Scripting Challenge Directory Backup with Rotation

## Tasks

1. **Challenge Description**

      Your task is to create a bash script that takes a directory path as a command-line argument and performs a backup of the directory. The script should create timestamped backup folders and copy all the files from the specified directory into the backup folder.

      Additionally, the script should implement a rotation mechanism to keep only the last 3 backups. This means that if there are more than 3 backup folders, the oldest backup folders should be removed to ensure only the most recent backups are retained.

      > The script will create a timestamped backup folder inside the specified directory and copy all the files into it. It will also check for existing backup folders and remove the oldest backups to keep only the last 3 backups.

   **Answer**

   **Create a Folder And Make Some File**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day09/image/task11.png)

      - Note:
         - First, check whether zip is installed or not.
           ```bash
              zip  
         - If you have not installed
           ```bash
              sudo apt install zip

   **Crontab Job Scheduling:**  
   
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day09/image/task2.png)  
      - Auto scheduling through `crontab job scheduling`:
        ```bash
           * 1 * * * bash /root/backup.sh /root/datafile /root/backup 

   **It will take a backup every hour, and the oldest backups will be deleted, leaving only the latest three backups visible:**  
   
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day09/image/task3.png)  

   **Bash Script:**
   
   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day09/image/bash1.png)

   **Reference**  
   [TrainWithShubham - Production Backup Rotation | Shell Scripting For DevOps Engineer](https://youtu.be/PZYJ33bMXAw?si=Zb50P67x_F32ikeO)   

   [LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)



# Day 10 Task: Log Analyzer and Report Generator

## Challenge Title: Log Analyzer and Report Generator

## Scenario

You are a system administrator responsible for managing a network of servers. Every day, a log file is generated on each server containing important system events and error messages. As part of your daily tasks, you need to analyze these log files, identify specific events, and generate a summary report.

## Task

Write a Bash script that automates the process of analyzing log files and generating a daily summary report. The script should perform the following steps:

1. **Input:** The script should take the path to the log file as a command-line argument.

2. **Error Count:** Analyze the log file and count the number of error messages. An error message can be identified by a specific keyword (e.g., "ERROR" or "Failed"). Print the total error count.

3. **Critical Events:** Search for lines containing the keyword "CRITICAL" and print those lines along with the line number.

4. **Top Error Messages:** Identify the top 5 most common error messages and display them along with their occurrence count.

5. **Summary Report:** Generate a summary report in a separate text file. The report should include:
   - Date of analysis
   - Log file name
   - Total lines processed
   - Total error count
   - Top 5 error messages with their occurrence count
   - List of critical events with line numbers

6. **Optional Enhancement:** Add a feature to automatically archive or move processed log files to a designated directory after analysis.

## Tips

- Use `grep`, `awk`, and other command-line tools to process the log file.
- Utilize arrays or associative arrays to keep track of error messages and their counts.
- Use appropriate error handling to handle cases where the log file doesn't exist or other issues arise.

## Sample Log File

A sample log file named `sample_log.log` has been provided in the same directory as this challenge file. You can use this file to test your script or use [this](https://github.com/logpai/loghub/blob/master/Zookeeper/Zookeeper_2k.log)

## How to Participate

1. Clone this repository or download the challenge file from the provided link.
2. Write your Bash script to complete the log analyzer and report generator task.
3. Use the provided `sample_log.log` or create your own log files for testing.
4. Test your script with various log files and scenarios to ensure accuracy.
5. Submit your completed script by the end of Day 10 of the 90-day DevOps challenge.

## Submission

Submit your completed script by [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) or sending the script file to the challenge organizer.

Good luck and happy scripting!

[← Previous Day](../day09/README.md) | [Next Day →](../day11/README.md)



# Day 10 Answers: Log Analyzer and Report Generator

## Scenario

You are a system administrator responsible for managing a network of servers. Every day, a log file is generated on each server containing important system events and error messages. As part of your daily tasks, you need to analyze these log files, identify specific events, and generate a summary report.

## Task

Write a Bash script that automates the process of analyzing log files and generating a daily summary report. The script should perform the following steps:

1. **Input:** The script should take the path to the log file as a command-line argument.

2. **Error Count:** Analyze the log file and count the number of error messages. An error message can be identified by a specific keyword (e.g., "ERROR" or "Failed"). Print the total error count.

3. **Critical Events:** Search for lines containing the keyword "CRITICAL" and print those lines along with the line number.

4. **Top Error Messages:** Identify the top 5 most common error messages and display them along with their occurrence count.

5. **Summary Report:** Generate a summary report in a separate text file. The report should include:
   - Date of analysis
   - Log file name
   - Total lines processed
   - Total error count
   - Top 5 error messages with their occurrence count
   - List of critical events with line numbers

   <h2>Answer</h2>

   - **First created a folder and then a log file.**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day10/image/task1.png)

   - **Bash Code for Reference.**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day10/image/task2.png)

   - <h2>Output</h2>

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day10/image/output.png)

6. **Optional Enhancement:** Add a feature to automatically archive or move processed log files to a designated directory after analysis.

## Tips

- Use `grep`, `awk`, and other command-line tools to process the log file.
- Utilize arrays or associative arrays to keep track of error messages and their counts.
- Use appropriate error handling to handle cases where the log file doesn't exist or other issues arise.

## Sample Log File

A sample log file named `sample_log.log` has been provided in the same directory as this challenge file. You can use this file to test your script or use [this](https://github.com/logpai/loghub/blob/master/Zookeeper/Zookeeper_2k.log)

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)



# Day 11 Task: Error Handling in Shell Scripting

## Learning Objectives
Understanding how to handle errors in shell scripts is crucial for creating robust and reliable scripts. Today, you'll learn how to use various techniques to handle errors effectively in your bash scripts.

## Topics to Cover
1. **Understanding Exit Status**: Every command returns an exit status (0 for success and non-zero for failure). Learn how to check and use exit statuses.
2. **Using `if` Statements for Error Checking**: Learn how to use `if` statements to handle errors.
3. **Using `trap` for Cleanup**: Understand how to use the `trap` command to handle unexpected errors and perform cleanup.
4. **Redirecting Errors**: Learn how to redirect errors to a file or `/dev/null`.
5. **Creating Custom Error Messages**: Understand how to create meaningful error messages for debugging and user information.

## Tasks

### Task 1: Checking Exit Status
- Write a script that attempts to create a directory and checks if the command was successful. If not, print an error message.

### Task 2: Using `if` Statements for Error Checking
- Modify the script from Task 1 to include more commands (e.g., creating a file inside the directory) and use `if` statements to handle errors at each step.

### Task 3: Using `trap` for Cleanup
- Write a script that creates a temporary file and sets a `trap` to delete the file if the script exits unexpectedly.

### Task 4: Redirecting Errors
- Write a script that tries to read a non-existent file and redirects the error message to a file called `error.log`.

### Task 5: Creating Custom Error Messages
- Modify one of the previous scripts to include custom error messages that provide more context about what went wrong.

## Example Scripts

### Example 1: Checking Exit Status
```bash
#!/bin/bash
mkdir /tmp/mydir
if [ $? -ne 0 ]; then
  echo "Failed to create directory /tmp/mydir"
fi
```

### Example 2: Trap
```bash
#!/bin/bash
tempfile=$(mktemp)
trap "rm -f $tempfile" EXIT

echo "This is a temporary file." > $tempfile
cat $tempfile
# Simulate an error
exit 1
```

### Example 3: Redirecting Errors
```bash
#!/bin/bash
cat non_existent_file.txt 2> error.log
```

### Example 4: Custom Error Messages
```bash
#!/bin/bash
mkdir /tmp/mydir
if [ $? -ne 0 ]; then
  echo "Error: Directory /tmp/mydir could not be created. Check if you have the necessary permissions."
fi
```

[← Previous Day](../day10/README.md) | [Next Day →](../day12/README.md)



# Day 11 Answers: Error Handling in Shell Scripting

## Learning Objectives
Understanding how to handle errors in shell scripts is crucial for creating robust and reliable scripts. Today, you'll learn how to use various techniques to handle errors effectively in your bash scripts.

## Topics to Cover
1. **Understanding Exit Status**: Every command returns an exit status (0 for success and non-zero for failure). Learn how to check and use exit statuses.
2. **Using `if` Statements for Error Checking**: Learn how to use `if` statements to handle errors.
3. **Using `trap` for Cleanup**: Understand how to use the `trap` command to handle unexpected errors and perform cleanup.
4. **Redirecting Errors**: Learn how to redirect errors to a file or `/dev/null`.
5. **Creating Custom Error Messages**: Understand how to create meaningful error messages for debugging and user information.

## Tasks with Answers

### Task 1: Checking Exit Status
- Write a script that attempts to create a directory and checks if the command was successful. If not, print an error message.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day11/image/task1.png)

### Task 2: Using `if` Statements for Error Checking
- Modify the script from Task 1 to include more commands (e.g., creating a file inside the directory) and use `if` statements to handle errors at each step.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day11/image/task2.png)

### Task 3: Using `trap` for Cleanup
- Write a script that creates a temporary file and sets a `trap` to delete the file if the script exits unexpectedly.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day11/image/task3.png)

### Task 4: Redirecting Errors
- Write a script that tries to read a non-existent file and redirects the error message to a file called `error.log`.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day11/image/task4.png)

### Task 5: Creating Custom Error Messages
- Modify one of the previous scripts to include custom error messages that provide more context about what went wrong.

**Answer** 

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day11/image/task5.png)

   - **I also intentionally created an error by not creating the file, so it showed me this error. I did this for reference.**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day11/image/task5ka1.png)

## Example Scripts

### Example 1: Checking Exit Status
```bash
#!/bin/bash
mkdir /tmp/mydir
if [ $? -ne 0 ]; then
  echo "Failed to create directory /tmp/mydir"
fi
```

### Example 2: Trap
```bash
#!/bin/bash
tempfile=$(mktemp)
trap "rm -f $tempfile" EXIT

echo "This is a temporary file." > $tempfile
cat $tempfile
# Simulate an error
exit 1
```

### Example 3: Redirecting Errors
```bash
#!/bin/bash
cat non_existent_file.txt 2> error.log
```

### Example 4: Custom Error Messages
```bash
#!/bin/bash
mkdir /tmp/mydir
if [ $? -ne 0 ]; then
  echo "Error: Directory /tmp/mydir could not be created. Check if you have the necessary permissions."
fi
```

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)



# Day 12 Task: Deep Dive in Git & GitHub for DevOps Engineers

## Find the answers by your understandings (Shouldn't be copied from the internet & use hand-made diagrams) of the questions below and write a blog on it.

1. What is Git and why is it important?
2. What is the difference between Main Branch and Master Branch?
3. Can you explain the difference between Git and GitHub?
4. How do you create a new repository on GitHub?
5. What is the difference between a local & remote repository? How to connect local to remote?

## Tasks

### Task 1:
- Set your user name and email address, which will be associated with your commits.

### Task 2:
- Create a repository named "DevOps" on GitHub.
- Connect your local repository to the repository on GitHub.
- Create a new file in Devops/Git/Day-02.txt & add some content to it.
- Push your local commits to the repository on GitHub.

Reference: [YouTube Video](https://youtu.be/AT1uxOLsCdk)

Note: These steps assume that you have already installed Git on your computer and have created a GitHub account. If you need help with these prerequisites, you can refer to the [guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

[← Previous Day](../day11/README.md) | [Next Day →](../day13/README.md)



# Day 12 Answers: Deep Dive in Git & GitHub for DevOps Engineers

## Find the answers by your understandings (Shouldn't be copied from the internet & use hand-made diagrams) of the questions below and write a blog on it.

1. What is Git and why is it important?
   - **Git** is a distributed version control system that allows multiple developers to work on a project simultaneously without overwriting each other's changes. It helps track changes in source code during software development, enabling collaboration, version control, and efficient management of code changes.

   **Importance of Git:**
     - **Version Control:** Keeps track of changes, allowing you to revert to previous versions if needed.
     - **Collaboration:** Multiple developers can work on the same project simultaneously.   
     - **Branching:** Allows you to work on different features or fixes in isolation.  
     - **Backup::** Acts as a backup of your codebase. 

2. What is the difference between Main Branch and Master Branch?
   - Traditionally, **master** was the default branch name in Git repositories. However, many communities have moved to using **main** as the default branch name to be more inclusive and avoid potentially offensive terminology.
   
   - Main Branch vs. Master Branch:
     -  **Main Branch:** The new default branch name used in many modern repositories.
     - **Master Branch:** The traditional default branch name used in older repositories.

     The traditional default branch name used in older repositories.


3. Can you explain the difference between Git and GitHub?
   - **Git** is a version control system, while **GitHub** is a web-based platform that uses Git for version control and adds collaboration features like pull requests, issue tracking, and project management.
      - Git:
        - Command-line tool.
        - Manages local repositories.
      - GitHub:
        - Hosting service for Git repositories.
        - Adds collaboration tools and user interfaces.

4. How do you create a new repository on GitHub?
   1. Go to GitHub.
   2. Click on the + icon in the top right corner.
   3. Select New repository.
   4. Enter a repository name (e.g., "DevOps").
   5. Click Create repository. 

5. What is the difference between a local & remote repository? How to connect local to remote?
   - Local Repository:
     - Stored on your local machine.
     - Contains your working directory and Git database. 
   - Remote Repository:
     - Hosted on a server (e.g., GitHub).
     - Allows collaboration with other developers.
   - Connecting Local to Remote:
     1. Initialize a local repository: `git init`
     2. Add a remote: `git remote add origin <URL>`

## Tasks with Answers

### Task 1:
- Set your user name and email address, which will be associated with your commits.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day12/image/set_user_name_and_email_address.png)

### Task 2:
- Create a repository named "DevOps" on GitHub.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day12/image/create_a_new_repository.png)

- Connect your local repository to the repository on GitHub.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day12/image/connect_your_local_repository_to_the_repository_on_github.png)

- Create a new file in Devops/Git/Day-12.txt & add some content to it.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day12/image/create_a_new_file.png)

- Push your local commits to the repository on GitHub.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day12/image/push_repository.png)

**After that if you check it on GitHub then it's output will look like this**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day12/image/gitui.png)

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day12/image/gitui1.png)

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day12/image/gitui2.png)


[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)



# Day 13 Task: Advance Git & GitHub for DevOps Engineers

## Git Branching

Branches are a core concept in Git that allow you to isolate development work without affecting other parts of your repository. Each repository has one default branch, and can have multiple other branches. You can merge a branch into another branch using a pull request.

Branches let you develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository.

## Git Revert and Reset

Git reset and git revert are two commonly used commands that allow you to remove or edit changes you’ve made in the code in previous commits. Both commands can be very useful in different scenarios.

## Git Rebase and Merge

### What Is Git Rebase?

Git rebase is a command that lets users integrate changes from one branch to another, and the commit history is modified once the action is complete. Git rebase helps keep a clean project history.

### What Is Git Merge?

Git merge is a command that allows developers to merge Git branches while keeping the logs of commits on branches intact. Even though merging and rebasing do similar things, they handle commit logs differently.

For a better understanding of Git Rebase and Merge, check out this [article](https://www.simplilearn.com/git-rebase-vs-merge-article).

## Tasks

### Task 1: Feature Development with Branches

1. **Create a Branch and Add a Feature:**
   - Add a text file called `version01.txt` inside the `Devops/Git/` directory with “This is the first feature of our application” written inside.
   - Create a new branch from `master`. 
     ```bash
     git checkout -b dev
     ```
   - Commit your changes with a message reflecting the added feature.
     ```bash
     git add Devops/Git/version01.txt
     git commit -m "Added new feature"
     ```

2. **Push Changes to GitHub:**
   - Push your local commits to the repository on GitHub.
     ```bash
     git push origin dev
     ```

3. **Add More Features with Separate Commits:**
   - Update `version01.txt` with the following lines, committing after each change:
     - 1st line: `This is the bug fix in development branch`
       ```bash
       echo "This is the bug fix in development branch" >> Devops/Git/version01.txt
       git commit -am "Added feature2 in development branch"
       ```
     - 2nd line: `This is gadbad code`
       ```bash
       echo "This is gadbad code" >> Devops/Git/version01.txt
       git commit -am "Added feature3 in development branch"
       ```
     - 3rd line: `This feature will gadbad everything from now`
       ```bash
       echo "This feature will gadbad everything from now" >> Devops/Git/version01.txt
       git commit -am "Added feature4 in development branch"
       ```

4. **Restore the File to a Previous Version:**
   - Revert or reset the file to where the content should be “This is the bug fix in development branch”.
     ```bash
     git revert HEAD~2
     ```

### Task 2: Working with Branches

1. **Demonstrate Branches:**
   - Create 2 or more branches and take screenshots to show the branch structure.

2. **Merge Changes into Master:**
   - Make some changes to the `dev` branch and merge it into `master`.
     ```bash
     git checkout master
     git merge dev
     ```

3. **Practice Rebase:**
   - Try rebasing and observe the differences.
     ```bash
     git rebase master
     ```

## Note:

Following best practices for branching is important. Check out these [best practices](https://www.flagship.io/git-branching-strategies/) that the industry follows.

Simple Reference on branching: [video](https://youtu.be/NzjK9beT_CY)

Advanced Reference on branching: [video](https://youtu.be/7xhkEQS3dXw)

Share your learnings from this task on LinkedIn using #90DaysOfDevOps Challenge. Happy Learning!

[← Previous Day](../day12/README.md) | [Next Day →](../day14/README.md)



# Day 13 Answers: Advance Git & GitHub for DevOps Engineers

## Git Branching

Branches are a core concept in Git that allow you to isolate development work without affecting other parts of your repository. Each repository has one default branch, and can have multiple other branches. You can merge a branch into another branch using a pull request.

Branches let you develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository.

## Git Revert and Reset

Git reset and git revert are two commonly used commands that allow you to remove or edit changes you’ve made in the code in previous commits. Both commands can be very useful in different scenarios.

## Git Rebase and Merge

### What Is Git Rebase?

Git rebase is a command that lets users integrate changes from one branch to another, and the commit history is modified once the action is complete. Git rebase helps keep a clean project history.

### What Is Git Merge?

Git merge is a command that allows developers to merge Git branches while keeping the logs of commits on branches intact. Even though merging and rebasing do similar things, they handle commit logs differently.

For a better understanding of Git Rebase and Merge, check out this [article](https://www.simplilearn.com/git-rebase-vs-merge-article).

## Tasks with Answers

### Task 1: Feature Development with Branches

1. **Create a Branch and Add a Feature:**
   - Add a text file called `version01.txt` inside the `Devops/Git/` directory with “This is the first feature of our application” written inside. 

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/1%20Create%20a%20Branch%20and%20Add%20a%20Feature.png)

   - Create a new branch from `master`. 
     ```bash
     git checkout -b dev
     ```
**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/2%20Create%20a%20new%20branch.png)

   - Commit your changes with a message reflecting the added feature.
     ```bash
     git add Devops/Git/version01.txt
     git commit -m "Added new feature"
     ```

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/3%20Commit%20your%20changes%20with%20a%20message%20reflecting.png)

2. **Push Changes to GitHub:**
   - Push your local commits to the repository on GitHub.
     ```bash
     git push origin dev
     ```
**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/4%20Push%20your%20local%20commits%20to%20the%20repository%20on%20GitHub.png)

3. **Add More Features with Separate Commits:**
   - Update `version01.txt` with the following lines, committing after each change:
     - 1st line: `This is the bug fix in development branch`
       ```bash
       echo "This is the bug fix in development branch" >> Devops/Git/version01.txt
       git commit -am "Added feature2 in development branch"
       ```
**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/5%20This%20is%20the%20bug%20fix%20in%20development%20branch.png)

  - 2nd line: `This is gadbad code`
       ```bash
       echo "This is gadbad code" >> Devops/Git/version01.txt
       git commit -am "Added feature3 in development branch"
       ```
**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/6%20This%20is%20gadbad%20code.png)

  - 3rd line: `This feature will gadbad everything from now`
       ```bash
       echo "This feature will gadbad everything from now" >> Devops/Git/version01.txt
       git commit -am "Added feature4 in development branch"
       ```
**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/7%20This%20feature%20will%20gadbad%20everything%20from%20now.png)

4. **Restore the File to a Previous Version:**
   - Revert or reset the file to where the content should be “This is the bug fix in development branch”.
     ```bash
     git revert HEAD~2
     ```
**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/8%20Restore%20the%20File%20to%20a%20Previous%20Version.png)

This command reverts the last two commits, effectively removing the "gadbad code" and "gadbad everything" lines.

### Task 2: Working with Branches

1. **Demonstrate Branches:**
   - Create 2 or more branches and take screenshots to show the branch structure.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/9%20Create%202%20or%20more%20branches.png)

2. **Merge Changes into Master:**
   - Make some changes to the `dev` branch and merge it into `master`.
     ```bash
     git checkout master
     git merge dev
     ```
**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/11%20Merge%20Changes%20into%20Master_main.png)

   - Screenshot of branch structure:
     - To visualize the branch structure, you can use `git log` with graph options or a graphical tool like GitKraken. 

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/10%20Screenshot%20of%20branch%20structure.png)

3. **Practice Rebase:**
   - Try rebasing and observe the differences.
     ```bash
     git rebase master
     ```
**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day13/image/12%20Practice%20Rebase.png)

   - During a rebase, Git re-applies commits from the current branch (in this case, dev) onto the target branch (master). This results in a linear commit history.

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)



# Day 14 Task: Create a Linux & Git-GitHub Cheat Sheet

## Finally!! 🎉

You have completed the Linux & Git-GitHub hands-on tasks, and I hope you have learned something interesting from it. 🙌

Now, let's create an interesting 😉 assignment that will not only help you in the future but also benefit the DevOps community!

## Task: Create a Cheat Sheet

Let’s make a well-articulated and documented **cheat sheet** with all the commands you learned so far in Linux and Git-GitHub, along with a brief description of their usage.

Show us your knowledge mixed with your creativity 😎.

### Guidelines

- The cheat sheet should be unique and reflect your understanding.
- Include all the important commands you have learned.
- Provide a brief description of each command's usage.
- Make it visually appealing and easy to understand.

### Reference

For your reference, check out this [cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf). However, ensure that your cheat sheet is unique.

### Share Your Work

Post your cheat sheet on LinkedIn and spread the knowledge. 😃

**Happy Learning! :)**

[← Previous Day](../day13/README.md) | [Next Day →](../day15/README.md)



# Day 14 Answers: Create a Linux & Git-GitHub Cheat Sheet

## Finally!! 🎉

You have completed the Linux & Git-GitHub hands-on tasks, and I hope you have learned something interesting from it. 🙌

Now, let's create an interesting 😉 assignment that will not only help you in the future but also benefit the DevOps community!

## Tasks with Answers: Create a Cheat Sheet

Let’s make a well-articulated and documented **cheat sheet** with all the commands you learned so far in Linux and Git-GitHub, along with a brief description of their usage.

Show us your knowledge mixed with your creativity 😎.

### Guidelines

- The cheat sheet should be unique and reflect your understanding.
- Include all the important commands you have learned.
- Provide a brief description of each command's usage.
- Make it visually appealing and easy to understand.

## Linux Commands / Git Commands

### File and Directory Management
- `ls` - Lists files and directories.
- `cd <directory>` - Changes the directory.
- `pwd` - Prints current directory.
- `mkdir <directory>` - Creates a new directory.
- `rm <file>` - Removes a file.
- `rm -r <directory>` - Removes a directory and its contents.
- `cp <source> <destination>` - Copies files or directories.
- `mv <source> <destination>` - Moves or renames files or directories.
- `touch <file>` - Creates or updates a file.

### Viewing and Editing Files
- `cat <file>` - Displays file content.
- `less <file>` - Views file content one screen at a time.
- `nano <file>` - Edits files using nano editor.
- `vim <file>` - Edits files using vim editor.

### System Information
- `uname -a` - Displays system information.
- `top` - Shows real-time system processes.
- `df -h` - Displays disk usage.
- `free -h` - Displays memory usage.

### Permissions
- `chmod <permissions> <file>` - Changes file permissions.
- `chown <owner>:<group> <file>` - Changes file owner and group.

### Networking
- `ping <host>` - Sends ICMP echo requests.
- `ifconfig` - Displays or configures network interfaces.

## Git Commands

### Configuration
- `git config --global user.name "Your Name"` - Sets global user name.
- `git config --global user.email "your.email@example.com"` - Sets global user email.

### Repository Management
- `git init` - Initializes a new repository.
- `git clone <repository>` - Clones a repository.

### Basic Operations
- `git status` - Shows working tree status.
- `git add <file>` - Stages changes.
- `git commit -m "message"` - Commits changes.
- `git push` - Pushes changes to remote repository.
- `git checkout -b dev` - Create a new branch from `master`.
- `git checkout` - switch to another branch and check it out into your working directory.
- `git log --oneline --graph --all` - visualize the branch structure.
- `git push origin dev` - Push Changes to GitHub.
- `git merge dev` - merge it into `master/main`.
- `git log` -  show all commits in the current branch’s history.

### Reference

For your reference, check out this [cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf). However, ensure that your cheat sheet is unique.

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)


# Day 15 Task: Basics of Python for DevOps Engineers

## Hello Dosto 

Let's start with the basics of Python, as this is also important for DevOps Engineers to build logic and programs.

### What is Python?

- Python is an open-source, general-purpose, high-level, and object-oriented programming language.
- It was created by **Guido van Rossum**.
- Python consists of vast libraries and various frameworks like Django, TensorFlow, Flask, Pandas, Keras, etc.

### How to Install Python?

You can install Python on your system, whether it is Windows, macOS, Ubuntu, CentOS, etc. Below are the links for the installation:

- [Windows Installation](https://www.python.org/downloads/)
- Ubuntu: `apt-get install python3.6`

## Tasks

### Task 1:

1. Install Python on your respective OS, and check the version.
2. Read about different data types in Python.

You can get the complete playlist [here](https://www.youtube.com/watch?v=abPgj_3hzVY&list=PLlfy9GnSVerS_L5z0COaF7rsbgWmJXTOM) 🙌

Don't forget to share your journey over LinkedIn. Let the community know that you have started another chapter of your journey.

**Happy Learning, Ruko Mat Phod do! 😃**

[← Previous Day](../day14/README.md) | [Next Day →](../day16/README.md)



# Day 15 Answers: Basics of Python for DevOps Engineers

## What is Python?

Python is an open-source, general-purpose, high-level, and object-oriented programming language created by Guido van Rossum. It has a vast ecosystem of libraries and frameworks, such as Django, TensorFlow, Flask, Pandas, Keras, and many more.

## How to Install Python

### Windows Installation

1. Go to the [Python website](https://www.python.org/downloads/).
2. Download the latest version of Python.
3. Run the installer and follow the instructions.
4. Check the installation by opening a command prompt and typing:
   ```bash
   python --version

### Ubuntu Installation
   - `sudo apt-get update`
   - `sudo apt-get install python3.6`

### macOS Installation

1. Download the installer from the [Python website](https://www.python.org/downloads/macos/).
2. Follow the installation instructions.
3. Check the installation by opening a terminal and typing:
   - `python3 --version`

## Tasks with Answers

### Task 1:

1. Install Python on your respective OS, and check the version.

**Answer**

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day15/image/Installation_Python.png)

### 2. Read about different data types in Python.
   - Python supports several data types, which can be categorized as follows:
      - **Numeric Types:**
         - **int:** Integer values
            - `x = 10`

         - **float:** Floating-point values
            - `y = 10.5`

         - **complex:** Complex numbers
            - `z = 3 + 5j`

      - **Sequence Types:**
         - **str:** String values
            - `name = "bhavin"`

         - **list:** Ordered collection of items
            - `fruits = ["apple", "banana", "cherry"]`

         - **tuple:** Ordered, immutable collection of items
            - `coordinates = (10.0, 20.0)`

   - **Mapping Types:**
      - **dict:** Key-value pairs
         - `person = {"name": "bhavin", "age": 24}`

   - **Set Types:**
      - **set:** Unordered collection of unique items
         - `unique_numbers = {1, 2, 3, 4, 5}`

      - **frozenset:** Immutable set
         - `frozen_numbers = frozenset([1, 2, 3, 4, 5])`

   - **Boolean Type:**
      - **bool:** Boolean values
         - `is_active = True`

   - **None Type:**
      - **NoneType:** Represents the absence of a value
         - `data = None`


You can get the complete playlist [here](https://www.youtube.com/watch?v=abPgj_3hzVY&list=PLlfy9GnSVerS_L5z0COaF7rsbgWmJXTOM) 🙌

**Happy Learning, Ruko Mat Phod do! 😃**

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)



# Day 16 Task: Docker for DevOps Engineers

### Docker

Docker is a software platform that allows you to build, test, and deploy applications quickly. Docker packages software into standardized units called containers that have everything the software needs to run, including libraries, system tools, code, and runtime. Using Docker, you can quickly deploy and scale applications into any environment and know your code will run.

## Tasks

As you have already installed Docker in previous tasks, now is the time to run Docker commands.

- Use the `docker run` command to start a new container and interact with it through the command line. [Hint: `docker run hello-world`]

- Use the `docker inspect` command to view detailed information about a container or image.

- Use the `docker port` command to list the port mappings for a container.

- Use the `docker stats` command to view resource usage statistics for one or more containers.

- Use the `docker top` command to view the processes running inside a container.

- Use the `docker save` command to save an image to a tar archive.

- Use the `docker load` command to load an image from a tar archive.

These tasks involve simple operations that can be used to manage images and containers.

For reference, you can watch this video:
https://youtu.be/Tevxhn6Odc8

You can post on LinkedIn and let us know what you have learned from this task by #90DaysOfDevOps Challenge. Happy Learning :)

[← Previous Day](../day15/README.md) | [Next Day →](../day17/README.md)



# Day 16 Answers: Docker for DevOps Engineers

### Docker

Docker is a software platform that allows you to build, test, and deploy applications quickly. Docker packages software into standardized units called containers that have everything the software needs to run, including libraries, system tools, code, and runtime. Using Docker, you can quickly deploy and scale applications into any environment and know your code will run.

## Tasks with Answers

As you have already installed Docker in previous tasks, now is the time to run Docker commands.

### 1. Use the `docker run` command to start a new container and interact with it through the command line. [Hint: `docker run hello-world`]

**Answer**
   - This command runs the `hello-world` image, which prints a message confirming that Docker is working correctly.
![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day16/image/1_Start_a_New_Container.png)

### 2. Use the `docker inspect` command to view detailed information about a container or image.

**Answer**
   - View Detailed Information About a Container or Image:

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day16/image/2_docker_inspect.png)

### 3. Use the `docker port` command to list the port mappings for a container.

**Answer**
   - This command maps port 8181 on the host to port 82 in the container and lists the port mappings.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day16/image/3_docker_port.png)

### 4. Use the `docker stats` command to view resource usage statistics for one or more containers.

**Answer**
   - This command provides a live stream of resource usage statistics for all running containers.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day16/image/4_docker_stats.png)

### 5. Use the `docker top` command to view the processes running inside a container.

**Answer**
   - This command lists the processes running inside the `my_container2` container.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day16/image/5_docker_top.png)

### 6. Use the `docker save` command to save an image to a tar archive.

**Answer**
   - This command saves the `nginx` image to a tar archive named `my_image.tar`.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day16/image/6_docker_save.png)

### 7. Use the `docker load` command to load an image from a tar archive.

**Answer**
   - This command loads the image from the `my_image.tar` archive into Docker.

![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day16/image/7_docker_load.png)

These tasks involve simple operations that can be used to manage images and containers.

For reference, you can watch this video: [Docker Tutorial on AWS EC2 as DevOps Engineer // DevOps Project Bootcamp Day 2](https://youtu.be/Tevxhn6Odc8).

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)



## Day 17 Task: Docker Project for DevOps Engineers

### You people are doing just amazing in **#90daysofdevops**. Today's challenge is so special because you are going to do a DevOps project with Docker. Are you excited? 😍

# Dockerfile

Docker is a tool that makes it easy to run applications in containers. Containers are like small packages that hold everything an application needs to run. To create these containers, developers use something called a Dockerfile.

A Dockerfile is like a set of instructions for making a container. It tells Docker what base image to use, what commands to run, and what files to include. For example, if you were making a container for a website, the Dockerfile might tell Docker to use an official web server image, copy the files for your website into the container, and start the web server when the container starts.

For more about Dockerfile, visit [here](https://rushikesh-mashidkar.hashnode.dev/dockerfile-docker-compose-swarm-and-volumes).

## Task

- Create a Dockerfile for a simple web application (e.g. a Node.js or Python app)
- Build the image using the Dockerfile and run the container
- Verify that the application is working as expected by accessing it in a web browser
- Push the image to a public or private repository (e.g. Docker Hub)

For a reference project, visit [here](https://youtu.be/Tevxhn6Odc8).

If you want to dive further, watch this [bootcamp](https://youtube.com/playlist?list=PLlfy9GnSVerRqYJgVYO0UiExj5byjrW8u).

You can share your learning with everyone over LinkedIn and tag us along. 😃

Happy Learning :)

[← Previous Day](../day16/README.md) | [Next Day →](../day18/README.md)



# Day 17 Answers: Docker Project for DevOps Engineers

### You people are doing just amazing in **#90daysofdevops**. Today's challenge is so special because you are going to do a DevOps project with Docker. Are you excited? 😍

# Dockerfile

Docker is a tool that makes it easy to run applications in containers. Containers are like small packages that hold everything an application needs to run. To create these containers, developers use something called a Dockerfile.

A Dockerfile is like a set of instructions for making a container. It tells Docker what base image to use, what commands to run, and what files to include. For example, if you were making a container for a website, the Dockerfile might tell Docker to use an official web server image, copy the files for your website into the container, and start the web server when the container starts.

For more about Dockerfile, visit [here](https://rushikesh-mashidkar.hashnode.dev/dockerfile-docker-compose-swarm-and-volumes).

## Tasks with Answers

**1. Create a Dockerfile for a simple web application (e.g. a Node.js or Python app)**
   - **1. Create a Simple Flask Application**
      - Create a new directory for your project and navigate into it:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day17/image/1_Create_a_new_directory.png)

      - Create a new file named `app.py` and add the following content:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day17/image/2_app_py.png)

      - Create a requirements file named `requirements.txt` and add the following content:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day17/image/3_Create_a_requirements_file.png)

   - **2. Create a Dockerfile**
      - Create a file named `Dockerfile` in the same directory and add the following content:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day17/image/4_Create_a_Dockerfile.png)

**2. Build the image using the Dockerfile and run the container**
   - To build the Docker image, run the following command in the directory containing the Dockerfile:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day17/image/5_build_the_docker_image.png)

   - Run the Container
      - To run the container, use the following command:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day17/image/6_Run_the_Container.png)

**3. Verify that the application is working as expected by accessing it in a web browser**
   - Open your web browser and navigate to `http://localhost:5000`. You should see the message "Hello, World!".

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day17/image/7_Verify_the_Application.png)

**4. Push the image to a public or private repository (e.g. Docker Hub)**
   - To push the image to Docker Hub, you need to tag it with your Docker Hub username and repository name, then push it.
   - **1. Tag the Image**

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day17/image/8_Tag_the_Image.png)

   - **2. Push the Image**

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day17/image/9_Push_the_Image.png)

For a reference project, visit [here](https://youtu.be/Tevxhn6Odc8).

If you want to dive further, watch this [bootcamp](https://youtube.com/playlist?list=PLlfy9GnSVerRqYJgVYO0UiExj5byjrW8u).

You can share your learning with everyone over LinkedIn and tag us along. 😃

Happy Learning :)

[Code for Reference](https://raw.githubusercontent.com/Bhavin213/90DaysOfDevOps/master/2024/day17/code.txt)

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)



# Day 18 Task: Docker for DevOps Engineers

Till now you have created a Dockerfile and pushed it to the repository. Let's move forward and dig deeper into other Docker concepts. Today, let's study Docker Compose! 😃

## Docker Compose

- Docker Compose is a tool that was developed to help define and share multi-container applications.
- With Compose, we can create a YAML file to define the services and, with a single command, spin everything up or tear it all down.
- Learn more about Docker Compose [here](https://tecadmin.net/tutorial/docker/docker-compose/).

## What is YAML?

- YAML is a data serialization language that is often used for writing configuration files. Depending on whom you ask, YAML stands for "Yet Another Markup Language" or "YAML Ain’t Markup Language" (a recursive acronym), which emphasizes that YAML is for data, not documents.
- YAML is a popular programming language because it is human-readable and easy to understand.
- YAML files use a .yml or .yaml extension.
- Read more about it [here](https://www.redhat.com/en/topics/automation/what-is-yaml).

## Task 1

Learn how to use the docker-compose.yml file to set up the environment, configure the services and links between different containers, and also to use environment variables in the docker-compose.yml file.

[Sample docker-compose.yml file](https://github.com/LondheShubham153/90DaysOfDevOps/blob/master/2023/day18/docker-compose.yaml)

## Task 2

- Pull a pre-existing Docker image from a public repository (e.g. Docker Hub) and run it on your local machine. Run the container as a non-root user (Hint: Use the `usermod` command to give the user permission to Docker). Make sure you reboot the instance after giving permission to the user.
- Inspect the container's running processes and exposed ports using the `docker inspect` command.
- Use the `docker logs` command to view the container's log output.
- Use the `docker stop` and `docker start` commands to stop and start the container.
- Use the `docker rm` command to remove the container when you're done.

## How to Run Docker Commands Without Sudo?

- Make sure Docker is installed and the system is updated (This was already completed as part of previous tasks):
- `sudo usermod -a -G docker $USER`
- Reboot the machine.

For reference, you can watch this [video](https://youtu.be/Tevxhn6Odc8).

You can post on LinkedIn and let us know what you have learned from this task by using #90DaysOfDevOps Challenge. Happy Learning! :)

[← Previous Day](../day17/README.md) | [Next Day →](../day19/README.md)



# Day 18 Answers:  Docker for DevOps Engineers

Till now you have created a Dockerfile and pushed it to the repository. Let's move forward and dig deeper into other Docker concepts. Today, let's study Docker Compose! 😃

## Docker Compose

- Docker Compose is a tool that was developed to help define and share multi-container applications.
- With Compose, we can create a YAML file to define the services and, with a single command, spin everything up or tear it all down.
- Learn more about Docker Compose [here](https://tecadmin.net/tutorial/docker/docker-compose/).

## What is YAML?

- YAML is a data serialization language that is often used for writing configuration files. Depending on whom you ask, YAML stands for "Yet Another Markup Language" or "YAML Ain’t Markup Language" (a recursive acronym), which emphasizes that YAML is for data, not documents.
- YAML is a popular programming language because it is human-readable and easy to understand.
- YAML files use a .yml or .yaml extension.
- Read more about it [here](https://www.redhat.com/en/topics/automation/what-is-yaml).

## Tasks with Answers

## Task 1

Learn how to use the docker-compose.yml file to set up the environment, configure the services and links between different containers, and also to use environment variables in the docker-compose.yml file.

[Sample docker-compose.yml file](https://github.com/LondheShubham153/90DaysOfDevOps/blob/master/2023/day18/docker-compose.yaml)

   **Answer**

   ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/1_docker_compose_yml_file.png)

## Task 2
   
   - **1. Pull a pre-existing Docker image from a public repository (e.g. Docker Hub) and run it on your local machine. Run the container as a non-root user (Hint: Use the `usermod` command to give the user permission to Docker). Make sure you reboot the instance after giving permission to the user.**
      - Pull the Docker image:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/2_Pull_the_Docker_image.png)

      - Add the current user to the Docker group:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/3_Add_the_current_user_to_the_Docker_group.png)

      - Reboot the machine to apply the changes:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/4_Reboot_the_machine_to_apply_the_changes.png)

      - Run the Docker container:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/5_Run_the_Docker_container.png)      

   - **2. Inspect the container's running processes and exposed ports using the `docker inspect` command.**
      - Inspect the container:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/6_Inspect_the_container.png)      

   - **3. Use the `docker logs` command to view the container's log output.**
      - View the logs:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/7_View_the_logs.png)

   - **4. Use the `docker stop` and `docker start` commands to stop and start the container.**
      - Stop the container:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/8_Stop_the_container.png)

      - Start the container:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/9_Start_the_container.png)

   - **5. Use the `docker rm` command to remove the container when you're done.**
      - Remove the container:

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/10_Remove_the_container.png)      

## How to Run Docker Commands Without Sudo?

- Make sure Docker is installed and the system is updated (This was already completed as part of previous tasks):
   - `sudo usermod -a -G docker $USER`

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/3_Add_the_current_user_to_the_Docker_group.png)      

   - Reboot the machine.

      **Answer**

      ![image](https://github.com/Bhavin213/90DaysOfDevOps/blob/master/2024/day18/image/4_Reboot_the_machine_to_apply_the_changes.png)         

For reference, you can watch this [video](https://youtu.be/Tevxhn6Odc8).

[LinkedIn](https://www.linkedin.com/in/bhavin-savaliya/)



# Day 19 Task: Docker for DevOps Engineers

**So far, you've learned how to create a docker-compose.yml file and push it to the repository. Let's move forward and explore more Docker Compose concepts. Today, let's study Docker Volume and Docker Network!** 😃

## Docker Volume

Docker allows you to create volumes, which are like separate storage areas that can be accessed by containers. They enable you to store data, like a database, outside the container, so it doesn't get deleted when the container is removed. You can also mount the same volume to multiple containers, allowing them to share data. For more details, check out this [reference](https://docs.docker.com/storage/volumes/).

## Docker Network

Docker allows you to create virtual networks, where you can connect multiple containers together. This way, the containers can communicate with each other and with the host machine. Each container has its own storage space, but if we want to share storage between containers, we need to use volumes. For more details, check out this [reference](https://docs.docker.com/network/).

## Task 1

Create a multi-container docker-compose file that will bring up and bring down containers in a single shot (e.g., create application and database containers).

### Hints:

- Use the `docker-compose up` command with the `-d` flag to start a multi-container application in detached mode.
- Use the `docker-compose scale` command to increase or decrease the number of replicas for a specific service. You can also add [`replicas`](https://stackoverflow.com/questions/63408708/how-to-scale-from-within-docker-compose-file) in the deployment file for auto-scaling.
- Use the `docker-compose ps` command to view the status of all containers, and `docker-compose logs` to view the logs of a specific service.
- Use the `docker-compose down` command to stop and remove all containers, networks, and volumes associated with the application.

## Task 2

- Learn how to use Docker Volumes and Named Volumes to share files and directories between multiple containers.
- Create two or more containers that read and write data to the same volume using the `docker run --mount` command.
- Verify that the data is the same in all containers by using the `docker exec` command to run commands inside each container.
- Use the `docker volume ls` command to list all volumes and the `docker volume rm` command to remove the volume when you're done.

## Project Opportunity

You can use this task as a project to add to your resume.

You can post on LinkedIn and let us know what you have learned from this task by using #90DaysOfDevOps Challenge. Happy Learning! 🙂

[← Previous Day](../day18/README.md) | [Next Day →](../day20/README.md)



# Day 20 Task: Docker for DevOps Engineers

## Finally!! 🎉

You have completed ✅ the Docker hands-on sessions, and I hope you have learned something valuable from it. 🙌

Now it's time to take your Docker skills to the next level by creating a comprehensive cheat-sheet of all the commands you've learned so far. This cheat-sheet should include commands for both Docker and Docker Compose, along with brief explanations of their usage. Not only will this cheat-sheet help you in the future, but it will also serve as a valuable resource for the DevOps community. 😊🙌

So, put your knowledge and creativity to the test and create a cheat-sheet that truly stands out! 🚀

For reference, I have added a [cheatsheet](https://cdn.hashnode.com/res/hashnode/image/upload/v1670863735841/r6xdXpsap.png?auto=compress,format&format=webp). Make sure your cheat-sheet is UNIQUE.

Post it on LinkedIn and share your knowledge with the community. 😃

**Happy Learning :)**

[← Previous Day](../day19/README.md) | [Next Day →](../day21/README.md)



# Day 21 Task: Important Docker Interview Questions

## Docker Interview

Docker is a crucial topic for DevOps Engineer interviews, especially for freshers. Here are some essential questions to help you prepare and ace your Docker interviews:

## Questions

- What is the difference between an Image, Container, and Engine?
- What is the difference between the Docker command COPY vs ADD?
- What is the difference between the Docker command CMD vs RUN?
- How will you reduce the size of a Docker image?
- Why and when should you use Docker?
- Explain the Docker components and how they interact with each other.
- Explain the terminology: Docker Compose, Dockerfile, Docker Image, Docker Container.
- In what real scenarios have you used Docker?
- Docker vs Hypervisor?
- What are the advantages and disadvantages of using Docker?
- What is a Docker namespace?
- What is a Docker registry?
- What is an entry point?
- How to implement CI/CD in Docker?
- Will data on the container be lost when the Docker container exits?
- What is a Docker swarm?
- What are the Docker commands for the following:
  - Viewing running containers
  - Running a container under a specific name
  - Exporting a Docker image
  - Importing an existing Docker image
  - Deleting a container
  - Removing all stopped containers, unused networks, build caches, and dangling images?
- What are the common Docker practices to reduce the size of Docker images?
- How do you troubleshoot a Docker container that is not starting?
- Can you explain the Docker networking model?
- How do you manage persistent storage in Docker?
- How do you secure a Docker container?
- What is Docker overlay networking?
- How do you handle environment variables in Docker?

These questions will help you in your next DevOps interview. Write a blog and share it on LinkedIn to showcase your knowledge.

**Happy Learning :)**

[← Previous Day](../day20/README.md) | [Next Day →](../day22/README.md)



# Day-22 : Getting Started with Jenkins 😃
**Linux, Git, Git-Hub, Docker finish ho chuka hai to chaliye seekhte hai inko deploy krne ke lye CI-CD tool:**

## What is Jenkins?
- Jenkins is an open source continuous integration-continuous delivery and deployment (CI/CD) automation software DevOps tool written in the Java programming language. It is used to implement CI/CD workflows, called pipelines.

- Jenkins is a tool that is used for automation, and it is an open-source server that allows all the developers to build, test and deploy software. It works or runs on java as it is written in java. By using Jenkins we can make a continuous integration of projects(jobs) or end-to-endpoint automation.

- Jenkins achieves Continuous Integration with the help of plugins. Plugins allow the integration of Various DevOps stages. If you want to integrate a particular tool, you need to install the plugins for that tool. For example Git, Maven 2 project, Amazon EC2, HTML publisher etc.

### Let us do discuss the necessity of this tool before going ahead to the procedural part for installation:

- Nowadays, humans are becoming lazy😴 day by day so even having digital screens and just one click button in front of us then also need some automation.

- Here, I’m referring to that part of automation where we need not have to look upon a process(here called a job) for completion and after it doing another job. For that, we have Jenkins with us.

Note: By now Jenkins should be installed on your machine(as it was a part of previous tasks, if not follow [Installation Guide](https://youtu.be/OkVtBKqMt7I))

## Tasks:

### Task 1: Write a small article in your own words about 
- what Jenkins is and why it is used. Avoid copying directly from the internet. 
- Reflect on how Jenkins integrates into the DevOps lifecycle and its benefits.
- Discuss the role of Jenkins in automating the build, test, and deployment processes.

### Task 2: Create a Freestyle Pipeline to Print "Hello World"

Create a freestyle pipeline in Jenkins that:
- Prints "Hello World"
- Prints the current date and time
- Clones a GitHub repository and lists its contents
- Configure the pipeline to run periodically (e.g., every hour).

### Share Your Progress

Don't forget to post your progress on LinkedIn to share your learning journey with others. Happy learning and good luck with your DevOps challenge!

[← Previous Day](../day21/README.md) | [Next Day →](../day23/README.md)



# Day 23 Task: Jenkins Freestyle Project for DevOps Engineers

The community is absolutely crushing it in the #90daysofdevops journey. Today's challenge is particularly exciting as it involves creating a Jenkins Freestyle Project, an excellent opportunity for DevOps engineers to showcase their skills and push their limits. Who's ready to dive in and make it happen? 😍

## What is CI/CD?

- **CI (Continuous Integration)** is the practice of automating the integration of code changes from multiple developers into a single codebase. It involves developers frequently committing their work into a central code repository (such as GitHub or Stash). Automated tools then build the newly committed code and perform tasks like code review, ensuring that the code is integrated smoothly. The key goals of Continuous Integration are to find and address bugs quickly, make the integration process easier across a team of developers, improve software quality, and reduce the time it takes to release new features.

- **CD (Continuous Delivery)** follows Continuous Integration and ensures that new changes can be released to customers quickly and without errors. This includes running integration and regression tests in a staging environment (similar to production) to ensure the final release is stable. Continuous Delivery automates the release process, ensuring a release-ready product at all times and allowing deployment at any moment.

## What Is a Build Job?

A Jenkins build job contains the configuration for automating specific tasks or steps in the application building process. These tasks include gathering dependencies, compiling, archiving, transforming code, testing, and deploying code in different environments.

Jenkins supports several types of build jobs, such as freestyle projects, pipelines, multi-configuration projects, folders, multibranch pipelines, and organization folders.

## What is a Freestyle Project? 🤔

A freestyle project in Jenkins is a type of project that allows you to build, test, and deploy software using various options and configurations. Here are a few tasks you could complete with a freestyle project in Jenkins:

### Task 1

- Create an agent for your app (which you deployed using Docker in a previous task).
- Create a new Jenkins freestyle project for your app.
- In the "Build" section of the project, add a build step to run the `docker build` command to build the image for the container.
- Add a second step to run the `docker run` command to start a container using the image created in the previous step.

### Task 2

- Create a Jenkins project to run the `docker-compose up -d` command to start multiple containers defined in the compose file (Hint: use the application and database docker-compose file from Day 19).
- Set up a cleanup step in the Jenkins project to run the `docker-compose down` command to stop and remove the containers defined in the compose file.

For reference on Jenkins Freestyle Projects, visit [here](https://youtu.be/wwNWgG5htxs).

You can post on LinkedIn and let us know what you have learned from this task as part of the #90DaysOfDevOps Challenge.

**Happy Learning :)**

[← Previous Day](../day22/README.md) | [Next Day →](../day24/README.md)



# Day 24 Task: Complete Jenkins CI/CD Project

Let's create a comprehensive CI/CD pipeline for your Node.js application! 😍

## Did you finish Day 23?

- Day 23 focused on Jenkins CI/CD, ensuring you understood the basics. Today, you'll take it a step further by completing a full project from start to finish, which you can proudly add to your resume. 
- As you've already worked with Docker and Docker Compose, you'll be integrating these tools into a live project.

## Task 1

1. Fork [this repository](https://github.com/LondheShubham153/node-todo-cicd.git).
2. Set up a connection between your Jenkins job and your GitHub repository through GitHub Integration.
3. Learn about [GitHub WebHooks](https://betterprogramming.pub/how-too-add-github-webhook-to-a-jenkins-pipeline-62b0be84e006) and ensure you have the CI/CD setup configured.
4. Refer to [this video](https://youtu.be/nplH3BzKHPk) for a step-by-step guide on the entire project.

## Task 2

1. In the "Execute Shell" section of your Jenkins job, run the application using Docker Compose.
2. Create a Docker Compose file for this project (a valuable open-source contribution).
3. Run the project and celebrate your accomplishment! 🎉

For a detailed walkthrough and hands-on experience with the project, visit [this video](https://youtu.be/nplH3BzKHPk).

You can post on LinkedIn and share your experiences and learnings from this task using the #90DaysOfDevOps Challenge.

**Happy Learning :)**

[← Previous Day](../day23/README.md) | [Next Day →](../day25/README.md)



# Day 25 Task: Complete Jenkins CI/CD Project - Continued with Documentation

You've been making amazing progress, so let's take a moment to catch up and refine our work. Today's focus is on completing the Jenkins CI/CD project from Day 24 and creating thorough documentation for it.

## Did you finish Day 24?

- Day 24 provided an end-to-end project experience, and adding this to your resume will be a significant achievement.

- Take your time to finish the project, create comprehensive documentation, and make sure to highlight it in your resume and share your experience.

## Task 1

- Document the entire process from cloning the repository to adding webhooks, deployment, and more. Create a detailed README file for your project. You can refer to [this example](https://github.com/LondheShubham153/fynd-my-movie/blob/master/README.md) for inspiration.

- A well-written README file will not only help others understand your project but also make it easier for you to revisit and use the project in the future.

## Task 2

- As it's a lighter day, set a small goal for yourself. Consider something you've been meaning to accomplish and use this time to focus on it.

- Share your goal and how you plan to achieve it using [this template](https://www.linkedin.com/posts/shubhamlondhe1996_taking-resolutions-and-having-goals-for-an-activity-7023858409762373632-s2J8?utm_source=share&utm_medium=member_desktop).

- Having small, achievable goals and strategies for reaching them is essential. Don't forget to reward yourself for your efforts!

For a detailed walkthrough and project guidance, visit [this video](https://youtu.be/nplH3BzKHPk).

You can post on LinkedIn and let us know what you have learned from this task using the #90DaysOfDevOps Challenge.

**Happy Learning :)**

[← Previous Day](../day24/README.md) | [Next Day →](../day26/README.md)



# Day 26 Task: Jenkins Declarative Pipeline

One of the most important parts of your DevOps and CICD journey is a Declarative Pipeline Syntax of Jenkins

## Some terms for your Knowledge

**What is Pipeline -** A pipeline is a collection of steps or jobs interlinked in a sequence.

**Declarative:** Declarative is a more recent and advanced implementation of a pipeline as a code.

**Scripted:** Scripted was the first and most traditional implementation of the pipeline as a code in Jenkins. It was designed as a general-purpose DSL (Domain Specific Language) built with Groovy.

# Why you should have a Pipeline

The definition of a Jenkins Pipeline is written into a text file (called a [`Jenkinsfile`](https://www.jenkins.io/doc/book/pipeline/jenkinsfile)) which in turn can be committed to a project’s source control repository.  
This is the foundation of "Pipeline-as-code"; treating the CD pipeline as a part of the application to be versioned and reviewed like any other code.

**Creating a `Jenkinsfile` and committing it to source control provides a number of immediate benefits:**

- Automatically creates a Pipeline build process for all branches and pull requests.
- Code review/iteration on the Pipeline (along with the remaining source code).

# Pipeline syntax

```groovy
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                //
            }
        }
        stage('Test') {
            steps {
                //
            }
        }
        stage('Deploy') {
            steps {
                //
            }
        }
    }
}
```

# Task-01

- Create a New Job, this time select Pipeline instead of Freestyle Project.
- Follow the Official Jenkins [Hello world example](https://www.jenkins.io/doc/pipeline/tour/hello-world/)
- Complete the example using the Declarative pipeline
- In case of any issues feel free to post on any Groups, [Discord](https://discord.gg/Q6ntmMtH) or [Telegram](https://t.me/trainwithshubham)

You can post your progress on LinkedIn and let us know what you have learned from this task by #90DaysOfDevOps Challenge.

Happy Learning:)

[← Previous Day](../day25/README.md) | [Next Day →](../day27/README.md)



# Day 27 Task: Jenkins Declarative Pipeline with Docker

Day 26 was all about a Declarative pipeline, now its time to level up things, let's integrate Docker and your Jenkins declarative pipeline

## Use your Docker Build and Run Knowledge

**docker build -** you can use `sh 'docker build . -t <tag>' ` in your pipeline stage block to run the docker build command. (Make sure you have docker installed with correct permissions.

**docker run:** you can use `sh 'docker run -d  <image>'` in your pipeline stage block to build the container.

**How will the stages look**

```groovy
stages {
        stage('Build') {
            steps {
                sh 'docker build -t trainwithshubham/django-app:latest'
            }
        }
    }
```

# Task-01

- Create a docker-integrated Jenkins declarative pipeline
- Use the above-given syntax using `sh` inside the stage block
- You will face errors in case of running a job twice, as the docker container will be already created, so for that do task 2

# Task-02

- Create a docker-integrated Jenkins declarative pipeline using the `docker` groovy syntax inside the stage block.
- You won't face errors, you can Follow [this documentation](https://tempora-mutantur.github.io/jenkins.io/github_pages_test/doc/book/pipeline/docker/)

- Complete your previous projects using this Declarative pipeline approach

- In case of any issues feel free to post on any Groups, [Discord](https://discord.gg/Q6ntmMtH) or [Telegram](https://t.me/trainwithshubham)

Are you enjoying the #90DaysOfDevOps Challenge?
Let me know how are feeling after 4 weeks of DevOps Learnings,

Happy Learning:)

[← Previous Day](../day26/README.md) | [Next Day →](../day28/README.md)



# Day 28 Task: Jenkins Agents

## Jenkins Master (Server)

The Jenkins master server is the central control unit that manages the overall orchestration of workflows defined in pipelines. It handles tasks such as scheduling jobs, monitoring job status, and managing configurations. The master serves the Jenkins UI and acts as the control node, delegating job execution to agents.

## Jenkins Agent

A Jenkins agent is a separate machine or container that executes the tasks defined in Jenkins jobs. When a job is triggered on the master, the actual execution occurs on the assigned agent. Each agent is identified by a unique label, allowing the master to delegate jobs to the appropriate agent.

For small teams or projects, a single Jenkins installation may suffice. However, as the number of projects grows, it becomes necessary to scale. Jenkins supports this by allowing a master to connect with multiple agents, enabling distributed job execution.

<p align="center"><img align="center" src="https://user-images.githubusercontent.com/115981550/215276859-fa140ab7-e905-41c9-8ae2-1eef577c5e72.png" /></p>

## Pre-requisites

To set up an agent, you'll need a fresh Ubuntu 22.04 Linux installation. Ensure Java (the same version as on the Jenkins master server) and Docker are installed on the agent machine.

*Note: While creating an agent, ensure that permissions, rights, and ownership are appropriately set for Jenkins users.*

## Task 01

1. **Create an Agent:**
   - Set up a new node in Jenkins by creating an agent.

2. **AWS EC2 Instance Setup:**
   - Create a new AWS EC2 instance and connect it to the master (where Jenkins is installed).

3. **Master-Agent Connection:**
   - Establish a connection between the master and agent using SSH and a public-private key pair exchange.
   - Verify the agent's status in the "Nodes" section.

   You can follow [this article](https://www.linkedin.com/posts/chetanrakhra_devops-project-share-activity-7017885886461698048-os5f?utm_source=share&utm_medium=member_android) for detailed instructions.

## Task 02

1. **Run Previous Jobs on the New Agent:**
   - Use the agent to run the Jenkins jobs you built on Day 26 and Day 27.

2. **Labeling:**
   - Assign labels to the agent and configure your master server to trigger builds on the appropriate agent based on these labels.

3. **Support:**
   - If you encounter any issues, feel free to seek help on [Discord](https://discord.gg/Q6ntmMtH) or [Telegram](https://t.me/trainwithshubham).

## Reflection

Are you enjoying the #90DaysOfDevOps Challenge? Share your thoughts and experiences after four weeks of learning DevOps.

**Happy Learning! :)**

[← Previous Day](../day27/README.md) | [Next Day →](../day29/README.md)



## Day 29 Task: Jenkins Important Interview Questions

<p align="center"><img align="center" src="https://user-images.githubusercontent.com/115981550/215283081-1c77ac18-4825-49d1-8727-7f0940846fff.png" /></p>

## Jenkins Interview

Here are some Jenkins-specific questions related to Docker and other DevOps concepts that can be useful during a DevOps Engineer interview:

### General Questions

1. **What’s the difference between continuous integration, continuous delivery, and continuous deployment?**
2. **Benefits of CI/CD.**
3. **What is meant by CI-CD?**
4. **What is Jenkins Pipeline?**
5. **How do you configure a job in Jenkins?**
6. **Where do you find errors in Jenkins?**
7. **In Jenkins, how can you find log files?**
8. **Jenkins workflow and write a script for this workflow?**
9. **How to create continuous deployment in Jenkins?**
10. **How to build a job in Jenkins?**
11. **Why do we use pipelines in Jenkins?**
12. **Is Jenkins alone sufficient for automation?**
13. **How will you handle secrets in Jenkins?**
14. **Explain the different stages in a CI-CD setup.**
15. **Name some of the plugins in Jenkins.**

### Scenario-Based Questions

1. **You have a Jenkins pipeline that deploys to a staging environment. Suddenly, the deployment failed due to a missing configuration file. How would you troubleshoot and resolve this issue?**
2. **Imagine you have a Jenkins job that is taking significantly longer to complete than expected. What steps would you take to identify and mitigate the issue?**
3. **You need to implement a secure method to manage environment-specific secrets for different stages (development, staging, production) in your Jenkins pipeline. How would you approach this?**
4. **Suppose your Jenkins master node is under heavy load and build times are increasing. What strategies can you use to distribute the load and ensure efficient build processing?**
5. **A developer commits a code change that breaks the build. How would you set up Jenkins to automatically handle such scenarios and notify the relevant team members?**
6. **You are tasked with setting up a Jenkins pipeline for a multi-branch project. How would you handle different configurations and build steps for different branches?**
7. **How would you implement a rollback strategy in a Jenkins pipeline to revert to a previous stable version if the deployment fails?**
8. **In a scenario where you have multiple teams working on different projects, how would you structure Jenkins jobs and pipelines to ensure efficient resource utilization and manage permissions?**
9. **Your Jenkins agents are running in a cloud environment, and you notice that build times fluctuate due to varying resource availability. How would you optimize the performance and cost of these agents?**

These questions will help you prepare for your next DevOps interview. Consider writing a blog and sharing your experiences and knowledge on LinkedIn.

**Happy Learning! :)**

[← Previous Day](../day28/README.md) | [Next Day →](../day30/README.md)



## Day 30 Task: Kubernetes Architecture

<p  align="center"><img  align="center"  src="https://kubernetes.io/images/kubernetes-horizontal-color.png"  /></p>

## Kubernetes Overview

With the widespread adoption of [containers](https://cloud.google.com/containers) among organizations, Kubernetes, the container-centric management software, has become a standard to deploy and operate containerized applications and is one of the most important parts of DevOps.

Originally developed at Google and released as open-source in 2014. Kubernetes builds on 15 years of running Google's containerized workloads and the valuable contributions from the open-source community. Inspired by Google’s internal cluster management system, [Borg](https://research.google.com/pubs/pub43438.html),

## Tasks

1. What is Kubernetes? Write in your own words and why do we call it k8s?

2. What are the benefits of using k8s?

3. Explain the architecture of Kubernetes, refer to [this video](https://youtu.be/FqfoDUhzyDo)

4. What is Control Plane?

5. Write the difference between kubectl and kubelets.

6. Explain the role of the API server.

Kubernetes architecture is important, so make sure you spend a day understanding it. [This video](https://youtu.be/FqfoDUhzyDo) will surely help you.

_Happy Learning :)_

[← Previous Day](../day29/README.md) | [Next Day →](../day31/README.md)



## Day 31 Task: Launching your First Kubernetes Cluster with Nginx running

### Awesome! You learned the architecture of one of the top most important tool "Kubernetes" in your previous task.

## What about doing some hands-on now?

Let's read about minikube and implement _k8s_ in our local machine

1. **What is minikube?**

_Ans_:- Minikube is a tool which quickly sets up a local Kubernetes cluster on macOS, Linux, and Windows. It can deploy as a VM, a container, or on bare-metal.

Minikube is a pared-down version of Kubernetes that gives you all the benefits of Kubernetes with a lot less effort.

This makes it an interesting option for users who are new to containers, and also for projects in the world of edge computing and the Internet of Things.

2. **Features of minikube**

_Ans_ :-

(a) Supports the latest Kubernetes release (+6 previous minor versions)

(b) Cross-platform (Linux, macOS, Windows)

(c) Deploy as a VM, a container, or on bare-metal

(d) Multiple container runtimes (CRI-O, containerd, docker)

(e) Direct API endpoint for blazing fast image load and build

(f) Advanced features such as LoadBalancer, filesystem mounts, FeatureGates, and network policy

(g) Addons for easily installed Kubernetes applications

(h) Supports common CI environments

## Task-01:

## Install minikube on your local

For installation, you can Visit [this page](https://minikube.sigs.k8s.io/docs/start/).

If you want to try an alternative way, you can check [this](https://k8s-docs.netlify.app/en/docs/tasks/tools/install-minikube/).

## Let's understand the concept **pod**

_Ans:-_

Pods are the smallest deployable units of computing that you can create and manage in Kubernetes.

A Pod (as in a pod of whales or pea pod) is a group of one or more containers, with shared storage and network resources, and a specification for how to run the containers. A Pod's contents are always co-located and co-scheduled, and run in a shared context. A Pod models an application-specific "logical host": it contains one or more application containers which are relatively tightly coupled.

You can read more about pod from [here](https://kubernetes.io/docs/concepts/workloads/pods/) .

## Task-02:

## Create your first pod on Kubernetes through minikube.

We are suggesting you make an nginx pod, but you can always show your creativity and do it on your own.

**Having an issue? Don't worry, adding a sample yaml file for pod creation, you can always refer that.**

_Happy Learning :)_

[← Previous Day](../day30/README.md) | [Next Day →](../day32/README.md)



## Day 32 Task: Launching your Kubernetes Cluster with Deployment

### Congratulation ! on your learning on K8s on Day-31

## What is Deployment in k8s

A Deployment provides a configuration for updates for Pods and ReplicaSets.

You describe a desired state in a Deployment, and the Deployment Controller changes the actual state to the desired state at a controlled rate. You can define Deployments to create new replicas for scaling, or to remove existing Deployments and adopt all their resources with new Deployments.

## Today's task let's keep it very simple.

## Task-1:

**Create one Deployment file to deploy a sample todo-app on K8s using "Auto-healing" and "Auto-Scaling" feature**

- add a deployment.yml file (sample is kept in the folder for your reference)
- apply the deployment to your k8s (minikube) cluster by command
  `kubectl apply -f deployment.yml`

Let's make your resume shine with one more project ;)

**Having an issue? Don't worry, adding a sample deployment file , you can always refer that or wathch [this video](https://youtu.be/ONrbWFJXLLk)**

Happy Learning :)

[← Previous Day](../day31/README.md) | [Next Day →](../day33/README.md)



# Day 33 Task: Working with Namespaces and Services in Kubernetes

### Congrats🎊🎉 on updating your Deployment yesterday💥🙌

## What are Namespaces and Services in k8s

In Kubernetes, Namespaces are used to create isolated environments for resources. Each Namespace is like a separate cluster within the same physical cluster. Services are used to expose your Pods and Deployments to the network. Read more about Namespace [Here](https://kubernetes.io/docs/concepts/workloads/pods/user-namespaces/)

# Today's task:

## Task 1:

- Create a Namespace for your Deployment

- Use the command `kubectl create namespace <namespace-name>` to create a Namespace

- Update the deployment.yml file to include the Namespace

- Apply the updated deployment using the command:
  `kubectl apply -f deployment.yml -n <namespace-name>`

- Verify that the Namespace has been created by checking the status of the Namespaces in your cluster.

## Task 2:

- Read about Services, Load Balancing, and Networking in Kubernetes. Refer official documentation of kubernetes [Link](https://kubernetes.io/docs/concepts/services-networking/)

Need help with Namespaces? Check out this [video](https://youtu.be/K3jNo4z5Jx8) for assistance.

Keep growing your Kubernetes knowledge💥🙌

Happy Learning! :)

[← Previous Day](../day32/README.md) | [Next Day →](../day34/README.md)



# Day 34 Task: Working with Services in Kubernetes

### Congratulation🎊 on your learning on Deployments in K8s on Day-33

## What are Services in K8s

In Kubernetes, Services are objects that provide stable network identities to Pods and abstract away the details of Pod IP addresses. Services allow Pods to receive traffic from other Pods, Services, and external clients.

## Task-1:

- Create a Service for your todo-app Deployment from Day-32
- Create a Service definition for your todo-app Deployment in a YAML file.
- Apply the Service definition to your K8s (minikube) cluster using the `kubectl apply -f service.yml -n <namespace-name>` command.
- Verify that the Service is working by accessing the todo-app using the Service's IP and Port in your Namespace.

## Task-2:

- Create a ClusterIP Service for accessing the todo-app from within the cluster
- Create a ClusterIP Service definition for your todo-app Deployment in a YAML file.
- Apply the ClusterIP Service definition to your K8s (minikube) cluster using the `kubectl apply -f cluster-ip-service.yml -n <namespace-name>` command.
- Verify that the ClusterIP Service is working by accessing the todo-app from another Pod in the cluster in your Namespace.

## Task-3:

- Create a LoadBalancer Service for accessing the todo-app from outside the cluster
- Create a LoadBalancer Service definition for your todo-app Deployment in a YAML file.
- Apply the LoadBalancer Service definition to your K8s (minikube) cluster using the `kubectl apply -f load-balancer-service.yml -n <namespace-name>` command.
- Verify that the LoadBalancer Service is working by accessing the todo-app from outside the cluster in your Namespace.

Struggling with Services? Take a look at this video for a step-by-step [guide](https://youtu.be/OJths_RojFA).

Need help with Services in Kubernetes? Check out the Kubernetes [documentation](https://kubernetes.io/docs/concepts/services-networking/service/) for assistance.

Happy Learning :)

[← Previous Day](../day33/README.md) | [Next Day →](../day35/README.md)



# Day 35: Mastering ConfigMaps and Secrets in Kubernetes🔒🔑🛡️

### 👏🎉 Yay! Yesterday we conquered Namespaces and Services 💪💻🔗🚀

## What are ConfigMaps and Secrets in k8s

In Kubernetes, ConfigMaps and Secrets are used to store configuration data and secrets, respectively. ConfigMaps store configuration data as key-value pairs, while Secrets store sensitive data in an encrypted form.

- _Example :- Imagine you're in charge of a big spaceship (Kubernetes cluster) with lots of different parts (containers) that need information to function properly.
  ConfigMaps are like a file cabinet where you store all the information each part needs in simple, labeled folders (key-value pairs).
  Secrets, on the other hand, are like a safe where you keep the important, sensitive information that shouldn't be accessible to just anyone (encrypted data).
  So, using ConfigMaps and Secrets, you can ensure each part of your spaceship (Kubernetes cluster) has the information it needs to work properly and keep sensitive information secure! 🚀_
- Read more about [ConfigMap](https://kubernetes.io/docs/concepts/configuration/configmap/) & [Secret](https://kubernetes.io/docs/concepts/configuration/secret/).

## Today's task:

## Task 1:

- Create a ConfigMap for your Deployment
- Create a ConfigMap for your Deployment using a file or the command line
- Update the deployment.yml file to include the ConfigMap
- Apply the updated deployment using the command: `kubectl apply -f deployment.yml -n <namespace-name>`
- Verify that the ConfigMap has been created by checking the status of the ConfigMaps in your Namespace.

## Task 2:

- Create a Secret for your Deployment
- Create a Secret for your Deployment using a file or the command line
- Update the deployment.yml file to include the Secret
- Apply the updated deployment using the command: `kubectl apply -f deployment.yml -n <namespace-name>`
- Verify that the Secret has been created by checking the status of the Secrets in your Namespace.

Need help with ConfigMaps and Secrets? Check out this [video](https://youtu.be/FAnQTgr04mU) for assistance.

Keep learning and expanding your knowledge of Kubernetes💥🙌

[← Previous Day](../day34/README.md) | [Next Day →](../day36/README.md)



# Day 36 Task: Managing Persistent Volumes in Your Deployment 💥

🙌 Kudos to you for conquering ConfigMaps and Secrets in Kubernetes yesterday.

🔥 You're on fire! 🔥

## What are Persistent Volumes in k8s

In Kubernetes, a Persistent Volume (PV) is a piece of storage in the cluster that has been provisioned by an administrator. A Persistent Volume Claim (PVC) is a request for storage by a user. The PVC references the PV, and the PV is bound to a specific node. Read official documentation of [Persistent Volumes](https://kubernetes.io/docs/concepts/storage/persistent-volumes/).

⏰ Wait, wait, wait! 📣 Attention all #90daysofDevOps Challengers. 💪

Before diving into today's task, don't forget to share your thoughts on the #90daysofDevOps challenge 💪 Fill out our feedback form (https://lnkd.in/gcgvrq8b) to help us improve and provide the best experience 🌟 Your participation and support is greatly appreciated 🙏 Let's continue to grow together 🌱

## Today's tasks:

### Task 1:

Add a Persistent Volume to your Deployment todo app.

- Create a Persistent Volume using a file on your node. [Template](https://github.com/LondheShubham153/90DaysOfDevOps/blob/94e3970819e097a5b8edea40fe565d583419f912/2023/day36/pv.yml)

- Create a Persistent Volume Claim that references the Persistent Volume. [Template](https://github.com/LondheShubham153/90DaysOfDevOps/blob/94e3970819e097a5b8edea40fe565d583419f912/2023/day36/pvc.yml)

- Update your deployment.yml file to include the Persistent Volume Claim. After Applying pv.yml pvc.yml your deployment file look like this [Template](https://github.com/LondheShubham153/90DaysOfDevOps/blob/94e3970819e097a5b8edea40fe565d583419f912/2023/day36/Deployment.yml)

- Apply the updated deployment using the command: `kubectl apply -f deployment.yml`

- Verify that the Persistent Volume has been added to your Deployment by checking the status of the Pods and Persistent Volumes in your cluster. Use this commands `kubectl get pods` ,

`kubectl get pv`

⚠️ Don't forget: To apply changes or create files in your Kubernetes deployments, each file must be applied separately. ⚠️

### Task 2:

Accessing data in the Persistent Volume,

- Connect to a Pod in your Deployment using command : `kubectl exec -it <pod-name> -- /bin/bash

`

- Verify that you can access the data stored in the Persistent Volume from within the Pod

Need help with Persistent Volumes? Check out this [video](https://youtu.be/U0_N3v7vJys) for assistance.

Keep up the excellent work🙌💥

Happy Learning :)

[← Previous Day](../day35/README.md) | [Next Day →](../day37/README.md)



## Day 37 Task: Kubernetes Important interview Questions.

## Questions

1.What is Kubernetes and why it is important?

2.What is difference between docker swarm and kubernetes?

3.How does Kubernetes handle network communication between containers?

4.How does Kubernetes handle scaling of applications?

5.What is a Kubernetes Deployment and how does it differ from a ReplicaSet?

6.Can you explain the concept of rolling updates in Kubernetes?

7.How does Kubernetes handle network security and access control?

8.Can you give an example of how Kubernetes can be used to deploy a highly available application?

9.What is namespace is kubernetes? Which namespace any pod takes if we don't specify any namespace?

10.How ingress helps in kubernetes?

11.Explain different types of services in kubernetes?

12.Can you explain the concept of self-healing in Kubernetes and give examples of how it works?

13.How does Kubernetes handle storage management for containers?

14.How does the NodePort service work?

15.What is a multinode cluster and single-node cluster in Kubernetes?

16.Difference between create and apply in kubernetes?

## These questions will help you in your next DevOps Interview.

_Write a Blog and share it on LinkedIn._

**_Happy Learning :)_**

[← Previous Day](../day36/README.md) | [Next Day →](../day38/README.md)



# Day 38 Getting Started with AWS Basics☁

![AWS](https://user-images.githubusercontent.com/115981550/217238286-6c6bc6e7-a1ac-4d12-98f3-f95ff5bf53fc.png)

Congratulations!!!! you have come so far. Don't let your excuses break your consistency. Let's begin our new Journey with Cloud☁. By this time you have created multiple EC2 instances, if not let's begin the journey:

## AWS:

Amazon Web Services is one of the most popular Cloud Provider that has free tier too for students and Cloud enthutiasts for their Handson while learning (Create your free account today to explore more on it).

Read from [here](https://aws.amazon.com/what-is-aws/)

## IAM:

AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can centrally manage permissions that control which AWS resources users can access. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.
Read from [here](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)

Get to know IAM more deeply [Click Here!!](https://www.youtube.com/watch?v=ORB4eY8EydA)

### Task1:

Create an IAM user with username of your own wish and grant EC2 Access. Launch your Linux instance through the IAM user that you created now and install jenkins and docker on your machine via single Shell Script.

### Task2:

In this task you need to prepare a devops team of avengers. Create 3 IAM users of avengers and assign them in devops groups with IAM policy.

Post your progress on Linkedin. Till then Happy Learning :)

[← Previous Day](../day37/README.md) | [Next Day →](../day39/README.md)



# Day 39 AWS and IAM Basics☁

![AWS](https://miro.medium.com/max/1400/0*dIzXLQn6aBClm1TJ.png)

By this time you have created multiple EC2 instances, and post installation manually installed applications like Jenkins, docker etc.
Now let's switch to little automation part. Sounds interesting??🤯

## AWS:

Amazon Web Services is one of the most popular Cloud Provider that has free tier too for students and Cloud enthutiasts for their Handson while learning (Create your free account today to explore more on it).

Read from [here](https://aws.amazon.com/what-is-aws/)

## User Data in AWS:

- When you launch an instance in Amazon EC2, you have the option of passing user data to the instance that can be used to perform common automated configuration tasks and even run scripts after the instance starts. You can pass two types of user data to Amazon EC2: shell scripts and cloud-init directives.
- You can also pass this data into the launch instance wizard as plain text, as a file (this is useful for launching instances using the command line tools), or as base64-encoded text (for API calls).
- This will save time and manual effort everytime you launch an instance and want to install any application on it like apache, docker, Jenkins etc

Read more from [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/user-data.html)

## IAM:

AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can centrally manage permissions that control which AWS resources users can access. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.
Read from [here](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)

Get to know IAM more deeply🏊[Click Here!!](https://www.youtube.com/watch?v=ORB4eY8EydA)

### Task1:

- Launch EC2 instance with already installed Jenkins on it. Once server shows up in console, hit the IP address in browser and you Jenkins page should be visible.
- Take screenshot of Userdata and Jenkins page, this will verify the task completion.

### Task2:

- Read more on IAM Roles and explain the IAM Users, Groups and Roles in your own terms.
- Create three Roles named: DevOps-User, Test-User and Admin.

Post your progress on Linkedin. Till then Happy Learning :)

[← Previous Day](../day38/README.md) | [Next Day →](../day40/README.md)



# Day 40 AWS EC2 Automation ☁

![AWS](https://www.eginnovations.com/blog/wp-content/uploads/2021/09/Amazon-AWS-Cloud-Topimage-1.jpg)

I hope your journey with AWS cloud and automation is going well [](https://emojipedia.org/emoji/%F0%9F%98%8D/)

### 😍

## Automation in EC2:

Amazon EC2 or Amazon Elastic Compute Cloud can give you secure, reliable, high-performance, and cost-effective computing infrastructure to meet demanding business needs.

Also, if you know a few things, you can automate many things.

Read from [here](https://aws.amazon.com/ec2/)

## Launch template in AWS EC2:

- You can make a launch template with the configuration information you need to start an instance. You can save launch parameters in launch templates so you don't have to type them in every time you start a new instance.
- For example, a launch template can have the AMI ID, instance type, and network settings that you usually use to launch instances.
- You can tell the Amazon EC2 console to use a certain launch template when you start an instance.

Read more from [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-launch-templates.html)

## Instance Types:

Amazon EC2 has a large number of instance types that are optimised for different uses. The different combinations of CPU, memory, storage and networking capacity in instance types give you the freedom to choose the right mix of resources for your apps. Each instance type comes with one or more instance sizes, so you can adjust your resources to meet the needs of the workload you want to run.

Read from [here](https://aws.amazon.com/ec2/instance-types/?trk=32f4fbd0-ffda-4695-a60c-8857fab7d0dd&sc_channel=ps&s_kwcid=AL!4422!3!536392685920!e!!g!!ec2%20instance%20types&ef_id=CjwKCAiA0JKfBhBIEiwAPhZXD_O1-3qZkRa-KScynbwjvHd3l4UHSTfKuigd5ZPukXoDXu-v3MtC7hoCafEQAvD_BwE:G:s&s_kwcid=AL!4422!3!536392685920!e!!g!!ec2%20instance%20types)

## AMI:

An Amazon Machine Image (AMI) is an image that AWS supports and keeps up to date. It contains the information needed to start an instance. When you launch an instance, you must choose an AMI. When you need multiple instances with the same configuration, you can launch them from a single AMI.

### Task1:

- Create a launch template with Amazon Linux 2 AMI and t2.micro instance type with Jenkins and Docker setup (You can use the Day 39 User data script for installing the required tools.

- Create 3 Instances using Launch Template, there must be an option that shows number of instances to be launched ,can you find it? :)

- You can go one step ahead and create an auto-scaling group, sounds tough?

Check [this](https://docs.aws.amazon.com/autoscaling/ec2/userguide/create-launch-template.html#create-launch-template-for-auto-scaling) out

Post your progress on Linkedin.

Happy Learning :)

[← Previous Day](../day39/README.md) | [Next Day →](../day41/README.md)



# Day 41: Setting up an Application Load Balancer with AWS EC2 🚀 ☁

![LB2](https://user-images.githubusercontent.com/115981550/218145297-d55fe812-32b7-4242-a4f8-eb66312caa2c.png)

### Hi, I hope you had a great day yesterday learning about the launch template and instances in EC2. Today, we are going to dive into one of the most important concepts in EC2: Load Balancing.

## What is Load Balancing?

Load balancing is the distribution of workloads across multiple servers to ensure consistent and optimal resource utilization. It is an essential aspect of any large-scale and scalable computing system, as it helps you to improve the reliability and performance of your applications.

## Elastic Load Balancing:

**Elastic Load Balancing (ELB)** is a service provided by Amazon Web Services (AWS) that automatically distributes incoming traffic across multiple EC2 instances. ELB provides three types of load balancers:

Read more from [here](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html)

1. **Application Load Balancer (ALB)** - _operates at layer 7 of the OSI model and is ideal for applications that require advanced routing and microservices._

- Read more from [here](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html)

2. **Network Load Balancer (NLB)** - _operates at layer 4 of the OSI model and is ideal for applications that require high throughput and low latency._

- Read more from [here](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/introduction.html)

3. **Classic Load Balancer (CLB)** - _operates at layer 4 of the OSI model and is ideal for applications that require basic load balancing features._

- Read more [here](https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/introduction.html)

## 🎯 Today's Tasks:

### Task 1:

- launch 2 EC2 instances with an Ubuntu AMI and use User Data to install the Apache Web Server.
- Modify the index.html file to include your name so that when your Apache server is hosted, it will display your name also do it for 2nd instance which include " TrainWithShubham Community is Super Aweasome :) ".
- Copy the public IP address of your EC2 instances.
- Open a web browser and paste the public IP address into the address bar.
- You should see a webpage displaying information about your PHP installation.

### Task 2:

- Create an Application Load Balancer (ALB) in EC2 using the AWS Management Console.
- Add EC2 instances which you launch in task-1 to the ALB as target groups.
- Verify that the ALB is working properly by checking the health status of the target instances and testing the load balancing capabilities.

![LoadBalancer](https://user-images.githubusercontent.com/115981550/218143557-26ec33ce-99a7-4db6-a46f-1cf48ed77ae0.png)

Need help with task? Check out this [Blog for assistance](https://rushikesh-mashidkar.hashnode.dev/create-an-application-load-balancer-elastic-load-balancing-using-aws-ec2-instance).

Don't forget to share your progress on LinkedIn and have a great day🙌💥

Happy Learning! 😃

[← Previous Day](../day40/README.md) | [Next Day →](../day42/README.md)



# Day 42: IAM Programmatic access and AWS CLI 🚀 ☁

Today is more of a reading excercise and getting some programmatic access for your AWS account

## IAM Programmatic access

In order to access your AWS account from a terminal or system, you can use AWS Access keys and AWS Secret Access keys
Watch [this video](https://youtu.be/XYKqL5GFI-I) for more details.

## AWS CLI

The AWS Command Line Interface (AWS CLI) is a unified tool to manage your AWS services. With just one tool to download and configure, you can control multiple AWS services from the command line and automate them through scripts.

The AWS CLI v2 offers several new features including improved installers, new configuration options such as AWS IAM Identity Center (successor to AWS SSO), and various interactive features.

## Task-01

- Create AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY from AWS Console.

## Task-02

- Setup and install AWS CLI and configure your account credentials

Let me know if you have any issues while doing the task.

Happy Learning :)

[← Previous Day](../day41/README.md) | [Next Day →](../day43/README.md)



# Day 43: S3 Programmatic access with AWS-CLI 💻 📁

Hi, I hope you had a great day yesterday. Today as part of the #90DaysofDevOps Challenge we will be exploring most commonly used service in AWS i.e S3.

![s3](https://user-images.githubusercontent.com/115981550/218308379-a2e841cf-6b77-4d02-bfbe-20d1bae09b20.png)

# S3

Amazon Simple Storage Service (Amazon S3) is an object storage service that provides a secure and scalable way to store and access data on the cloud. It is designed for storing any kind of data, such as text files, images, videos, backups, and more.
Read more [here](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)

## Task-01

- Launch an EC2 instance using the AWS Management Console and connect to it using Secure Shell (SSH).
- Create an S3 bucket and upload a file to it using the AWS Management Console.
- Access the file from the EC2 instance using the AWS Command Line Interface (AWS CLI).

Read more about S3 using aws-cli [here](https://docs.aws.amazon.com/cli/latest/reference/s3/index.html)

## Task-02

- Create a snapshot of the EC2 instance and use it to launch a new EC2 instance.
- Download a file from the S3 bucket using the AWS CLI.
- Verify that the contents of the file are the same on both EC2 instances.

Added Some Useful commands to complete the task. [Click here for commands](https://github.com/LondheShubham153/90DaysOfDevOps/blob/833a67ac4ec17b992934cd6878875dccc4274f56/2023/day43/aws-cli.md)

Let me know if you have any questions or face any issues while doing the tasks.🚀

Happy Learning :)

[← Previous Day](../day42/README.md) | [Next Day →](../day44/README.md)



Here are some commonly used AWS CLI commands for Amazon S3:

`aws s3 ls` - This command lists all of the S3 buckets in your AWS account.

`aws s3 mb s3://bucket-name` - This command creates a new S3 bucket with the specified name.

`aws s3 rb s3://bucket-name` - This command deletes the specified S3 bucket.

`aws s3 cp file.txt s3://bucket-name` - This command uploads a file to an S3 bucket.

`aws s3 cp s3://bucket-name/file.txt .` - This command downloads a file from an S3 bucket to your local file system.

`aws s3 sync local-folder s3://bucket-name` - This command syncs the contents of a local folder with an S3 bucket.

`aws s3 ls s3://bucket-name` - This command lists the objects in an S3 bucket.

`aws s3 rm s3://bucket-name/file.txt` - This command deletes an object from an S3 bucket.

`aws s3 presign s3://bucket-name/file.txt` - This command generates a pre-signed URL for an S3 object, which can be used to grant temporary access to the object.

`aws s3api list-buckets` - This command retrieves a list of all S3 buckets in your AWS account, using the S3 API.



# Day 44: Relational Database Service in AWS

Amazon Relational Database Service (Amazon RDS) is a collection of managed services that makes it simple to set up, operate, and scale databases in the cloud

## Task-01

- Create a Free tier RDS instance of MySQL
- Create an EC2 instance
- Create an IAM role with RDS access
- Assign the role to EC2 so that your EC2 Instance can connect with RDS
- Once the RDS instance is up and running, get the credentials and connect your EC2 instance using a MySQL client.

Hint:

You should install mysql client on EC2, and connect the Host and Port of RDS with this client.

Post the screenshots once your EC2 instance can connect a MySQL server, that will be a small win for you.

Watch [this video](https://youtu.be/MrA6Rk1Y82E) for reference.

Happy Learning

[← Previous Day](../day43/README.md) | [Next Day →](../day45/README.md)



# Day 45: Deploy Wordpress website on AWS

Over 30% of all websites on the internet use WordPress as their content management system (CMS). It is most often used to run blogs, but it can also be used to run e-commerce sites, message boards, and many other popular things. This guide will show you how to set up a WordPress blog site.

## Task-01

- As WordPress requires a MySQL database to store its data ,create an RDS as you did in Day 44

To configure this WordPress site, you will create the following resources in AWS:

- An Amazon EC2 instance to install and host the WordPress application.
- An Amazon RDS for MySQL database to store your WordPress data.
- Setup the server and post your new Wordpress app.

Read [this](https://aws.amazon.com/getting-started/hands-on/deploy-wordpress-with-amazon-rds/) for a detailed explanation
Happy Learning :)

[← Previous Day](../day44/README.md) | [Next Day →](../day46/README.md)



# Day-46: Set up CloudWatch alarms and SNS topic in AWS

Hey learners, you have been using aws services atleast for last 45 days. Have you ever wondered what happen if for any service is charging you bill continously and you don't know till you loose all your pocket money ?

Hahahaha😁, Well! we, as a responsible community ,always try to make it under free tier , but it's good to know and setup something , which will inform you whenever bill touches a Threshold.

## What is Amazon CloudWatch?

Amazon CloudWatch monitors your Amazon Web Services (AWS) resources and the applications you run on AWS in real time. You can use CloudWatch to collect and track metrics, which are variables you can measure for your resources and applications.

Read more about cloudwatch from the official documentation [here](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)

## What is Amazon SNS?

Amazon Simple Notification Service is a notification service provided as part of Amazon Web Services since 2010. It provides a low-cost infrastructure for mass delivery of messages, predominantly to mobile users.

Read more about it [here](https://docs.aws.amazon.com/sns/latest/dg/welcome.html)

## Task :

- Create a CloudWatch alarm that monitors your billing and send an email to you when a it reaches $2.

(You can keep it for your future use)

- Delete your billing Alarm that you created now.

(Now you also know how to delete as well. )

Need help with Cloudwatch? Check out this [official documentation](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html) for assistance.

Keep growing your AWS knowledge💥🙌

Happy Learning! :)

[← Previous Day](../day45/README.md) | [Next Day →](../day47/README.md)



# Day 47: AWS Elastic Beanstalk
Today, we explore the new AWS service- Elastic Beanstalk. We'll also cover deploying a small web application (game) on this platform

## What is AWS Elastic Beanstalk?
![image](https://github.com/Simbaa815/90DaysOfDevOps/assets/112085387/75f69087-d769-4586-b4a7-99a87feaec92)

- AWS Elastic Beanstalk is a service used to deploy and scale web applications developed by developers.
- It supports multiple programming languages and runtime environments such as Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker.

## Why do we need AWS Elastic Beanstalk?
- Previously, developers faced challenges in sharing software modules across geographically separated teams.
- AWS Elastic Beanstalk solves this problem by providing a service to easily share applications across different devices.

## Advantages of AWS Elastic Beanstalk
- Highly scalable
- Fast and simple to begin
- Quick deployment
- Supports multi-tenant architecture
- Simplifies operations
- Cost efficient

## Components of AWS Elastic Beanstalk
- Application Version: Represents a specific iteration or release of an application's codebase.
- Environment Tier: Defines the infrastructure resources allocated for an environment (e.g., web server environment, worker environment).
- Environment: Represents a collection of AWS resources running an application version.
- Configuration Template: Defines the settings for an environment, including instance types, scaling options, and more.

## Elastic Beanstalk Environment 
There are two types of environments: <b>web server</b> and <b>worker</b>.

- <u>Web server environments</u> are front-end facing, accessed directly by clients using a URL.

- <u>Worker environments</u> support backend applications or micro apps.

## Task-01
Deploy the [2048-game](https://github.com/Simbaa815/2048-game) using the AWS Elastic Beanstalk.

If you ever find yourself facing a challenge, feel free to refer to this helpful [blog](https://devxblog.hashnode.dev/aws-elastic-beanstalk-deploying-the-2048-game) post for guidance and support.

---

# Additional work 

## Test Knowledge on aws 💻 📈
Today, we will be test the aws knowledge on services in AWS, as part of the 90 Days of DevOps Challenge.


## Task-01

- Launch an EC2 instance using the AWS Management Console and connect to it using SSH.
- Install a web server on the EC2 instance and deploy a simple web application.
- Monitor the EC2 instance using Amazon CloudWatch and troubleshoot any issues that arise.

## Task-02
- Create an Auto Scaling group using the AWS Management Console and configure it to launch EC2 instances in response to changes in demand.
- Use Amazon CloudWatch to monitor the performance of the Auto Scaling group and the EC2 instances and troubleshoot any issues that arise.
- Use the AWS CLI to view the state of the Auto Scaling group and the EC2 instances and verify that the correct number of instances are running.


We hope that these tasks will give you hands-on experience with aws services and help you understand how these services work together. If you have any questions or face any issues while doing the tasks, please let us know.

Happy Learning :)

[← Previous Day](../day46/README.md) | [Next Day →](../day48/README.md)



# Day-48 - ECS

Today will be a great learning for sure. I know many of you may not know about the term "ECS". As you know, 90 Days Of DevOps Challenge is mostly about 'learning new' , let's learn then ;)

## What is ECS ?

- ECS (Elastic Container Service) is a fully-managed container orchestration service provided by Amazon Web Services (AWS). It allows you to run and manage Docker containers on a cluster of virtual machines (EC2 instances) without having to manage the underlying infrastructure.

With ECS, you can easily deploy, manage, and scale your containerized applications using the AWS Management Console, the AWS CLI, or the API. ECS supports both "Fargate" and "EC2 launch types", which means you can run your containers on AWS-managed infrastructure or your own EC2 instances.

ECS also integrates with other AWS services, such as Elastic Load Balancing, Auto Scaling, and Amazon VPC, allowing you to build scalable and highly available applications. Additionally, ECS has support for Docker Compose and Kubernetes, making it easy to adopt existing container workflows.

Overall, ECS is a powerful and flexible container orchestration service that can help simplify the deployment and management of containerized applications in AWS.

## Difference between EKS and ECS ?

- EKS (Elastic Kubernetes Service) and ECS (Elastic Container Service) are both container orchestration platforms provided by Amazon Web Services (AWS). While both platforms allow you to run containerized applications in the AWS cloud, there are some differences between the two.

**Architecture**:
ECS is based on a centralized architecture, where there is a control plane that manages the scheduling of containers on EC2 instances. On the other hand, EKS is based on a distributed architecture, where the Kubernetes control plane is distributed across multiple EC2 instances.

**Kubernetes Support**:
EKS is a fully managed Kubernetes service, meaning that it supports Kubernetes natively and allows you to run your Kubernetes workloads on AWS without having to manage the Kubernetes control plane. ECS, on the other hand, has its own orchestration engine and does not support Kubernetes natively.

**Scaling**:
EKS is designed to automatically scale your Kubernetes cluster based on demand, whereas ECS requires you to configure scaling policies for your tasks and services.

**Flexibility**:
EKS provides more flexibility than ECS in terms of container orchestration, as it allows you to customize and configure Kubernetes to meet your specific requirements. ECS is more restrictive in terms of the options available for container orchestration.

**Community**:
Kubernetes has a large and active open-source community, which means that EKS benefits from a wide range of community-driven development and support. ECS, on the other hand, has a smaller community and is largely driven by AWS itself.

In summary, EKS is a good choice if you want to use Kubernetes to manage your containerized workloads on AWS, while ECS is a good choice if you want a simpler, more managed platform for running your containerized applications.

# Task :

Set up ECS (Elastic Container Service) by setting up Nginx on ECS.

[← Previous Day](../day47/README.md) | [Next Day →](../day49/README.md)



# Day 49 - INTERVIEW QUESTIONS ON AWS

Hey people, we have listened to your suggestions and we are looking forward to get more!
As you people have asked to put more interview based questions as part of Daily Task, So here it it :)

## INTERVIEW QUESTIONS:

- Name 5 aws services you have used and what's the use cases?
- What are the tools used to send logs to the cloud environment?
- What are IAM Roles? How do you create /manage them?
- How to upgrade or downgrade a system with zero downtime?
- What is infrastructure as code and how do you use it?
- What is a load balancer? Give scenarios of each kind of balancer based on your experience.
- What is CloudFormation and why is it used for?
- Difference between AWS CloudFormation and AWS Elastic Beanstalk?
- What are the kinds of security attacks that can occur on the cloud? And how can we minimize them?
- Can we recover the EC2 instance when we have lost the key?
- What is a gateway?
- What is the difference between the Amazon Rds, Dynamodb, and Redshift?
- Do you prefer to host a website on S3? What's the reason if your answer is either yes or no?

Let's share your answer on LinkedIn in best possible way thinking you are in a interview table.
Happy Learning !! :)

[← Previous Day](../day48/README.md) | [Next Day →](../day50/README.md)



# Day 50: Your CI/CD pipeline on AWS - Part-1 🚀 ☁

What if I tell you, in next 4 days, you'll be making a CI/CD pipeline on AWS with these tools.

- CodeCommit
- CodeBuild
- CodeDeploy
- CodePipeline
- S3

## What is CodeCommit ?

- CodeCommit is a managed source control service by AWS that allows users to store, manage, and version their source code and artifacts securely and at scale. It supports Git, integrates with other AWS services, enables collaboration through branch and merge workflows, and provides audit logs and compliance reports to meet regulatory requirements and track changes. Overall, CodeCommit provides developers with a reliable and efficient way to manage their codebase and set up a CI/CD pipeline for their software development projects.

# Task-01 :

- Set up a code repository on CodeCommit and clone it on your local.
- You need to setup GitCredentials in your AWS IAM.
- Use those credentials in your local and then clone the repository from CodeCommit

# Task-02 :

- Add a new file from local and commit to your local branch
- Push the local changes to CodeCommit repository.

For more details watch [this](https://youtu.be/p5i3cMCQ760) video.

Happy Learning :)

[← Previous Day](../day49/README.md) | [Next Day →](../day51/README.md)



# Day 51: Your CI/CD pipeline on AWS - Part 2 🚀 ☁

On your journey of making a CI/CD pipeline on AWS with these tools, you completed AWS CodeCommit.

Next few days you'll learn these tools/services:

- CodeBuild
- CodeDeploy
- CodePipeline
- S3

## What is CodeBuild ?

- AWS CodeBuild is a fully managed build service in the cloud. CodeBuild compiles your source code, runs unit tests, and produces artifacts that are ready to deploy. CodeBuild eliminates the need to provision, manage, and scale your own build servers.

# Task-01 :

- Read about Buildspec file for Codebuild.
- create a simple index.html file in CodeCommit Repository
- you have to build the index.html using nginx server

# Task-02 :

- Add buildspec.yaml file to CodeCommit Repository and complete the build process.

For more details watch [this](https://youtu.be/p5i3cMCQ760) video.

Happy Learning :)

[← Previous Day](../day50/README.md) | [Next Day →](../day52/README.md)



# Day 52: Your CI/CD pipeline on AWS - Part 3 🚀 ☁

On your journey of making a CI/CD pipeline on AWS with these tools, you completed AWS CodeCommit & CodeBuild.

Next few days you'll learn these tools/services:

- CodeDeploy
- CodePipeline
- S3

## What is CodeDeploy ?

- AWS CodeDeploy is a deployment service that automates application deployments to Amazon EC2 instances, on-premises instances, serverless Lambda functions, or Amazon ECS services.

CodeDeploy can deploy application content that runs on a server and is stored in Amazon S3 buckets, GitHub repositories, or Bitbucket repositories. CodeDeploy can also deploy a serverless Lambda function. You do not need to make changes to your existing code before you can use CodeDeploy.

# Task-01 :

- Read about Appspec.yaml file for CodeDeploy.
- Deploy index.html file on EC2 machine using nginx
- you have to setup a CodeDeploy agent in order to deploy code on EC2

# Task-02 :

- Add appspec.yaml file to CodeCommit Repository and complete the deployment process.

For more details watch [this](https://youtu.be/IUF-pfbYGvg) video.

Happy Learning :)

[← Previous Day](../day51/README.md) | [Next Day →](../day53/README.md)



# Day 53: Your CI/CD pipeline on AWS - Part 4 🚀 ☁

On your journey of making a CI/CD pipeline on AWS with these tools, you completed AWS CodeCommit, CodeBuild & CodeDeploy.

Finish Off in style with AWS CodePipeline

## What is CodePipeline ?

- CodePipeline builds, tests, and deploys your code every time there is a code change, based on the release process models you define.
  Think of it as a CI/CD Pipeline service

# Task-01 :

- Create a Deployment group of Ec2 Instance.
- Create a CodePipeline that gets the code from CodeCommit, Builds the code using CodeBuild and deploys it to a Deployment Group.

For more details watch [this](https://youtu.be/IUF-pfbYGvg) video.

Happy Learning :)

[← Previous Day](../day52/README.md) | [Next Day →](../day54/README.md)



# Day 54: Understanding Infrastructure as Code and Configuration Management

## What's the difference bhaiyya?

When it comes to the cloud, Infrastructure as Code (IaC) and Configuration Management (CM) are inseparable. With IaC, a descriptive model is used for infrastructure management. To name a few examples of infrastructure: networks, virtual computers, and load balancers. Using an IaC model always results in the same setting.

Throughout the lifecycle of a product, Configuration Management (CM) ensures that the performance, functional and physical inputs, requirements, design, and operations of that product remain consistent.

# Task-01

- Read more about IaC and Config. Management Tools
- Give differences on both with suitable examples
- What are most commont IaC and Config management Tools?

Write a blog on this topic in the most creative way and post it on linkedIn :)

happy learning...

[← Previous Day](../day53/README.md) | [Next Day →](../day55/README.md)



# Day 55: Understanding Configuration Management with Ansible

## What's this Ansible?

Ansible is an open-source automation tool, or platform, used for IT tasks such as configuration management, application deployment, intraservice orchestration, and provisioning

# Task-01

- Installation of Ansible on AWS EC2 (Master Node)
  `sudo apt-add-repository ppa:ansible/ansible` `sudo apt update`
  `sudo apt install ansible`

# Task-02

- read more about Hosts file
  `sudo nano /etc/ansible/hosts ansible-inventory --list -y`

# Task-03

- Setup 2 more EC2 instances with same Private keys as the previous instance (Node)
- Copy the private key to master server where Ansible is setup
- Try a ping command using ansible to the Nodes.

Write a blog on this topic with screenshots in the most creative way and post it on linkedIn :)

happy learning...

[← Previous Day](../day54/README.md) | [Next Day →](../day56/README.md)



# Day 56: Understanding Ad-hoc commands in Ansible

Ansible ad hoc commands are one-liners designed to achieve a very specific task they are like quick snippets and your compact swiss army knife when you want to do a quick task across multiple machines.

To put simply, Ansible ad hoc commands are one-liner Linux shell commands and playbooks are like a shell script, a collective of many commands with logic.

Ansible ad hoc commands come handy when you want to perform a quick task.

# Task-01

- write an ansible ad hoc ping command to ping 3 servers from inventory file
- Write an ansible ad hoc command to check uptime

- You can refer to [this](https://www.middlewareinventory.com/blog/ansible-ad-hoc-commands/) blog to understand the different examples of ad-hoc commands and try out them, post the screenshots in a blog with an explanation.

happy Learning :)

[← Previous Day](../day55/README.md) | [Next Day →](../day57/README.md)



# Day 57: Ansible Hands-on with video

Ansible is fun, you saw in last few days how easy it is.

Let's make it fun now, by using a video explanation for Ansible.

# Task-01

- Write a Blog explanation for the [ansible video](https://youtu.be/SGB7EdiP39E)

happy Learning :)

[← Previous Day](../day56/README.md) | [Next Day →](../day58/README.md)



# Day 58: Ansible Playbooks

Ansible playbooks run multiple tasks, assign roles, and define configurations, deployment steps, and variables. If you’re using multiple servers, Ansible playbooks organize the steps between the assembled machines or servers and get them organized and running in the way the users need them to. Consider playbooks as the equivalent of instruction manuals.

# Task-01

- Write an ansible playbook to create a file on a different server

- Write an ansible playbook to create a new user.

- Write an ansible playbook to install docker on a group of servers

Watch [this](https://youtu.be/089mRKoJTzo) video to learn about ansible Playbooks

# Task-02

- Write a blog about writing ansible playbooks with the best practices.

Let me or anyone in the community know if you face any challenges

happy Learning :)

[← Previous Day](../day57/README.md) | [Next Day →](../day59/README.md)



# Day 59: Ansible Project 🔥

Ansible playbooks are amazing, as you learned yesterday.
What if you deploy a simple web app using ansible, sounds like a good project, right?

# Task-01

- create 3 EC2 instances . make sure all three are created with same key pair

- Install Ansible in host server

- copy the private key from local to Host server (Ansible_host) at (/home/ubuntu/.ssh)

- access the inventory file using sudo vim /etc/ansible/hosts

- Create a playbook to install Nginx

- deploy a sample webpage using the ansible playbook

Read [this](https://medium.com/@sandeep010498/learn-ansible-with-real-time-project-cf6a0a512d45) Blog by [Sandeep Singh](https://medium.com/@sandeep010498) to clear all your doubts

Let me or anyone in the community know if you face any challenges

happy Learning :)

[← Previous Day](../day58/README.md) | [Next Day →](../day60/README.md)



# Day 60 - Terraform🔥

Hello Learners , you guys are doing every task by creating an ec2 instance (mostly). Today let’s automate this process . How to do it ? Well Terraform is the solution .

## What is Terraform?

Terraform is an infrastructure as code (IaC) tool that allows you to create, manage, and update infrastructure
resources such as virtual machines, networks, and storage in a repeatable, scalable, and automated way.

## Task 1:

Install Terraform on your system
Refer this [link](https://phoenixnap.com/kb/how-to-install-terraform) for installation

## Task 2: Answer below questions

- Why we use terraform?
- What is Infrastructure as Code (IaC)?
- What is Resource?
- What is Provider?
- Whats is State file in terraform? What’s the importance of it ?
- What is Desired and Current State?

You can prepare for tomorrow's task from [here](https://www.youtube.com/live/965CaSveIEI?feature=share)🚀🚀

We Hope this tasks will help you understand how to write a basic Terraform configuration file and basic commands on Terraform.

Don’t forget to post in on LinkedIn.
Happy Learning:)

[← Previous Day](../day59/README.md) | [Next Day →](../day61/README.md)



# Day 61- Terraform🔥

Hope you've already got the gist of What Working with Terraform would be like . Lets begin
with day 2 of Terraform !

## Task 1:

find purpose of basic Terraform commands which you'll use often

1. `terraform init`

2. `terraform init -upgrade`

3. `terraform plan`

4. `terraform apply`

5. `terraform validate`

6. `terraform fmt`

7. `terraform destroy`

Also along with these tasks its important to know about Terraform in general-
Who are Terraform's main competitors?
The main competitors are:

Ansible
Packer
Cloud Foundry
Kubernetes

Want a Free video Course for terraform? Click [here](https://bit.ly/tws-terraform)

Don't forget to share your learnings on Linkedin ! Happy Learning :)

[← Previous Day](../day60/README.md) | [Next Day →](../day62/README.md)



# Day 62 - Terraform and Docker 🔥

Terraform needs to be told which provider to be used in the automation, hence we need to give the provider name with source and version.
For Docker, we can use this block of code in your main.tf

## Blocks and Resources in Terraform

## Terraform block

## Task-01

- Create a Terraform script with Blocks and Resources

```
terraform {
  required_providers {
    docker = {
      source  = "kreuzwerker/docker"
      version = "~> 2.21.0"
}
}
}
```

### Note: kreuzwerker/docker, is shorthand for registry.terraform.io/kreuzwerker/docker.

## Provider Block

The provider block configures the specified provider, in this case, docker. A provider is a plugin that Terraform uses to create and manage your resources.

```
provider "docker" {}
```

## Resource

Use resource blocks to define components of your infrastructure. A resource might be a physical or virtual component such as a Docker container, or it can be a logical resource such as a Heroku application.

Resource blocks have two strings before the block: the resource type and the resource name. In this example, the first resource type is docker_image and the name is Nginx.

## Task-02

- Create a resource Block for an nginx docker image

Hint:

```
resource "docker_image" "nginx" {
 name         = "nginx:latest"
 keep_locally = false
}
```

- Create a resource Block for running a docker container for nginx

```
resource "docker_container" "nginx" {
 image = docker_image.nginx.latest
 name  = "tutorial"
 ports {
   internal = 80
   external = 80
 }
}
```

Note: In case Docker is not installed

`sudo apt-get install docker.io`
`sudo docker ps`
`sudo chown $USER /var/run/docker.sock`

# Video Course

I can imagine, Terraform can be tricky, so best to use a Free video Course for terraform [here](https://bit.ly/tws-terraform)

Happy Learning :)

[← Previous Day](../day61/README.md) | [Next Day →](../day63/README.md)



# Day 63 - Terraform Variables

variables in Terraform are quite important, as you need to hold values of names of instance, configs , etc.

We can create a variables.tf file which will hold all the variables.

```
variable "filename" {
default = "/home/ubuntu/terrform-tutorials/terraform-variables/demo-var.txt"
}
```

```
variable "content" {
default = "This is coming from a variable which was updated"
}
```

These variables can be accessed by var object in main.tf

## Task-01

- Create a local file using Terraform
  Hint:

```
resource "local_file" "devops" {
filename = var.filename
content = var.content
}
```

## Data Types in Terraform

## Map

```
variable "file_contents" {
type = map
default = {
"statement1" = "this is cool"
"statement2" = "this is cooler"
}
}
```

## Task-02

- Use terraform to demonstrate usage of List, Set and Object datatypes
- Put proper screenshots of the outputs

Use `terraform refresh`

To refresh the state by your configuration file, reloads the variables

# Video Course

I can imagine, Terraform can be tricky, so best to use a Free video Course for terraform [here](https://bit.ly/tws-terraform)

Happy Learning :)

[← Previous Day](../day62/README.md) | [Next Day →](../day64/README.md)



# Day 64 - Terraform with AWS

Provisioning on AWS is quite easy and straightforward with Terraform.

## Prerequisites

### AWS CLI installed

The AWS Command Line Interface (AWS CLI) is a unified tool to manage your AWS services. With just one tool to download and configure, you can control multiple AWS services from the command line and automate them through scripts.

### AWS IAM user

IAM (Identity Access Management) AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.

_In order to connect your AWS account and Terraform, you need the access keys and secret access keys exported to your machine._

```
export AWS_ACCESS_KEY_ID=<access key>
export AWS_SECRET_ACCESS_KEY=<secret access key>
```

### Install required providers

```
terraform {
 required_providers {
        aws = {
        source  = "hashicorp/aws"
        version = "~> 4.16"
}
}
        required_version = ">= 1.2.0"
}
```

Add the region where you want your instances to be

```
provider "aws" {
region = "us-east-1"
}
```

## Task-01

- Provision an AWS EC2 instance using Terraform

Hint:

```
resource "aws_instance" "aws_ec2_test" {
        count = 4
        ami = "ami-08c40ec9ead489470"
        instance_type = "t2.micro"
        tags = {
     Name = "TerraformTestServerInstance"
  }
}
```

# Video Course

I can imagine, Terraform can be tricky, so best to use a Free video Course for terraform [here](https://bit.ly/tws-terraform)

Happy Learning :)

[← Previous Day](../day63/README.md) | [Next Day →](../day65/README.md)



# Day 65 - Working with Terraform Resources 🚀

Yesterday, we saw how to create a Terraform script with Blocks and Resources. Today, we will dive deeper into Terraform resources.

## Understanding Terraform Resources

A resource in Terraform represents a component of your infrastructure, such as a physical server, a virtual machine, a DNS record, or an S3 bucket. Resources have attributes that define their properties and behaviors, such as the size and location of a virtual machine or the domain name of a DNS record.

When you define a resource in Terraform, you specify the type of resource, a unique name for the resource, and the attributes that define the resource. Terraform uses the resource block to define resources in your Terraform configuration.

## Task 1: Create a security group

To allow traffic to the EC2 instance, you need to create a security group. Follow these steps:

In your main.tf file, add the following code to create a security group:

```
resource "aws_security_group" "web_server" {
  name_prefix = "web-server-sg"

  ingress {
    from_port   = 80
    to_port     = 80
    protocol    = "tcp"
    cidr_blocks = ["0.0.0.0/0"]
  }
}
```

- Run terraform init to initialize the Terraform project.

- Run terraform apply to create the security group.

## Task 2: Create an EC2 instance

- Now you can create an EC2 instance with Terraform. Follow these steps:

- In your main.tf file, add the following code to create an EC2 instance:

```
resource "aws_instance" "web_server" {
  ami           = "ami-0557a15b87f6559cf"
  instance_type = "t2.micro"
  key_name      = "my-key-pair"
  security_groups = [
    aws_security_group.web_server.name
  ]

  user_data = <<-EOF
              #!/bin/bash
              echo "<html><body><h1>Welcome to my website!</h1></body></html>" > index.html
              nohup python -m SimpleHTTPServer 80 &
              EOF
}
```

Note: Replace the ami and key_name values with your own. You can find a list of available AMIs in the AWS documentation.

Run terraform apply to create the EC2 instance.

## Task 3: Access your website

- Now that your EC2 instance is up and running, you can access the website you just hosted on it. Follow these steps:

Happy Terraforming!

[← Previous Day](../day64/README.md) | [Next Day →](../day66/README.md)



# Day 66 - Terraform Hands-on Project - Build Your Own AWS Infrastructure with Ease using Infrastructure as Code (IaC) Techniques(Interview Questions) ☁️

Welcome back to your Terraform journey.

In the previous tasks, you have learned about the basics of Terraform, its configuration file, and creating an EC2 instance using Terraform. Today, we will explore more about Terraform and create multiple resources.

## Task:

- Create a VPC (Virtual Private Cloud) with CIDR block 10.0.0.0/16
- Create a public subnet with CIDR block 10.0.1.0/24 in the above VPC.
- Create a private subnet with CIDR block 10.0.2.0/24 in the above VPC.
- Create an Internet Gateway (IGW) and attach it to the VPC.
- Create a route table for the public subnet and associate it with the public subnet. This route table should have a route to the Internet Gateway.
- Launch an EC2 instance in the public subnet with the following details:
- AMI: ami-0557a15b87f6559cf
- Instance type: t2.micro
- Security group: Allow SSH access from anywhere
- User data: Use a shell script to install Apache and host a simple website
- Create an Elastic IP and associate it with the EC2 instance.
- Open the website URL in a browser to verify that the website is hosted successfully.

#### This Terraform hands-on task is designed to test your proficiency in using Terraform for Infrastructure as Code (IaC) on AWS. You will be tasked with creating a VPC, subnets, an internet gateway, and launching an EC2 instance with a web server running on it. This task will showcase your skills in automating infrastructure deployment using Terraform. It's a popular interview question for companies looking for candidates with hands-on experience in Terraform. That's it for today.

Happy Terraforming:)

[← Previous Day](../day65/README.md) | [Next Day →](../day67/README.md)



# Day 67: AWS S3 Bucket Creation and Management

## AWS S3 Bucket

Amazon S3 (Simple Storage Service) is an object storage service that offers industry-leading scalability, data availability, security, and performance. It can be used for a variety of use cases, such as storing and retrieving data, hosting static websites, and more.

In this task, you will learn how to create and manage S3 buckets in AWS.

## Task

- Create an S3 bucket using Terraform.
- Configure the bucket to allow public read access.
- Create an S3 bucket policy that allows read-only access to a specific IAM user or role.
- Enable versioning on the S3 bucket.

## Resources

[Terraform S3 bucket resource](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket)

Good luck and happy learning!

[← Previous Day](../day66/README.md) | [Next Day →](../day68/README.md)



# Day 68 - Scaling with Terraform 🚀

Yesterday, we learned how to AWS S3 Bucket with Terraform. Today, we will see how to scale our infrastructure with Terraform.

## Understanding Scaling

Scaling is the process of adding or removing resources to match the changing demands of your application. As your application grows, you will need to add more resources to handle the increased load. And as the load decreases, you can remove the extra resources to save costs.

Terraform makes it easy to scale your infrastructure by providing a declarative way to define your resources. You can define the number of resources you need and Terraform will automatically create or destroy the resources as needed.

## Task 1: Create an Auto Scaling Group

Auto Scaling Groups are used to automatically add or remove EC2 instances based on the current demand. Follow these steps to create an Auto Scaling Group:

- In your main.tf file, add the following code to create an Auto Scaling Group:

```
resource "aws_launch_configuration" "web_server_as" {
  image_id        = "ami-005f9685cb30f234b"
  instance_type  = "t2.micro"
  security_groups = [aws_security_group.web_server.name]

  user_data = <<-EOF
              #!/bin/bash
              echo "<html><body><h1>You're doing really Great</h1></body></html>" > index.html
              nohup python -m SimpleHTTPServer 80 &
              EOF
}

resource "aws_autoscaling_group" "web_server_asg" {
  name                 = "web-server-asg"
  launch_configuration = aws_launch_configuration.web_server_lc.name
  min_size             = 1
  max_size             = 3
  desired_capacity     = 2
  health_check_type    = "EC2"
  load_balancers       = [aws_elb.web_server_lb.name]
  vpc_zone_identifier  = [aws_subnet.public_subnet_1a.id, aws_subnet.public_subnet_1b.id]
}


```

- Run terraform apply to create the Auto Scaling Group.

## Task 2: Test Scaling

- Go to the AWS Management Console and select the Auto Scaling Groups service.

- Select the Auto Scaling Group you just created and click on the "Edit" button.

- Increase the "Desired Capacity" to 3 and click on the "Save" button.

- Wait a few minutes for the new instances to be launched.

- Go to the EC2 Instances service and verify that the new instances have been launched.

- Decrease the "Desired Capacity" to 1 and wait a few minutes for the extra instances to be terminated.

- Go to the EC2 Instances service and verify that the extra instances have been terminated.

Congratulations🎊🎉 You have successfully scaled your infrastructure with Terraform.

Happy Learning :)

[← Previous Day](../day67/README.md) | [Next Day →](../day69/README.md)



# Day 69 - Meta-Arguments in Terraform

When you define a resource block in Terraform, by default, this specifies one resource that will be created. To manage several of the same resources, you can use either count or for_each, which removes the need to write a separate block of code for each one. Using these options reduces overhead and makes your code neater.

count is what is known as a ‘meta-argument’ defined by the Terraform language. Meta-arguments help achieve certain requirements within the resource block.

## Count

The count meta-argument accepts a whole number and creates the number of instances of the resource specified.

When each instance is created, it has its own distinct infrastructure object associated with it, so each can be managed separately. When the configuration is applied, each object can be created, destroyed, or updated as appropriate.

eg.

```

terraform {

required_providers {

aws = {

source = "hashicorp/aws"

version = "~> 4.16"

}

}

required_version = ">= 1.2.0"

}



provider "aws" {

region = "us-east-1"

}



resource "aws_instance" "server" {

count = 4



ami = "ami-08c40ec9ead489470"

instance_type = "t2.micro"



tags = {

Name = "Server ${count.index}"

}

}



```

## for_each

Like the count argument, the for_each meta-argument creates multiple instances of a module or resource block. However, instead of specifying the number of resources, the for_each meta-argument accepts a map or a set of strings. This is useful when multiple resources are required that have different values. Consider our Active directory groups example, with each group requiring a different owner.

```

terraform {

required_providers {

aws = {

source = "hashicorp/aws"

version = "~> 4.16"

}

}

required_version = ">= 1.2.0"

}



provider "aws" {

region = "us-east-1"

}



locals {

ami_ids = toset([

"ami-0b0dcb5067f052a63",

"ami-08c40ec9ead489470",

])

}



resource "aws_instance" "server" {

for_each = local.ami_ids



ami = each.key

instance_type = "t2.micro"

tags = {

Name = "Server ${each.key}"

}

}



Multiple key value iteration

locals {

ami_ids = {

"linux" :"ami-0b0dcb5067f052a63",

"ubuntu": "ami-08c40ec9ead489470",

}

}



resource "aws_instance" "server" {

for_each = local.ami_ids



ami = each.value

instance_type = "t2.micro"



tags = {

Name = "Server ${each.key}"

}

}

```

## Task-01

- Create the above Infrastructure as code and demonstrate the use of Count and for_each.
- Write about meta-arguments and its use in Terraform.

Happy learning :)

[← Previous Day](../day68/README.md) | [Next Day →](../day70/README.md)



# Day 70 - Terraform Modules

- Modules are containers for multiple resources that are used together. A module consists of a collection of .tf and/or .tf.json files kept together in a directory
- A module can call other modules, which lets you include the child module's resources into the configuration in a concise way.
- Modules can also be called multiple times, either within the same configuration or in separate configurations, allowing resource configurations to be packaged and re-used.

### Below is the format on how to use modules:

```
# Creating a AWS EC2 Instance
resource "aws_instance" "server-instance" {
  # Define number of instance
  instance_count = var.number_of_instances

  # Instance Configuration
  ami                    = var.ami
  instance_type          = var.instance_type
  subnet_id              = var.subnet_id
  vpc_security_group_ids = var.security_group

  # Instance Tagsid
  tags = {
    Name = "${var.instance_name}"
  }
}
```

```
# Server Module Variables
variable "number_of_instances" {
  description = "Number of Instances to Create"
  type        = number
  default     = 1
}

variable "instance_name" {
  description = "Instance Name"
}

variable "ami" {
  description = "AMI ID"
  default     = "ami-xxxx"
}

variable "instance_type" {
  description = "Instance Type"
}

variable "subnet_id" {
  description = "Subnet ID"
}

variable "security_group" {
  description = "Security Group"
  type        = list(any)
}
```

```
# Server Module Output
output "server_id" {
  description = "Server ID"
  value       = aws_instance.server-instance.id
}

```

## Task-01

Explain the below in your own words and it shouldnt be copied from Internet 😉

- Write about different modules Terraform.
- Difference between Root Module and Child Module.
- Is modules and Namespaces are same? Justify your answer for both Yes/No

You all are doing great, and you have come so far. Well Done Everyone🎉

Thode mehnat aur krni hai bas to lge rho tab tak.....Happy learning :)

[← Previous Day](../day69/README.md) | [Next Day →](../day71/README.md)



# Day 71 - Let's prepare for some interview questions of Terraform 🔥

### 1. What is Terraform and how it is different from other IaaC tools?

### 2. How do you call a main.tf module?

### 3. What exactly is Sentinel? Can you provide few examples where we can use for Sentinel policies?

### 4. You have a Terraform configuration file that defines an infrastructure deployment. However, there are multiple instances of the same resource that need to be created. How would you modify the configuration file to achieve this?

### 5. You want to know from which paths Terraform is loading providers referenced in your Terraform configuration (\*.tf files). You need to enable debug messages to find this out. Which of the following would achieve this?

A. Set the environment variable TF_LOG=TRACE

B. Set verbose logging for each provider in your Terraform configuration

C. Set the environment variable TF_VAR_log=TRACE

D. Set the environment variable TF_LOG_PATH

### 6. Below command will destroy everything that is being created in the infrastructure. Tell us how would you save any particular resource while destroying the complete infrastructure.

```
terraform destroy
```

### 7. Which module is used to store .tfstate file in S3?

### 8. How do you manage sensitive data in Terraform, such as API keys or passwords?

### 9. You are working on a Terraform project that needs to provision an S3 bucket, and a user with read and write access to the bucket. What resources would you use to accomplish this, and how would you configure them?

### 10. Who maintains Terraform providers?

### 11. How can we export data from one module to another?

#

Waiting for your responses😉.....Till then Happy learning :)

[← Previous Day](../day70/README.md) | [Next Day →](../day72/README.md)



Day 72 - Grafana🔥

Hello Learners , you guys are doing really a good job. You will not be there 24\*7 to monitor your resources. So, Today let’s monitor the resources in a smart way with - Grafana 🎉

## Task 1:

> What is Grafana? What are the features of Grafana?
> Why Grafana?
> What type of monitoring can be done via Grafana?
> What databases work with Grafana?
> What are metrics and visualizations in Grafana?
> What is the difference between Grafana vs Prometheus?

---

[← Previous Day](../day71/README.md) | [Next Day →](../day73/README.md)



Day 73 - Grafana 🔥
Hope you are now clear with the basics of grafana, like why we use, where we use, what can we do with this and so on.

Now, let's do some practical stuff.

---

Task:

> Setup grafana in your local environment on AWS EC2.

---

Ref: https://www.linkedin.com/posts/chetanrakhra_devops-project-share-activity-7042518379030556672-ZZA-?utm_source=share&utm_medium=member_desktop

[← Previous Day](../day72/README.md) | [Next Day →](../day74/README.md)



# Day 74 - Connecting EC2 with Grafana .

You guys did amazing job last day setting up Grafana on Local 🔥.

Now, let's do one step ahead.

---

Task:

Connect an Linux and one Windows EC2 instance with Grafana and monitor the different components of the server.

---

Don't forget to share this amazing work over LinkedIn and Tag us.





# Day 75 - Sending Docker Log to Grafana

We have monitored ,😉 that you guys are understanding and doing amazing with monitoring tool. 👌

Today, make it little bit more complex but interesting 😍 and let's add one more **Project** 🔥 to your resume.

---

## Task:

- Install _Docker_ and start docker service on a Linux EC2 through [USER DATA](../day39/README.md) .
- Create 2 Docker containers and run any basic application on those containers (A simple todo app will work).
- Now intregrate the docker containers and share the real time logs with Grafana (Your Instance should be connected to Grafana and Docker plugin should be enabled on grafana).
- Check the logs or docker container name on Grafana UI.

---

You can use [this video](https://youtu.be/y3SGHbixmJw) for your refernce. But it's always better to find your own way of doing. 😊

## Bonus :

- As you have done this amazing task, here is one bonus link.❤️

## You can use this [refernce video](https://youtu.be/CCi957AnSfc) to intregrate _Prometheus_ with _Grafana_ and monitor Docker containers. Seems interesting ?

Don't forget to share this amazing work over LinkedIn and Tag us.

## Happy Learning :)





# Day 76 Build a Grafana dashboard

A dashboard gives you an at-a-glance view of your data and lets you track metrics through different visualizations.

Dashboards consist of panels, each representing a part of the story you want your dashboard to tell.

Every panel consists of a query and a visualization. The query defines what data you want to display, whereas the visualization defines how the data is displayed.

## Task 01

- In the sidebar, hover your cursor over the Create (plus sign) icon and then click Dashboard.

- Click Add a new panel.

- In the Query editor below the graph, enter the query from earlier and then press Shift + Enter:

`sum(rate(tns_request_duration_seconds_count[5m])) by(route)`

- In the Legend field, enter {{route}} to rename the time series in the legend. The graph legend updates when you click outside the field.

- In the Panel editor on the right, under Settings, change the panel title to “Traffic”.

- Click Apply in the top-right corner to save the panel and go back to the dashboard view.

- Click the Save dashboard (disk) icon at the top of the dashboard to save your dashboard.

- Enter a name in the Dashboard name field and then click Save.

Read [this](https://grafana.com/tutorials/grafana-fundamentals/) in case you have any questions

Do share some amazing Dashboards with the community




# Day 77 Alerting

Grafana Alerting allows you to learn about problems in your systems moments after they occur. Create, manage, and take action on your alerts in a single, consolidated view, and improve your team’s ability to identify and resolve issues quickly.

Grafana Alerting is available for Grafana OSS, Grafana Enterprise, or Grafana Cloud. With Mimir and Loki alert rules you can run alert expressions closer to your data and at massive scale, all managed by the Grafana UI you are already familiar with.

## Task-01

- Setup [Grafana cloud](https://grafana.com/products/cloud/)
- Setup sample alerting

Check out [this blog](https://grafana.com/docs/grafana/latest/alerting/) for more details

[← Previous Day](../day76/README.md) | [Next Day →](../day78/README.md)



Day - 78 (Grafana Cloud)

---

Task - 01

1. Setup alerts for EC2 instance.
2. Setup alerts for AWS Billing Alerts.

---

For Reference: https://www.linkedin.com/posts/chetanrakhra_devops-project-share-activity-7044695663913148416-LfvD?utm_source=share&utm_medium=member_desktop




Day 79 - Prometheus 🔥

Now, the next step is to learn about the Prometheus.
It's an open-source system for monitoring services and alerts based on a time series data model. Prometheus collects data and metrics from different services and stores them according to a unique identifier—the metric name—and a time stamp.

Tasks:

---

1. What is the Architecture of Prometheus Monitoring?
2. What are the Features of Prometheus?
3. What are the Components of Prometheus?
4. What database is used by Prometheus?
5. What is the default data retention period in Prometheus?

---

Ref: https://www.devopsschool.com/blog/top-50-prometheus-interview-questions-and-answers/



# Project-1

=========

# Project Description

The project aims to automate the building, testing, and deployment process of a web application using Jenkins and GitHub. The Jenkins pipeline will be triggered automatically by GitHub webhook integration when changes are made to the code repository. The pipeline will include stages such as building, testing, and deploying the application, with notifications and alerts for failed builds or deployments.

## Task-01

Do the hands-on Project, read [this](https://www.linkedin.com/posts/chetanrakhra_devops-project-share-activity-7011367641952993281-DHn5?utm_source=share&utm_medium=member_desktop)



# Project-2

=========

# Project Description

The project is about automating the deployment process of a web application using Jenkins and its declarative syntax. The pipeline includes stages like building, testing, and deploying to a staging environment. It also includes running acceptance tests and deploying to production if all tests pass.

## Task-01

Do the hands-on Project, read [this](https://www.linkedin.com/posts/chetanrakhra_devops-project-share-activity-7014971330496212992-6Q2m?utm_source=share&utm_medium=member_desktop)




# Project-3

=========

# Project Description

The project involves hosting a static website using an AWS S3 bucket. Amazon S3 is an object storage service that provides a simple web services interface to store and retrieve any amount of data. The website files will be uploaded to an S3 bucket and configured to function as a static website. The bucket will be configured with the appropriate permissions and a unique domain name, making the website publicly accessible. Overall, the project aims to leverage the benefits of AWS S3 to host and scale a static website in a cost-effective and scalable manner.

## Task-01

Do the hands-on Project, read [this](https://www.linkedin.com/posts/chetanrakhra_aws-project-devopsjobs-activity-7016427742300663808-JAQd?utm_source=share&utm_medium=member_desktop)




# Project-4

=========

# Project Description

The project aims to deploy a web application using Docker Swarm, a container orchestration tool that allows for easy management and scaling of containerized applications. The project will utilize Docker Swarm's production-ready features such as load balancing, rolling updates, and service discovery to ensure high availability and reliability of the web application. The project will involve creating a Dockerfile to package the application into a container and then deploying it onto a Swarm cluster. The Swarm cluster will be configured to provide automated failover, load balancing, and horizontal scaling to the application. The goal of the project is to demonstrate the benefits of Docker Swarm for deploying and managing containerized applications in production environments.

## Task-01

Do the hands-on Project, read [this](https://www.linkedin.com/posts/chetanrakhra_devops-project-share-activity-7034173810656296960-UjUw?utm_source=share&utm_medium=member_desktop)



# Project-5

=========

# Project Description

The project involves deploying a Netflix clone web application on a Kubernetes cluster, a popular container orchestration platform that simplifies the deployment and management of containerized applications. The project will require creating Docker images of the web application and its dependencies and deploying them onto the Kubernetes cluster using Kubernetes manifests. The Kubernetes cluster will provide benefits such as high availability, scalability, and automatic failover of the application. Additionally, the project will utilize Kubernetes tools such as Kubernetes Dashboard and kubectl to monitor and manage the deployed application. Overall, the project aims to demonstrate the power and benefits of Kubernetes for deploying and managing containerized applications at scale.

## Task-01

Get a netflix clone form [GitHub](https://github.com/devandres-tech/Netflix-Clone), read [this](https://www.linkedin.com/posts/chetanrakhra_devops-project-share-activity-7034173810656296960-UjUw?utm_source=share&utm_medium=member_desktop) and follow the Redit clone steps to similarly deploy a Netflix Clone

Happy Learning :)



# Project-6

=========

# Project Description

The project involves deploying a Node JS app on AWS ECS Fargate and AWS ECR.
Read More about the tech stack [here](https://faun.pub/what-is-amazon-ecs-and-ecr-how-does-they-work-with-an-example-4acbf9be8415)

## Task-01

- Get a NodeJs application from [GitHub](https://github.com/LondheShubham153/node-todo-cicd).

- Build the Dockerfile present in the repo

- Setup AWS CLI and AWS Login in order to tag and push to ECR

- Setup an ECS cluster

- Create a Task Definition for the node js project with ECR image

- Run the Project and share it on LinkedIn :)


# Project-7

=========

# Project Description

The project involves deploying a Portfolio app on AWS S3 using GitHub Actions.
Git Hub actions allows you to perform CICD with GitHub Repository integrated.

## Task-01

- Get a Portfolio application from [GitHub](https://github.com/LondheShubham153/tws-portfolio).

- Build the GitHub Actions Workflow

- Setup AWS CLI and AWS Login in order to sync website to S3 (to be done as a part of YAML)

- Follow this [video]() to understand it better

- Run the Project and share it on LinkedIn :)


# Project-8

=========

# Project Description

The project involves deploying a react application on AWS Elastic BeanStalk using GitHub Actions.
Git Hub actions allows you to perform CICD with GitHub Repository integrated.

## Task-01

- Get source code from [GitHub](https://github.com/sitchatt/AWS_Elastic_BeanStalk_On_EC2.git).

- Setup AWS Elastic BeanStalk

- Build the GitHub Actions Workflow

- Follow this [blog](https://www.linkedin.com/posts/sitabja-chatterjee_effortless-deployment-of-react-app-to-aws-activity-7053579065487687680-wZI8?utm_source=share&utm_medium=member_desktop) to understand it better

- Run the Project and share it on LinkedIn :)

Happy Learning :)



# Project-9

=========

# Project Description

The project involves deploying a Django Todo app on AWS EC2 using Kubeadm Kubernetes cluster.

Kubernetes Cluster helps in Auto-scaling and Auto-healing of your application.

## Task-01

- Get a Django Full Stack application from [GitHub](https://github.com/LondheShubham153/django-todo-cicd).

- Setup the Kubernetes cluster using [this script](https://github.com/RishikeshOps/Scripts/blob/main/k8sss.sh)

- Setup Deployment and Service for Kubernetes.

- Run the Project and share it on LinkedIn :)



# Project-10

=========

# Project Description

The project involves Mounting of AWS S3 Bucket On Amazon EC2 Linux Using S3FS.

This is a AWS Mini Project that will teach you AWS, S3, EC2, S3FS.

## Task-01

- Create IAM user and set policies for the project resources using this [blog](https://medium.com/@chetxn/project-8-devops-implementation-8300b9ed1f2).
- Utilize and make the best use of aws-cli
- Run the Project and share it on LinkedIn :)





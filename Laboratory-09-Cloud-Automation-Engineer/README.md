# Laboratory 9: The Cloud Automation Engineer

## Mission Overview
Stepping into the role of a Cloud Automation Engineer at CloudNova Technologies, this laboratory focuses on eliminating manual administrative tasks by writing Bash automation scripts, managing file permissions, and scheduling automated backups using the Linux cron utility[cite: 1, 2].

## Objectives
* Understand fundamental Bash shell script syntax, including variables and basic commands[cite: 2].
* Use the nano command-line text editor to write and save executable scripts[cite: 2].
* Modify Linux file permissions using the `chmod` command[cite: 2].
* Understand task scheduling and the syntax of a Linux crontab[cite: 2].
* Document automation code and Cron job configurations using Markdown[cite: 2].

## Commands Executed
* `mkdir app-data` - Creates a dummy directory representing client data[cite: 2].
* `echo "This is critical client data." > app-data/data.txt` - Generates a sample data file[cite: 2].
* `nano backup.sh` - Opens the text editor to author the backup script[cite: 3].
* `chmod +x backup.sh` - Grants execution permissions to the script file[cite: 3, 4].
* `./backup.sh` - Executes the automation script manually[cite: 3].
* `ls -l backups/` - Verifies that the compressed archive was generated successfully[cite: 3].
* `crontab -l` - Lists active scheduled cron jobs[cite: 4].
* `env EDITOR=nano crontab -e` - Opens the crontab table editor[cite: 4].

## Skills Learned
* Shell scripting fundamentals and variable declaration.
* Linux permission management (`chmod`).
* Automated file compression using `tar`.
* Cron job configuration and time-expression syntax.

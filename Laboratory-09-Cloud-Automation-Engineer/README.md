# Laboratory 9: The Cloud Automation Engineer

## Mission Overview
Stepping into the role of a Cloud Automation Engineer at CloudNova Technologies, this laboratory focuses on eliminating manual administrative tasks by writing Bash automation scripts, managing file permissions, and scheduling automated backups using the Linux cron utility.

## Objectives
* Understand fundamental Bash shell script syntax, including variables and basic commands.
* Use the nano command-line text editor to write and save executable scripts.
* Modify Linux file permissions using the `chmod` command.
* Understand task scheduling and the syntax of a Linux crontab.
* Document automation code and Cron job configurations using Markdown.

## Commands Executed
* `mkdir app-data` - Creates a dummy directory representing client data.
* `echo "This is critical client data." > app-data/data.txt` - Generates a sample data file].
* `nano backup.sh` - Opens the text editor to author the backup script.
* `chmod +x backup.sh` - Grants execution permissions to the script file.
* `./backup.sh` - Executes the automation script manually.
* `ls -l backups/` - Verifies that the compressed archive was generated successfully.
* `crontab -l` - Lists active scheduled cron jobs.
* `env EDITOR=nano crontab -e` - Opens the crontab table editor.

## Skills Learned
* Shell scripting fundamentals and variable declaration.
* Linux permission management (`chmod`).
* Automated file compression using `tar`.
* Cron job configuration and time-expression syntax.

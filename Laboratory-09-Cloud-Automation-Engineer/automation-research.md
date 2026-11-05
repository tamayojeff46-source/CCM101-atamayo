# Automation Research: Concepts and Definitions

## Bash Script
A Bash script is a plain-text file containing a sequence of shell commands executed by the Bourne Again SHell interpreter. At the very top of the file, the shebang line (`#!/bin/bash`) instructs the operating system on precisely which interpreter program to use to execute the script instructions that follow.

## Variables
Programmers use variables (such as `$BACKUP_DIR`) instead of hardcoding exact folder paths because they act as reusable, labeled containers for dynamic values. This practice prevents code repetition, makes scripts significantly easier to maintain, and minimizes human errors during updates or modifications.

## Cron Job
A cron job is a time-based job scheduler built into Linux-based operating systems that runs commands or scripts automatically at specified dates and times. It is essential for cloud operations because it eliminates manual intervention for routine maintenance tasks like backups, system updates, and log rotations.

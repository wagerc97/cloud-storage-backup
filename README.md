# Cloud Storage Backup (CSB)
## In short
A set of scripts that use [Rclone](https://rclone.org/) to back up your cloud storage to a local storage device. 

## Purpose 
Easily configure your own backup service to periodically store your cloud data locally.  

## Requirements
Use for example cronjobs to trigger the according scripts (see [manual](/MANUAL.txt)) and save any changes on your cloud storage automatically. 
There is an [example crontab file](/src/maintenance/example-crontab.txt) with recommended cronjobs.  
You will need: 
- linux server
- [Rclone installation](https://rclone.org/downloads/)
- cronjob configuration

More details about the installation of the CSB service can be read in the [installation](/INSTALLATION.txt).

Note: This service was originally developed for Raspberry Pi. But any Linux/Unix system should be able to use it as intended.

## Quick Install
__Step 1:__ Highlight and copy the command below.  
__Step 2:__ Paste the command in a terminal session on your server and execute.  

``git clone https://github.com/wagerc97/cloud-storage-backup.git``

## Details
### Developed with focus on:
- good logging
- good documentation
- easy configuration

### About [Rclone](https://rclone.org/#about) <img align="right" src="https://rclone.org/img/logo_on_light__horizontal_color.svg" width="250" height="100" >

[Wikipedia](https://en.wikipedia.org/wiki/Rclone) defines Rclone as "an open source, multi threaded, command line computer program to manage or migrate content on cloud and other high latency storage. (...)"  

### Credit
Thanks [@pageauc](https://github.com/pageauc) for providing a nice Rclone installation repository [rclone4pi](https://github.com/pageauc/rclone4pi). It helped me to get into this topic. 

### Note 
This is the first time I used shell scripts in a project, so I learned a lot along the way. If you encounter any mistakes please let me know and I will fix it in the repo ;-)

# Linux Commands 

## Basic Comands

### Change Dirrectory

```
   cd 
```
### Make Dirrectory

```
   mkdir
```
### Copy File/Folder

```
   cp
```
### Move File/Folder

```
   mv
```
### List Files/Folders of the dirrectory

```
   ls
```
### Make a blank File

```
   touch 
```
### check in Which Dirrectory you are

```
   pwd
```
### Root Acess

```
   sudo
```
## Update the List of Software

```
   sudo apt-get update (Ubuntu 16)
   sudo apt update (Ubuntu 18)
```
### Install The Software

```
   sudo apt upgarde
```

### List dirrectory Recursively

``` 
   ls -R
```

### make a hidden file

```
   touch .yogesh
```
### Show hidden file in list

```
   ls -a
```

### Clear the Terminal

```
   clear
```
### Check the commands executed so far

```
   history
```
### Print Something On Terminal

```
   echo Yogesh Gaur
   printf "Yogesh Gaur"
```
 In Linux The files are named according to case senstivity YOGESH.txt and yogesh.txt are different

### Install a software

```
   sudo apt install
```
### List the Permissions of the file

```
    ls -l
```

### Change the Permission (mode) for Owner Group and Public

```
   chmod
```
### List the Processes that take maximum resoureces

```
   top
```
### List the foreground processes

```
   ps
```
### List all the Processes

```
   ps -a
```
### Change to super user

```
   sudo su
```

<h3>Code To Copy File from Local To Remote Sever</h3>

```
    scp source_folder remote_desktop_username@remote_desktop_ip:destination_folder
```

<h3>Code To Install any Software with root</h3>

```
   sudo apt-get install software_name
```

<h3>Code To Install any setup via curl</h3>

```
   curl -fsSL curl_url | sudo -E bash - &&\
```


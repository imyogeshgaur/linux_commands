# Linux Commands 

### Copy File/Folder

```
   cp file_name complete_location
```
### Move File/Folder

```
   mv file_name complete_location
```
### List All (hidden as well) Files/Folders of the dirrectory

```
   ls -a 
   ls -l (list with Permission)
```
### Make a blank File

```
   touch 
   touch .abc (create a hidden file abc)
```
### check in Which Dirrectory you are

```
   pwd
```
### Root Acess for a command

```
   sudo 
```
### Root Acess for complete terminal

```
   sudo su
```
### Update the APT (software to download other software)

```
   sudo apt-get update 
```
### Install The Software

```
   sudo apt upgarde software_name
```
### Install The Software

```
   sudo apt install software_name
```
### List dirrectory Recursively

``` 
   ls -R
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

### Add the Permission (mode) for Owner Group and Public

```
  chmod +w/+r/+x or +wr/+wx file_name
```
### Remove the Permission (mode) for Owner Group and Public

```
  chmod -w/-r/-x or -wr/-wx file_name
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
### Code To Copy File from Local To Remote Sever

```
    scp source_folder remote_desktop_username@remote_desktop_ip:destination_folder
```

### Code To Install any Software with root

```
   sudo apt-get install software_name
```

### Code To Install any setup via curl

```
   curl -fsSL curl_url | sudo -E bash - &&\
```

### Code To Kill a Process

```
  kill process_id
```

### Check the status of service

```
   service service_name status 
```

### Restart a Service

```
   sudo systemctl start service_name
```
### Get list of all listining ports
```
   netstat -ntlp
```

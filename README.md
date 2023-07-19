# git_commands


## Three-stage Architecture of git

![areas](https://github.com/DhanashriSaner/git_commands/assets/88526990/2db1b30f-5542-44b3-8775-64c54f4af283)

#### 1) Set global Username and email to git(locally)
```
git config --global user.name "<username>"
```

```
git config --global user.email "<email>"
```
#### 2) Clone an existing Git repository
```
git clone <repository_URL>
```

#### 3) Initialized empty Git repository
```
git init
```
#### 4) Show the status of the git repository
```
git status
```
#### 5) Add the file from the working directory into the staging area.
```
git add <filename>
```

#### 6) Add all current directory files into the staging area.
```
git add .
```
#### 7) Commit all the stage files to git
```
git commit -m "<Commit_message>"
```

#### 8) Restore the file from being modified to Tracked (2 options are available)

```
git restore <filename>
```
```
git checkout <filename>
```

#### 9) Add remote origin URL
```
git remote add origin <Your_remote_git_URL>
```
#### 10) Remove remote origin URL
```
git remote remove origin
```

#### 11) Push your local changes to the remote branch
```
git push origin <branch_name>
```
#### 12) create a new branch
```
git checkout -b <branch_name>
```
#### 13) Switch to master

```
git switch master
```



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

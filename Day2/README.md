# Basic Linux Commands

## Listing Commands

### Syntax

### Examples:
- `ls -l`  
  Lists the files and directories in long list format with extra information.

- `ls -a`  
  Lists all files, including hidden files and directories.

- `ls *.sh`  
  Lists all the files having `.sh` extension.

- `ls -i`  
  Lists the files and directories with their index numbers (inodes).

- `ls -d */`  
  Lists only directories (a pattern can be specified).

## Directory Commands

- `pwd`  
  Prints the present working directory.

- `cd path_to_directory`  
  Changes directory to the provided path.

- `cd ~` or `cd`  
  Changes directory to the home directory.

- `cd -`  
  Goes to the last working directory.

- `cd ..`  
  Changes directory to one level up.

- `cd ../..`  
  Changes directory two levels up.

- `mkdir directoryName`  
  Creates a new directory at the specified location.

### Examples:
- `mkdir newFolder`  
  Creates a new folder named `newFolder`.

- `mkdir .NewFolder`  
  Creates a hidden directory (prefixing a name with `.` makes it hidden).

- `mkdir A B C D`  
  Creates multiple directories (`A`, `B`, `C`, `D`) at the same time.

- `mkdir /home/user/Mydirectory`  
  Creates a new folder in a specific location.

- `mkdir -p A/B/C/D`  
  Creates a nested directory structure.


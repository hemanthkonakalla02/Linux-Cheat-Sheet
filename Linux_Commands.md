1]What is Linux ?

    ->Linux is a kernel that manages hardware and system resources,when combined with tools,libraries and utilities like(Graphical User Interface) it forms a complete
    operating system called as Linux distribution.


     1]touch fileName : is used to create a blank new file

    2]touch file{1..2}.txt : create multiple blank new files at a time

    3]ll : long list all files and directories along with the permisions,created date and time

    4]ls -a : it will shows all the files and directories along with the hidden files and directories

    5]ll -R : it will list all the sub-directories recursively

    6]ls -r : it will reverse the order of files and directories

    7]ll -a : long list all the files and directories along with the hidden files and directories with permisions,created date and time

    8]pwd : shows current working directory

    9]ls : view contents of directory

    10]cd : change directory

    11]cd .. : comes out of the directory

    12]mkdir : makes new directory

    13]mv : move files/rename files

    14]cp : copy files

    15]cp -r : copy directories

    16]rm : remove files

    17]rmdir : removes empty directory,if directory contains data then rmdir will not work we need to use rm -rf directoryName

    18]cat : list the content of file to teriminal

    19]cat > fileName : creates file and write data into file

    20]cat >> fileName : update the file content

    21]clear : clears teriminal window

    22]history : shows the commands that we executed till now

    23]echo : prints text to teriminal and it is commonly used with re-direction to write data into file

    24]less : is used to open the file content page-wise with scroll up/down support

    25]more : is used to open the file content page-wise only with scroll down support

    26]man : show manual of linux commands

    27]sudo -i : enables to perform task that requires root or admistrative permisions

    28]top : shows real time running processes and cpu/memory usage

    29]grep :  used for searching words in specific file

    30]head : view first 10 lines of any text file

    31]tail : view last 10 lines of any text file

    32]diff : compare the content of two files line by line

    34]kill : used for killing the unresponsive program

    35]find : searches files and directories

    36]cal : shows calendar

    37] vim : opens vim editor
        "i" --> insert mode
        "esc wq! filenane" --> saves data into file and quit
        "esc q!" --> quit the editor
    
    38]sort : is a command utility for sorting lines of text files

    39]df -h : info about  system disk in human readable format

    40]du -h : check how much space a file or directory takes

    41]zip : compress your files into zip archieve

    42]unzip : extract the zipped files from zip archieve

    43]dnf : is a command line tool for interaction with packaging system

    44]sudo dnf install packageName : installs the packages

    45]sudo dnf list : shows the list of installed packages

    46]sudo dnf remove packageName : Removes the installed packages

    47]alias ttt="clear" : alias creates a custom shortcut to represent a command

    48]w : current user info

    49]logname : shows login username

    50]uname -a : shows detailed information about our linux system

    51]uname -r : shows kernel version

    52]uname -m : shows system is 32bit or 64bit

    53]whereis : command in linux is used to locate binary,sourcecode and manual page files for a specified program/command

    54]whatis : used to get one line man page description

    55]sudo useradd username : creates new user

    56]cut -d: -f1 /etc/passwd : shows the created users

    57]sudo userdel -r username : deletes the user

    58]sudo passwd username : set password for user

    59]whoami : prints current user

    60]uptime : prints current time when machine is up 

    61]free -h : shows ram usage 

    62]ping : check connectivity status to a server

    63]chmod : to change permisions for files and directories

    64]chown : to change ownership of files and directories

    65]sudo groupadd groupName : creates new group

    66]sudo usermod -aG groupname username : add user to group 

    67]sudo getent group groupName : verifies group exists or not

    68]sudo groupdel groupName : deletes the group

    69]locate : used to locate files and directories

    70]ifconfig : prints ip address

    71]ip a : prints ip address but shortest print

    72]systemctl reboot : reboot the system

    72]systemctl poweroff : shutdown the system

    73]sch : securely copy files between linux systems

    74]ssh : connect to remote linux servers

    75]env : prints environment variables

    76]export : set environment variables

    77]netstat : to check open ports

    78]ps : process listing

    79]curl : to test rest api's

    80]java -jar bank.jar : to run jars in linux

    81]tail -f app.log : to monitor logs

    82]tail -f app.log | grep Error : monitor live errors

    83]ps -ef | grep java : find java processes

    84]sudo netstat -tulnp | grep 8080 : to check ports

    85]kill -15 PID Gracefull shutdown

    86]kill -9 PID force kill


    777 --> full permisions for owners groups others 

    87]grep -i "this" file2.txt : case insensitive

    88]grep -n "this" file2.txt : line numbers

    89]wc -l file2.txt : count lines

    90] grep "this" file2.txt | wc -l : count "this" lines

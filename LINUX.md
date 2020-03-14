# Some linux commands

List files in a directoru
> ls

List files with more information
> ls -l

List  files recursivly
> ls -R

List files and show size in Mega unit
> ls -l --block-size=M

List all file even hidden files
> ls -al

Get absolute path of the current directory
> pwd

Recursive copy
> cp -TR source destination

Show ressource usage from process
> top

Watch a file from the bottom
> tail -f filename

Create a directory
> mdkir

Change right for a file or directory
> chmod 0755 directory_or_file

Change owner for a  file or directory
> chown newuser:newgroup file_or_directory

Show disk file usage
> df -h

Change directory
> cd the_directory

Create a file
> touch filename

Send a mail
> mail -s "your subject" recipient@domain.fr

* Write your message after the command and press CRTL + D

Show file_content
> cat filename

Send password in your command example with pure-pw
>  (echo $PASSWORD ; echo $PASSWORD) | pure-pw passwd $USER -m


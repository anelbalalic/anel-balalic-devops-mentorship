#Commands used in banditlabs


###ssh bandit0@bandit.labs.overthewire.org -p 2220
#####Connecting to banditlabs with password bandit0

###ls
#####list all files in curent directory

###ls -la
#####list all files including hiden files
#####-l provides a list of a directories content in long listing format
#####-a tells the computer to not ignore entries starting with a period.

###cat readme
#####read the readme file   

###find . -type f -exec file {} + | grep ASCII
#####Grep is an acronym that stands for Global Regular Expression Print. It's usage as a command line tool is to search for a pattern or string of text in a given file. The syntax #####of using grep calls for the pattern or string your searching for and the filename you'd like to search in
#####The other helpful options to use here would be, type -f to find all regular files, and -exec file for finding all executable files

###cat ./-
#####read the file that containing ASCII text     

###cat "spaces in filename"
#####filename contains spaces in between, wrapping filename in double #####quotes then the cat command ignores spaces inside filenames

###cd inhere
####changing directory, opening directory

###find -type f -size 1033c ! -executable
####finding file type human-readable 1033bytes in size and not executable

####find / -user bandit7 -group bandit6 -size 33c
#####finding user file with name bandit 7, and is part of group bandit6

###cat data.text | grep millionth
#####finding password that is writen next to the word "millionth"

###cat data.txt | sort | uniq -u
#####using sort to sort text inside the data.txt, the file contains a lot of repeating statements so we will use the uniq command to print the not repeating statement

###strings data.txt | grep =
####use strings command which prints character sequences that are at least 4 characters long, and to get to the exact location of the password, we are going to use grep

###cat data.txt | base64 --decode
####reading and decoding base64  


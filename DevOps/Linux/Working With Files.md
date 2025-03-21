 A part of [[DevOps]] learning path
   Part of [[Linux]] Basics  
 
- `cat FILENAME` Open and show all files data
- `less FILENAME` Open and Show all of files data page by page
- `head FILENAME` Open and Show top lines of the file
- `tail FILENAME` Open and Show end lines of the file
- `tail -f -n LINENUMBER FILENAME` Good for opening log files shows last lines of the file and after that continue showing new lines are adding to file after running ( `n` option for showing a specific line it counts from down to top)
- `echo TEXT >> FILENAME` Add text to  end of a file
- `grep TEXT FILENAME` Find text in your file and shows the lines that contain your text( `-i` option for ignoring uppercase and lowercase )
- `sed -i 's/TEXT1/TEXT2/g' FILENAME` Replace all TEXT1 in file with TEXT2
- `diff FILENAME FILENAME` Comparing two files 
- `sort` Sort a file ( read more about options )
- `cut -d ',' -f2` Separate the words by ,
- `awk` Work like '`cut`' 
- `wc` For counting lines or character and others
- `var/log/SERVICE` Finding log of a service
- `etc/logrotate.d/SERVICE` Finding log rotate of a service
- `var/log/auth.log` Watching login log from SSH and normal logins 
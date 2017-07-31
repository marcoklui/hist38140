#Fail Log Week 3
Module 1
used $curl http://archive.org/stream/diplomaticcorre33statgoog/diplomaticcorre33statgoog_djvu.txt > texas.txt
loading taking a long time
nano texas.txt
used d 's/old text/new text/g' filename
sed: can't read filename: No such file or directory
marcoklui@a134260ac1e7:~$ grep '\bto\b' texas.txt
marcoklui@a134260ac1e7:~$ grep '\bto\b' texas.txt
marcoklui@a134260ac1e7:~$ grep 'to' texas.txt
marcoklui@a134260ac1e7:~$ sed -r -i.bak 's/(.+\bto\b.+)/~\1/g' texas.txt
marcoklui@a134260ac1e7:~$ mv old-file-name new-file-nam
mv: cannot stat ‘old-file-name’: No such file or directory
marcoklui@a134260ac1e7:~$ grep '~' texas.txt

not finding the file or directory 
went back to try sed -r -i.bak 's/(.+\bto\b.+)/~\1/g' texas.tx
no avail going to see slack and annotations for help



**Module 2**
downloaded said program
trying to get the correspondence file in exercise 1  
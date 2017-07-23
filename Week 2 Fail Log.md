


#**Fail Log Week 2**

#Exercise 1
Used the Dream Case data bases and did a search.

Did the searches, and downloaded the spreadsheet.

used nano notepad.md to list my search URLs and update what info i found.

dropped the downloaded csv and new note pad into github

#Exercise 2
Began Ian Milligan's wget tutorial 

used the mk dir wget-activehistory
followed the instructions to download active history

wget -r --no-parent -w 2 --limit-rate=20k http://activehistory.ca/papers/ 
used this line and now downloading the papers to the files

Now on the next step
ran wget http://collections.banq.qc.ca:8008/jrn03/equity/src/1883/ -A .txt -r --no-parent -nd –w 2 --limit-rate=20k

#Excerise 3
Started the TEI exercise
downloaded said files from sub folder
proceeded to download the pamphlet
Used Text encoding to find the page i needed
Confused on how to find the biblo in note++ as CTRL F  is not finding it
will move onto exercise 4 and come back to figure out

#Exercise 4

typed $ sudo apt-get install jq -y and made the proper dir and entered it

made empty file with $ touch canadiana.sh

installed the script and began $ chmod 755 canadiana.sh

saved the canadiana.sh and comitted it to the Github repo

#Exercise 5
Made twitter account
Used twitter apps to make the app with the crafting digital history page
saved keys
on DHbox used $ sudo pip install twarc

configured twarc with the appropiate keys
wrote twarc search canada150 > search.json

hit this error when using $ sudo npm install json2csv --save -g
npm ERR! Linux 3.13.0-86-generic
npm ERR! argv "/usr/bin/nodejs" "/usr/bin/npm" "install" "json2sv" "--save" "-g"
npm ERR! node v5.10.1
npm ERR! npm  v3.8.3
npm ERR! code E404
npm ERR! 404 Registry returned 404 for GET on https://registry.npmjs.org/json2sv
npm ERR! 404 
npm ERR! 404  'json2sv' is not in the npm registry.
npm ERR! 404 You should bug the author to publish it (or use the name yourself!)
npm ERR! 404 
npm ERR! 404 Note that you can also install from a
npm ERR! 404 tarball, folder, http url, or git url.
npm ERR! Please include the following file with any support request:
npm ERR!     /home/marcoklui/npm-debug.log

retraced my steps to no avail will move onto Exercise 6 and return to twarc after reading slack comments

#Exercise 6

installed the OCR $ sudo apt-get install tesseract-ocr

used $sudo to install the 3 apps 
had trouble installing image gick but looked at the annotation for help
downloaded output.txt







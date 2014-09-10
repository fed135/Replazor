Replazor
========

A cheap find-and-replace-in-files with confirm dialog in bash. 

The code is ugly and unoptimized. Not as portable as I'dd wish either.
Only tested on Ubuntu 14 (x86_64) running GNU Bash 4.3.11

I'll try to clean that up... someday.



## Usage:

$ bash Replazor [needle] [replacement] [optional:directory] [optional:filter]


## Example:

$ bash Replazor "some string" "some other string" /var/www/my_folder "*.js"

Will look inside all the .js files in /var/www/my_folder for the string "some string" 
And will ask you if you wish to replace -occurence, by occurence- the needle with
"some other string", the replacement.



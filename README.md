# PasteBin


## What is PasteBin
  PasteBin is a webcrawler which searches public pastebins for specified keywords.
All pastes are then returned after sending completion signal ctrl+c.


## How to use PasteBin
  
  Basic command:
  
    python PasteBin.py -k <keyword1>,"example substring",<keyword2>..... -o <outputfile>
  
  Both the keyword and outputfile arguments are optional and defaults are

    -k : ssh,pass,key,token
    -o : log.txt

  Optional command:

  	-a, Appends to file instead of overwriting file.
  	-t <time in seconds>, Runs for time in seconds.
  	-n <integer>, Runs for number of pastes.
  	-m <integer>, Runs for number of matches.




# Python_Regular_Expressions
Parsing web access logs to determine valid versus supspicious requests


In this projet I applied Python regular expressions to an important problem that appears in the real world: analyzing web access logs.
The input file that contained the access log requests came from a security researcher who set up a ‘honeypot’ server to
attract hackers, in order to record the requests used in hacking attempts, to learn about their methods and origins. 
The original file was downloaded from http://logsharing.dreamhosters.com/. The three output files that I created were:
(1) A file that collected all of the valid log lines from the input file.
(2) A file that collected all of the invalid log lines from the input file. 
(3) A summary file that collected the number of access attempts from each unique client IP
address from the previous output file created in step 2. The IP addresses were
sorted in decreasing order of the attempts.

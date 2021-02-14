# Python 3 Rejetto HTTP File Server (HFS) 2.3.x - Remote Command Execution (2)
Original code from the exploit database: https://www.exploit-db.com/exploits/39161

Python 2 is deprecated and urllib2 not functional on Python 3. Error when parsing 
1) Using the requests library instead solves the issue.
2) Using raw strings to avoid unicode escape SyntaxError


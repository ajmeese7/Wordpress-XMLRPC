Wordpress XMLRPC System Multicall Brute Force Exploit by 1N3

## ABOUT:
This is an exploit for Wordpress xmlrpc.php System Multicall function affecting Wordpress 3.5.1. The exploit works by sending 1,000+ auth attempts per request to xmlrpc.php in order to "brute force" valid Wordpress users and will iterate through whole wordlists until a valid user response is acquired. It will then selectively acquire and display the valid username and password to login.

## USAGE:
```
python3 wordpress-xmlrpc-brute.py http://target.com/xmlrpc.php passwords.txt username1 [username2] [username3]...
```

## LICENSE:
This software is free to distribute, modify and use with the condition that credit is provided to the creator (1N3@CrowdShield) and is not for commercial use.

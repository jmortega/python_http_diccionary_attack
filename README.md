python_http_dictionary_attack
=============================

Is a threaded pentesting scanner for basic HTTP authorization using dictionary attack. It is an attempt in which the script tries to log in with username and a password. Each time the script tries it uses a different word in the dictionary file.

A dictionary attack is a technique for defeating a cipher or authentication mechanism by trying to determine its decryption key or passphrase by trying hundreds or sometimes millions of likely possibilities, such as words in a dictionary.

In this tool, you have two dictionary files needed for arguments:

    A list of user dictionary
    A list of password dictionary

Basically you have 3 arguments. 
The host, user dictionary file and password dictionary file. 

Usage:
python python_http_dictionary_attack.py [URL_DOMAIN] [userdict.txt] [passdict.txt]
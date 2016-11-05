# Fuzz String Lists

Hand-picked web application fuzzing strings for initial testing of web application requests. The general use case will occur after one has mapped out a web application and has found some requests with lots of parameters. A quick fuzz of that request using Burp Intruder or wfuzz and this list could either discover a vulnerability or cause a strange response from the server. If a strange response is discovered, then more granular fuzzing/exploiting can be done with strings from https://github.com/danielmiessler/SecLists or https://github.com/minimaxir/big-list-of-naughty-strings. 

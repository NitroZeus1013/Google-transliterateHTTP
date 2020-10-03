# Google-transliterateHTTP
This repository contains a python script to use Google transliterate(not Google translate) in your program.
Google transliterate also known as google input tools. This is a kind of API which basically sends 
an HTTP request to https://www.google.com/inputtools/. And receives a response from website. It uses requests module to send the request and record the response.
The response is captured in a variable and it is a request object so I used the .json method to convert it to json object.
And the json object contains 7 results for each query and by using indexing required output is printed.

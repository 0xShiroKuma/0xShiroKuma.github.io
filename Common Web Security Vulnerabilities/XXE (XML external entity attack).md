# XXE (XML external entity attack) [TEMP]

1. Look for content-type XML in HTTP request POST or GET

Try some XML file and if the server accept the request try an XXE

2. If the server use XML, look for POST request 

Translate the requests with https://portswigger.net/bappstore/db57ecbe2cb7446292a94aa6181c9278
Check the response for possible XML interpretation


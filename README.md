WebStress tool
==============

###Install

```
npm install -g webstress-tool
```

###usage

```
	webstress GET http://www.test.com 
```
will fire 1 get request to test.com and print the result and the headers


```
	webstress GET http://www.test.com 10 5
```
will fire 5 GET requests every second for 10 seconds to test.com, printing the average time and total time per batch


```
	webstress POST http://www.test.com 10 5 payload.txt
```
will fire 5 GET requests every second for 10 seconds to test.com sending the content of payload.txt every request, 
printing the average time and total time per batch.


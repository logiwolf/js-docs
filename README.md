# js-docs
This document is all about JavaScript, and this is all you need to become a JavaScript developer. 

Note: This document will be updated frequently, and new materials will be added continuously.

### github markup link
[GitHub markup link : the link to the next,  show how to makeup github readme file] (https://markdown-it.github.io/)


## workspace configuration
### add/configure user snippet of VS code
step 1: click code icon from left corner of window    
step 2: select setting    
step 3: select configure user snippets
step 4: new global snippet file / select exciting snippet

configure snippet as following:
   
   ```
    "Print to console": { 
		"scope": "javascript,typescript",     //write a scope// 
		"prefix": "c",    //Write which keys make the short cuts//
		"body": [
			"console.log();"   //what should get ouptput//
		],
		"description": "Log output to console" //discription of output//
	} 
```

 ### customerize prettier extension style

 step 1: create new file called .prettierrc     
 step 2: add code shown below

 	{
	  "singleQuote": true,
	  "arrowParens": "avoid"
	}


step 3: save the file 


## Javascript fundermetals

### Primitive Data types
#### 1. Variable

#### 2. Arrays
it is a data types which hold multiple values.

***
##### How to create and array
Arrays can be made in ways ways. That is

1. Array literal 
```  	
	const number = [1,2,3];
```     
2. Array with new key word:
```
	const number = new Array(1,2,3);
 ```

***
 ##### How to get last element of array
 
```
	const friends = ['Ali', 'Ahmed', 'Saeed'];
	friends[friends.length-1];
```

---
##### How to get add/remove new element of array

1. Replace an old element by new element.
```
	const friends = ['Ali', 'Ahmed', 'Saeed'];
	friends[1] = "Moahmed";
```
2. add an element to end of an array.
```
	const friends = ['Ali', 'Ahmed', 'Saeed'];
	friends.push("Naeem");
```
3. add an element to beginning of an array.
```
	const friends = ['Ali', 'Ahmed', 'Saeed'];
	friends.unshift("Fazil");
```
4. remove an element from the end of an array.
```
	const friends = ['Ali', 'Ahmed', 'Saeed'];
	friends.pop();
```
5. remove an element from the beginning of an array.
```
	const friends = ['Ali', 'Ahmed', 'Saeed'];
	friends.shift();
```

---
 ##### How to get index of an element

1. Replace an old element by new element.
```
	const friends = ['Ali', 'Ahmed', 'Saeed'];
	friends[1] = "Moahmed";
```
---
#### 3. Objects



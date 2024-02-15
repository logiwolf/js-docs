# js-docs
this is a js notes from i have learned

### github markup link
[GitHub markup link : the link to the next,  show how to makeup github readme file] (https://markdown-it.github.io/)


## workspace configuration
### add/configure user snippet
1. -> click code code icon from left corner of window    -> select setting    -> select configure user snippets
   -> new global snippet file / select exciting snippet
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

 ### customerize prettier extension style

 -> create new file called .prettierrc     -> add code shown below

 ```
{
  "singleQuote": true,
  "arrowParens": "avoid"
}

```
-> save the file 

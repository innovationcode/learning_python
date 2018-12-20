# learning_python
*	Python is a great language for the beginner programmers and supports the development of a wide range of applications, from simple text 	
	processing to WWW browsers to games.
*	Many Languages require the program to compile(traslate) into a form that machine understands.
	
	For e.g.--

			`Java source code  ----->  compile     ----------->  execute`
			   `Hello.java   ------->  byte code (.class) ---->  output`

	Python is instead directly interpreted into machine instructions.

			`Python source code  ----->  interpret  ------> putput`                                                                           
	        `Hello.py         ------->  output`

*   Python is case-sensitive.

*   Python Identifiers --->
	Here are following identifier naming convention for Python: 
		–Class names start with an uppercase letter and all other identifiers with a lowercase letter. 
		–Starting an identifier with a single leading underscore indicates by convention that the identifier is meant to be private. –Starting an identifier with two leading underscores indicates a strongly private identifier. 
		–If the identifier also ends with two trailing underscores, the identifier is a language-defined special name. 

*	Reserved Words --->
	Keywords contain lowercase letters only. 

		`and				exec 				not 				assert 		finally`		
		`or 				break 				for 				pass  		class`
		`from 			print 				continue 			global 		raise` 
		`def  			if 					return 				del 		import` 
		`try 			elif 				in 					while 	 	else` 	
		`is 				with 				except 				lambda 		yield` 

*	Indentation  --->
	In Python there are no braces to indicate blocks of code for class and function definitions or flow control. Blocks of code are denoted by line indentation, which is rigidly enforced.

	For e.g.	
		`Java`											
		`int sum(int a, int b) `
		 `{`							
				`return a + b;`									
		 `}`

		 `Python`
		 		`def sum(a, b) :`
		 		`return a+b`

*	Multi-Line Statements --->
	Statements in Python typically end with a new line. Python does, however, allow the use of the line continuation character ('\') to denote that the line should continue. 

	For e.g. 
	 	`total = item_one + \ 
	    	    item_two + \ 
	         	item_three `

	Statements contained within the [], {}, or () brackets do not need to use the line continuation character. 

	For e.g.
		`days = ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday'] `

*	With single ('), double (") quotes, in python triple quotes can be used to span the string across multiple lines. 
	
	For e.g., 
		word = 'word'

		sentence = "This is a sentence." 
		
		paragraph = """This is a paragraph. It is made up of multiple lines and sentences."""
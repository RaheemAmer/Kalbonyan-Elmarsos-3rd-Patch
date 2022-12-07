# Learn Programming Fundamentals

![100%](https://progress-bar.dev/100/?title=Done)
<br />

- ## PROGRAMMING FOUNDATIONS Introduction

  - [x] `in progress` `2h 10m` - 01 - [Programming Foundations: Fundamentals](https://www.linkedin.com/learning/programming-foundations-fundamentals-3/the-fundamentals-of-programming?autoplay=true&contextUrn=urn%3Ali%3AlyndaLearningPath%3A56db2b643dd5596be4e4989b)
  - [x] `in progress` `2h 4m` - 02 - [Programming Foundations: Beyond the Fundamentals](https://www.linkedin.com/learning/programming-foundations-beyond-the-fundamentals/broadening-your-knowledge-of-programming-fundamentals?autoplay=true&contextUrn=urn%3Ali%3AlyndaLearningPath%3A56db2b643dd5596be4e4989b)

<img src="https://img.shields.io/badge/Total%20Number%20Of%20Hours%20For%20This%20Courses-4h14m-blue">

# Notes

<details>
  <summary>Programming Foundations: Fundamentals</summary>
	
	bug - error - crash

	order of steps is vital - 

	after writing code on text editor, opening it won’t run the program, cause python is an interpreted language and to run it we need an interpreter to run it

	Double-clicking does not run the Python Interpreter on the source code.

	---

	Three main ways to translate source code:

	1. compile → write our code then compiler acts like translation server and compiles code and the receiver would never know the original code (Hight level compiled into low level machine language)  

	    **EX → c, c++ and objective c** 

	2. interpret → send code and then use someone who knows it to read every line (process source code line by line using interpreter)

	    **EX → PHP and JavaScript**

	3. combination

	    **EX** → Java, c# and python


	---

	**Enhanced text editors (IDE - integrated development environments)**

	IntelliSense→ help with suggestions while typing

	---

	syntax - the rules of programming language

	syntax highlighting

	run selected line to debug it

	---

	statements - expressions - operators

	---

	### Errors Categories

	1. Syntax - language rules broken
	2. Runtime - unable to execute (DivisonbyError)
	3. Semantic - unexpected output (print alice - print name - print Name)

	---

	To get Python code suggestions, you need to tell VS Code which Python interpreter to use.

	`2 * 3 + 2 * 5` → 16

	---

	`exit()` to make Python exit command-line prompt

	---

	computer gives us space in memory to store data using variables

	---

	java is a static typed language

	python and Js are both dynamic = gets the data type from the stored value in the variable

	---

	python treats decimal as  floats in the most precise way while JavaScript no

	---

	conditional or Boolean expressions or relational operators, ==

	```python
	if 5 < 6:
		return True #block
	else
		return False #block
	```

	---

	```python
	def testMe():

	```

	parameters - arguments

	<aside>
	⚠️ void means a function doesn’t return a value

	</aside>
</details>  

<details>
		<summary> Programming Foundations: Beyond the Fundamentals </summary>
	Collection - grouping related stuff [list]

	```python
	#list
	cities = [
		"l1",
		"l2",
		"l3"
	]
	print(cities[1])

	#dict
	cities = {
		"id":"l1",
		"animal":"cat"
	}

	print(cities["id"])
	```

	<aside>
	⚠️ mutable vs immutable collections (defers from programming language to another)

	</aside>

	<aside>
	⚠️ in python, a tuple is an immutable list

	</aside>

	<aside>
	⚠️ list in  python, is array in JavaScript and c++

	</aside>

	<aside>
	⚠️ Dicts are also known as associative arrays - maps - tables

	</aside>

	---

	for is used to create a loop - iteration

	```python
	cities = [
		"l1",
		"l2",
		"l3"
	]

	for city in cities:
		print(city)

	# i= iterator
	i = 5
	while i <= 100:
		print(i)
		i+=5
	print("list done")

	fruits = [
		"pinapple",
		"strawberry",
		"mango"
	]

	print("our fruit selection: ")
	for fruit in fruits:
		print(fruit)
	```

	---

	**module** - python file that contains code using import 

	**package or library** → using multiple modules together to be used in a group (using ingredients to cook a  cake)

	**framework** →  when a set of code is not just used together but used in a specific way (buying ready cake) - A framework gives you a structure to use as a starting point and customize.

	```python
	import testmodule
	testmodule.mult(10,5)
	```

	---

	concatenation - using methods like find or index

	slice notation → string[start:end]

	---

	regular expression → create a description of a pattern that you want to match

	---

	```python
	distanceInMiles = float(input("Please enter desired value to be  converted: "))
	distanceInKm = distanceInMiles * 1.689344
	print("The converted value is: ", distanceInKm )
	```

	---

	Code style

	airbnb style guide

	---

	pseudocode

	---

	input and output in python

	```python
	infile = open("values.txt", "rt")
	infile.close()
	```

	---

	### Debugging

	1. Syntax error
	    - a loop that counts in the wrong direction
	2. Runtime error 
	    - calling a function that doesn't exist
	    - referencing a variable name that isn't defined
	3. Logic error
	    - a loop that counts in the wrong direction

	---

	### IDE

	1. Syntax highlighting
	2. Auto Completetion
	3. Linting → finding bugs before execution

	Each programming language has an IDE suitable for it’s needs

	---

	### Test Cases

	to check logic errors

	---

	### (OOP) Object

	<aside>
	⚠️ Each object has behaviors, which are built using methods.

	</aside>

	has: 

	1. methods
	2. properties

	---

	### Why aren't all possible methods made available to every object?

	<aside>
	⚠️ to avoid overloading computer memory with unneeded methods, If all objects had access to all methods in the language, your programs would need more computer memory.

	</aside>

	---

	Memory leak - Garbage collection (a compiler keeps track of which items in memory are no longer needed and deletes them automatically)

	Multi-threading

	Algorithms
</details>

# Certificates

![image](https://user-images.githubusercontent.com/18606136/205850580-981680fe-a56d-439a-b9cf-e96ca41066b6.png)

---

![image](https://user-images.githubusercontent.com/18606136/206301083-1fc350f6-328e-4aa9-8a56-b18e864ba686.png)


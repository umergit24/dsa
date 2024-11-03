---
link: https://www.youtube.com/playlist?list=PLu0CiQ7bzwER_9WMqWsv4TGrohhwHm5zE
---
#dsa
## algos


- linear search
- binary search

> [!code output for linear v binary search]
> ![[Pasted image 20240717213558.png]]

-  big-o
	- for judging and analysing algorithms efficiency
	- linear search : o(n)  "Linear Time"
		- time taken for function to complete depends on input size
		- n is the number of terms 
		- o is the steps taken / number of operations
	- binary search : o log(n)    "Logarithmic Time"
		- so log base 2 of 128 is 7 and log base 2 of 64 is 6
		- so for any number between 64 and 128, it takes 7 steps as shown above
		- not sure about this though
	- determined by worst case scenario
	- o(1)  "Constant Time"
		- same time taken for function to complete despite the number of inputs
		- independent from size of input
		- requires one operation
		- no iteration
		- e.g
			- takes a list, returns a specific index of the list as the list has direct access to any index in it
	- "Quadratic time" o(n^2)
		- e.g bubble sort
	- "Linearithmic time" o(n log(n))
		- e.g merge and sort
		- for unsorted lists




# computer memory and linked lists



grokking algo book
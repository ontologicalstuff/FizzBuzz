# FizzBuzz

This is the classic FizzBuzz coding challenge for neophytes. The problem, as stated in The Odin Project, reads: 

	Write a program that takes a user’s input and prints the numbers from one to the number the user entered. However, for multiples 	 of three print Fizz instead of the number and for the multiples of five print Buzz. For numbers which are multiples of both 		three and five print FizzBuzz.
	
Following the problem solving principle of "divide and conquer," I decompose the problem into the following subproblems: 

(1) "... that takes a user's input..." --> Program should include the prompt function. Consider setting a variable to capture the user's input. 

(2) "...prints the numbers from one to the number user entered." --> Program should display 1... n number. Thus, for example, if the user entered 5, then output should be 1, 2, 3, 4, 5. This implies a loop. Consider a for loop.

(3) "for multiples of [3] print Fizz instead of the number." --> Thus, (1, 2, 3, 4, 5) would be (1, 2, Fizz, 4, 5). This also implies the remainder % operator, since all multiples of 3 divided by three have a zero remainder. 

(4) "multiples of five print Buzz." --> Thus, (1, 2, Fizz, 4, 5) = (1, 2, Fizz, 4, Buzz.)

(5) "for numbers which are multiples of both three and five print FizzBuzz." --> If it number inputted by the user were 15, then (1, 2, Fizz, 4, Buzz... 14, FizzBuzz) would be the answer.

Download Link: https://assignmentchef.com/product/solved-cs302-assignment-1-fun-with-recursion
<br>
<h1>Description</h1>

In this assignment, you will implement a series of problems using recursion, the problems are:

<ol>

 <li>Output a series of stars (refer to the sample output), you will need to implement the following recursive functions to perform this problem

  <ul>

   <li>void printStarsIncreasing(int) – a function that prints out stars in a right triangle form, the first line has one star, the next row has two stars, the next row has three stars up to the integer passed in, if I pass in the value 4, then this function prints out one line with one star, next line with two stars, the next line with three stars, and the last line with 4 stars</li>

   <li>void printStarsDecreasing(int) – a function that prints out stars in a right triangle form using an integer passed in, the first line prints out the amount of stars passed into the function, the next line prints out one less star and so on, if I pass in the value 4, the first line prints out four stars, the next line prints out three stars, the next line prints out two stars, and the last line prints out one star</li>

   <li>void printStarsUtil(int) – this function takes in an integer and prints out that amount of stars, this function will be used in the printStarsIncreasing and printStarsDecreasing</li>

  </ul></li>

</ol>

You can visualize the problem in a way that you would need two nested loops, think of printStarsUtil as the inner loop and printStarsIncreasing and printStarsDecreasing as the two separate outer loops

<ol start="2">

 <li>Verify if a string is a palindrome using the following recursive function: bool isPalindrome(string), the function takes in string object and returns true if the string is a palindrome and false otherwise, a palindrome is a string that reads the same from left to right and right to left</li>

 <li>Verify if the digits in a given number is increasing from left to right using the following recursive function: bool increasingDigits(unsigned long long) returns true if the number read from left to right is non decreasing, i.e. if I pass in 1234 or 111345 would return true and for 2314 or 98653 would return false</li>

</ol>

<h1>Specifications</h1>

<ul>

 <li>Comment your code and your functions</li>

 <li>Do not modify the function prototypes</li>

 <li>Do not use global variables</li>

 <li>Everything must be recursive, you can only use a loop structure for input</li>

</ul>

<h1>Example Output</h1>

$ g++ Assignment01.cpp

$ ./a.out

Enter the width: hi Seriously?! Wow!

Enter the width: -9 Seriously?! Wow!

Enter the width: 0 Seriously?! Wow!

Enter the width: 4

*

**

***

****

****

***

**

*

Ok hopefully that worked Enter a string: racecar racecar is a palindrome, nicely done

Hopefully we are still doing alright, last part

Enter a number: 1222345

Looks like the digits are increasing from left to right

$ ./a.out

Enter the width: 3

*

**

***

***

**

*

Ok hopefully that worked

Enter a string: everyvillainislemons

Oh well, everyvillainislemons is not a palindrome

Hopefully we are still doing alright, last part Enter a number: hi

Can we just NOT do this again?!?!?!?!

Enter a number: 2345671

Digits do not increase from left to right, oh well



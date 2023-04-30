Download Link: https://assignmentchef.com/product/solved-ensf594-principles-of-software-development-ii-lab-assignment-1
<br>
<strong>Question 1: (1 marks) </strong>

For algorithm A, If the exact number of steps is T(n)=2n+3n<sup>2</sup>−1 what is the Big O? Explain.  <strong> </strong>

<h1>Question 2: (2 marks)</h1>

Consider the below functions we discussed in our lecture:

<em>Linear, logarithmic, exponential, quadratic, constant, cubic, </em>

Write the above function from top to bottom order from most to least efficient.

<strong> </strong>

<h1>Question 3: (3 marks)</h1>

Consider the below code fragment:

int test = 0;     for (int i = 0; i &lt; n; i++){         for (int j = 0; j &lt; n; j++){             test = test + i * j;

}

}




What is its Big-O running time? Explain your answer.

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<h1>Question 4:  (3 marks)</h1>

Consider the below code fragment:

int func(){     int test = 0;     for (int i = 0; i &lt; n; i++){         test = test + 1;

}

for (int j = 0; j &lt; n; j++){         test = test – 1;

}

return 0;

}




What is its Big-O running time? Explain your answer.




<h1>Question 5: (4 marks)</h1>

Consider the below code fragment:

int func(){

int i = n;     int count = 0;     while (i &gt; 0){         count = count + 1;

i = i // 2;

}

return 0;

}




What is its Big-O running time? Explain your answer.




<strong>Question 6:</strong> Write a scenario (or a code fragment), whose complexity is O(n<sup>3</sup>)    <strong>(3 marks)</strong><sup>  </sup>

<strong>Question 7:</strong> If an algorithm performing at O(n<sup>2</sup>) has the integer 7 as input, what is the worst case scenario for the algorithm?  <strong>(1 marks)</strong>










<strong>Question 8:</strong> Use Big O Notation to describe the time complexity of the following function that determines whether a given year is a leap year:  <strong>(1 marks)</strong> bool isLeapYear(year) {              return (year % 100 === 0) ? (year % 400 === 0) : (year % 4 === 0);

}

<strong>Question 9:</strong> Use Big O Notation to describe the time complexity of this function, which is below: <strong>(3 marks)</strong> int chessboardSpace(numberOfGrains)

{   chessboardSpaces = 1;         placedGrains = 1;         while (placedGrains &lt; numberOfGrains) {      placedGrains *= 2; chessboardSpaces += 1;

}

return chessboardSpaces; }




Explain your answer.

<strong>Question 10:</strong> Consider the code below:   <strong>(4 marks)</strong>




In our lecture, we have done an example about calculating the primitive operations and then determines the complexity. First identify the primitive operation of every line, and then calculate the Big-O of the above code? Also mention the class of growth rate function.

<strong>Question 11:</strong> In our lecture, we have discussed the Big Omega represents the lower bond. What is the lower bound of the below function:

<em>3nlogn – 2n  </em>










Notes for Submission:

You should submit a single PDF file for all the questions in this lab assignments. Submit clearly the question number in your pdf file. Use D2L to submit the pdf file

<strong> </strong>
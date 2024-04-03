# What-did-I-Learn-pt2


### What can you add from your own perspective about chapter 3?
In chapyer 3, it talks about the topic of functions, which is fundamental building block in JavaScript.
One perspective that comes from this chatper is the importance of understanding functions and not just as a tool 
for organizing code, but also as a modularity. By encapsulating logic within the functions, developers can create 
reusable and modular pieces of code, leading to more maintainable and scable software.


### Are the concepts relatable to anything in the course or your own life?
When it comes down to this chapter relating to the course. I will defiently give it a thumbs up.
This course is mainly getting future developers used to and ready for bigger coding languages you will need in order
to futhur your education in this carer field. But on the other hand, everything iv been learning up to now dosent have 
a big play in my day to day life. 


### What are some examples that helped you understand the concepts better? 
Through out my read i was having a hard time understand the concept until seeing an example. 
Like this example:

const makeNoise = function() {
  console.log("Pling!");
};

makeNoise();
// → Pling!

const roundTo = function(n, step) {
  let remainder = n % step;
  return n - remainder + (remainder < step / 2 ? 0 : step);
};

console.log(roundTo(23, 10));
// → 20


Im starting to understand this some what. But I do still very much feel I would need to have a real
life stiuation to understand this code better. In chapter 3, it basically said 
functions, such as roundTo and square, produce a value, and some don’t, such as makeNoise, whose only result is a side effect. 
A return statement determines the value the function returns. When control comes across such a statement, it immediately jumps 
out of the current function and gives the returned value to the code that called the function. 
A return keyword without an expression after it will cause the function to return undefined. But when would I use this function?


### What was new about this chapter?
  __The Recursion function__:
Recursion allows some functions to be written in a different style. Take, for example, this power function, which does the same as the (exponentiation) operator.
  

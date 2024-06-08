For loop
For loops are a fundamental construct in programming used to iterate over a sequence of elements.
They allow you to execute a block of code repeatedly for each item in the sequence. 
The basic syntax of a for loop varies slightly depending on the programming language, but the general structure is similar as below;
Initialization: The loop starts by initializing a variable (often called item, but it can be named anything) to the first element of the sequence.
Iteration: The loop then executes the block of code inside it with the current value of the variable.
Update: After executing the block of code, the loop updates the variable to the next value in the sequence.
Repeat: Steps 2 and 3 are repeated until there are no more elements in the sequence.
An example of iterating through an array using for loop;
for (let i = 0; i < arr.length; i++) {
  console.log(arr[i]);
}
For loops are versatile and can be used with different types of sequences, such as lists, tuples, dictionaries, and strings. 
They provide a convenient way to perform repetitive tasks without needing to write the same code multiple times.

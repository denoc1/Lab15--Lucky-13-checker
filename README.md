# Lab15--Lucky-13-checker

## Objective
Write a program that generates a series of random numbers and tracks whether a specific number (13) appears.

---

## Instructions

1. **Method**
   
   You need to have one method called `printTwoDigit` that accepts an integer parameter `n`.  You may assume `n >= 0`.

   The method will generate `n` random integers in the range **10 - 19 inclusive**, with each number equally likely.

   Print each number as it is generated.  (Numbers can be printed on the same line, with a space in between, or on separate lines.)

   Use a boolean flag to keep track of whether the number `13` appears at least once.

   After printing all of the numbers, the method should return `true` if the number `13` appeared, return `false` if `13` did not appear

 2.  **Main method**
    
        After asking the user for the number of values to generate, the main method will call the function `printTwoDigit` and pass the user's value.  After the flag is returned, the main method will then display one of the following messages:
       - `"Lucky 13!"` - if 13 appeared at least once
       - `"You were unlucky!"`  - if 13 did not appear
     
         
4.  **Edge Cases**
   
     If `n` is 0, print `"No numbers to generate."`


## Requirements
- Include standard method and program header documentation.
- Use Math.random() to generate the random numbers.

Sample output:

            Enter a number:  5
            12 19 13 15 10
            Lucky 13!
            
            Enter a number: 7
            10 12 15 19 11 12 17
            You were unlucky!
            
            Enter a number: 0
            No numbers to generate




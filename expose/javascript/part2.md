# Part 2 - Solutions

1. Here, we print '3' to the console. This is the value of 'i' after the loop variable is incremented, equal to the length of the 'prices' array. Since we used *var* to make 'i', it has a function scope, so we can access it outside the loop.

2. Here, we print '150' to the console. This is the discount for the last entry in the 'prices' array, and as such gets "saved" to the 'discountedPrice' variable. Again, this variable has a function scope, so we can print it outside the loop. 

3. Here, we print '150' to the console. This is the same as the last value as line 14 of the code helps round deciaml values. Since the final price was an integer to begin with, nothing changes, and all the same reasons for printing as the last question apply. 

4. The function will return the array [50, 100, 150]. This is the correct output of the function as essentially, we apply the discount of 50% to all of the input prices, and return the new array of the same length with discounted prices. As the loop had no errors, the code ran as expected, giving us 0.5 times all the original prices as output. 

5. Here, the code contains an error - as 'i' is declared with block scope, we cannot access it outside of the loop. 

6. Here, the code again contains an error - as 'discountedPrice' has a block scope, we can't access it outside the loop.

7. Here, we print '150' to the console. As 'finalPrice' has function scope (it has block scope, but the block it is declared in is the whole function), we can print it like last time. Thus, we print final discounted price from the input array.

8. This code will return [50, 100, 150], exactly like last time. This is because changing the scope of each variable in this case did not alter the execution of the code, as all variables were changed within their own blocks. 

9. Here, the code has an error - as 'i' is declared with block scope, we cannot access it outside of the loop. 

10. Here, we print '3' to the console. 'length' is a constant within the scope of the print, and we never reassign it. So, the code executes as expected and outputs '3'. 

11. This code will return [50, 100, 150], exactly like the last two times. We might think that declaring the 'discounted' array as a constant causes issues, but that simply declares it as a constant reference. We can still alter the constant array, as long as we do not try to reassign 'discounted'. So, the code executes as expected, giving the same output as last time. 

12. Answers labelled :
    A] student.name
    
    B] student['Grad Year']
    
    C] student.greeting()
    
    D] student['Favorite Teacher'].name
    
    E] student.courseload[0]

13. Answers labelled :
    A] Answer : '32' 
       Explanation : Here, as we have a string involved, we concatenate the string representation of the integer.

    B] Answer : 1
       Explanation : Here, no string conversion is done as we use the subtraction operator. All arguments are converted to numbers and subtracted as expected. 

    C] Answer : 3 
       Explanation : Here, null is interpreted as zero, and addition occurs as normal.

    D] Answer : '3null'
       Explanation : Here, as there is a string involved, we convert both arguments to strings and concatenate.

    E] Answer : 4
       Explanation : Here, true is interpreted as 1, and addition occurs as normal.

    F] Answer : 0
       Explanation : Here, both false and null are interpreted as 0, and added as normal.

    G] Answer : '3undefined'
       Explanation : Here, as there is a string involved, we convert both arguments to strings and concatenate.

    H] Answer : NaN
       Explanation : Here, no string conversion is done as we use the subtraction operator. All arguments are converted to numbers, but 'undefined' cannot be converted properly. So, subtraction results in 'Not a Number'.

14. Answers labelled :
    A] Answer : true 
       Explanation : Here, we convert both arguments to numbers and compare as expected.

    B] Answer : false
       Explanation : Here, strings are compared in lexicographic order - as '12' comes before '2' in a dictionary, the output is false.

    C] Answer : true 
       Explanation : Here, we convert both arguments to numbers and compare as expected.

    D] Answer : false
       Explanation : Here, the '===' operator does not convert types, so we get false as we compare a string directly to an integer. 

    E] Answer : false
       Explanation : Here, true is converted to 1, and comparison occurs as normal.

    F] Answer : true
       Explanation : Here, Boolean(2) explicitly outputs a boolean value of 'true', which is strictly compared to another boolean value of 'true', which are equal.

15. The '==' operator will perform type conversions to make the two arguments the same type, then perform a comparison according to type. The '===' operator also compares the types of the two arguments, meaning if the arguments do not start as the same type, they are not equal. 

16. See 'part2-question16.js' file in folder

17. Here, the 'doSomething' function that is passed as a parameter is one that takes a number, and returns that number multiplied by 2. So, once we pass that function as a parameter, in the 'modifyArray' function, we pass in the values of 'array' as parameters to the 'doSomething' function, which doubles them. So, if we were to print the output, we would have an array of the same length as the input 'array', whose elements are twice that of 'array'.

18. See 'part2-question18.js' file in folder

19. The output will be '1 4 3 2'.

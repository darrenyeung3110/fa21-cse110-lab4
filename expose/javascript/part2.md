1. 3 because i is global and the for loop terminates when i is greater than or equal to 3
2. 150 because the last discounted price is 150 and i is global
3. 150 because finalprice is keeping track of the last updated price in the list and it is global
4. It will return a list of three values: 50, 100, and 150
5. There will be an error because we are using let as the keyword, the variable i is no longer accessible after the scope of the for loop
6. There will be an error because discountedPrice is declared with let and it is only accessible within the block of the for loop. The console.log is outside the forloop  so it won't be able to access it 
7. 150 because final price is keeping track of the last updated price in the list 
8. it will return a list with the values 50, 100, 150 because it pushes back the discounted price after each iteration for each original price
9. There will be an error because i is defined with let which is only visible in the for loop scope 
10. 3 because it will print out the length of the prices array which was stored initially in a const varaible in the beginning of the function
11. It will return a list with values 50, 100, 150 because it pushes back the discounted price after each iteration for each original price
12. 
- student.name
- student["Grad year"] 
- student.greeting();
- student["Favorite Teacher"].name
- student.courseLoad[0]

13. 
- '32' because 2 maps to string and string concatenation is done with +
- 1 because you cannot perform substraction on strings so js converts the '3' to a number
- 3 because null converts to zero 
- '3null' because null converts to "null"
- 4 because true converts to 1 
- 0 because both false and null converts to 0
- '3undefined' because undefined converted to "undefined in string concatenation"
- NaN because we are not doing string concatenation and this is treated as a mathematical expression. When we try to subtract undefined, it gets conveted to NaN and whenever there is NaN in an expression, it turns the whole thing into NaN

14.
- true because  '2' becomes the number 2 
- false because '12' is lexicographically smaller than '2' ('1' comes before '2' in the dictionary)
- true because '2' becomes the number 2 
- false because === is strict equality and this check does not type convert and because string 2 is different from int 2, it is false
- false because true becomes 1 and 1 != 2
- true because in the Boolean() fucntion, everything with a value is true while everything without a value is false: 0, empty string, undefined, and null
  
15. == converts the variable values to the same type before performing comparison so there is implicit conversion involved. === is strict equality which doesn't convert at all, so when two different types are used, it is for sure a false 

16. look at js file
17. a list with 2, 4, 6 should be returned. so doSomething is a function that takes a number and returns 2 times that number. In JS, functions are first class objects. we pass an array [1,2,3] and this said function to another function called modifyarray. modifyarray will for each element in the paramter array, apply the passed in function (in this case, doSomething()) to each element in the array and pushes that to the new array. It then returns the new array in the end with all the new elements that had doSomething() applied on the original elements which multiplies by 2. Hence [1,2,3] became [2,4,6]

18. look at js file 

19.
1 
4
3
2

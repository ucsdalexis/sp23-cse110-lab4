# Part 2. A Little More of a Challenge

## var declaration 
1. `3` is printed.<br> This is because there are 3 items in `prices` and the value of `i` goes to the length of `prices` in the for loop. <br>
2. `150`  is printed.<br> This is because this is the value of the final `discountedPrice` in the array `prices` after applying the discount by multiplying last value in the array with `(1 - discount)`. <br>
3. `150`  is printed.<br> This is because `finalPrice` should be the same value as `discountedPrice` but rounded to the nearest hundredth. <br>
4. `[ 50, 100, 150 ]` is returned.<br> This is because the function returns an array filled with number from `prices` after applying the discount. <br>


## let declaration
5. At line 12, a `ReferenceError` is caused because `i` isn't defined because `let` makes the variable `i` only accessable within the for loop block it is defined in. <br>
6. At line 13, a `ReferenceError` is caused because `discountedPrice` isn't defined because `let` makes the variable `discountedPrice` only accessable within the for loop block it is defined in. <br>
7. At line 14, `150`  is printed. This is because `finalPrice` was called within the same block it was defined in.  <br>
8. `[ 50, 100, 150 ]` is returned.<br> This is because the function returns an array filled with number from `prices` after applying the discount. The scope of each variable is only needed within the blocks they were declared in, so no error occurs. <br>


## const declaration
9. At line 11, a `ReferenceError` is caused because `i` isn't defined because `let` makes the variable `i` only accessable within the for loop block it is defined in. <br>
10. At line 12, `3`  is printed. This is because `length` was called within the same block it was defined in and never reassigned to a different value.  <br>
11. `[ 50, 100, 150 ]` is returned.<br> This is because the function returns an array filled with number from `prices` after applying the discount. The scope of each variable is only needed within the blocks they were declared in, so no error occurs. All variables declared with the const declaration are never reassigned either so no error occurs on that end. <br>


## Data Types
12. a. `student.name` <br> 
    b. `student['Grad Year']` <br>
    c. `student.greeting()` <br> 
    d. `student['Favorite Teacher'].name` <br> 
    e. `student.courseLoad[0]` <br>


## Basic Operators & Type Conversion
13. a. ‘3’ + 2 <br> `32` is the output. This is because integers map to their exact string representation.<br>
    b. ‘3’ - 2 <br> `1` is the output. This is because subtraction tries to convert both operands to numbers.<br>
    c. 3 + null <br> `3` is the output. This is because when you add a number to null, the null value changes to 0.<br>
    d. ‘3’ + null <br> `3null` is the output. This is because when you add a string to null, the null value changes to the string 'null'.<br>
    e. true + 3 <br> `4` is the output. This is because when you add a boolean and a number the true changes to a 1.<br>
    f. false + null <br> `0` is the output. This is because when adding a boolean and null, both change to 0. <br>
    g. '3' + undefined <br> `3undefined` is the output. This is because when you add a string to undefined, undefined is changed to the string 'undefined'.<br>
    h. '3' - undefined <br> `NaN` is the output. This is because when you subtract a string with undefined, undefined changes to the value NaN and basically any operation with NaN will result in NaN. <br>
14. a. '2' > 1 <br> `true` is the output. This is because '2' is changed to a number and 2 is greater than 1. <br>
    b. '2' < '12' <br> `false` is the output. This is because in string comparison, the strings are compared character by character therefore '2' is not less than '1'. <br>
    c. 2 == '2' <br> `true` is the output. This is because '22 is changed to a number and 2 is equal to 2.<br>
    d. 2 === '2' <br> `false` is the output. This is because === checks the equality without type conversion and 2 is not the same as '2'. <br>
    e. true == 2 <br> `false` is the output. This is because true is changed to 1 and 1 is not equal to 2. <br>
    f. true === Boolean(2) <br> `true` is the output. This is because Boolean(2) is converted to true and true is equal to true. <br>
15. The double equality sign `==` means the equality test while converting the values to numbers when comparing different values. On the other hand, a strict equality operator `===` checks the equality without type conversion. <br>


## Function
17. `[ 2, 4, 6 ]` is the result. The function `modifyArray` takes an array and preforms the function `doSomething` on every single item in the array which was passed through the parameters of `modifyArray`.


## setInterval(), setTimeout(), clearTimeout()
19. `1` <br> `4` <br> `3` <br> `2` <br>
# Part 2 Answers

1. Line 12 will print `3` because this is the last value of `i` before it exits the for-loop and the `var` keyword allows for global scope.
2. Line 13 will print `150` because this is the last value stored in `discountedPrice` and again the `var` keyword allows for global scope.
3. Line 14 will also print `150` as this is the last value of `finalPrice`.
4. The function will return an array of discounted prices based on the discount specified in the parameter and applied to the list of prices passed in. The for-loop calculates the discounted price of each original price and stores it in a new array, which is then returned from the function after all the discounts have been calculated.
5. There will be a `ReferenceError` because `i` is not defined outside the scope of the for-loop as per the keyword `let`.
6. Similar to the previous answer, there will be a `ReferenceError` because `discountedPrice` is only accessible within the for-loop and cannot be logged outside of it.
7. Line 14 prints `150` because the last stored value in `finalPrice` is `150` and since the variable is defined outside of the for-loop, it can be accessed outside of the for-loop.
8. The function still returns an array of discounted prices because changing all of the `var` keywords to `let` doesn't affect the functionality in any way besides the scope of each variable.
9. Similar to Question 5, there will be a `ReferenceError` because `i` is not defined outside the scope of the for-loop as per the keyword `let`.
10. Line 12 will print `3` because that is the length of the array passed in to the function, which is set to the variable `length`.
11. The function works as expected and returns an array of discounted prices. Every loop in the for-loop redefines the variable `discountedPrice` which allows it to be recalculated each time before being pushed to the `discounted` array.
12. 
    1.  `student.name`
    2.  `student['Grad Year']`
    3.  `student.greeting()`
    4.  `student['Favorite Teacher'].name`
    5.  `student.courseLoad[0]`
13. 
    1. `'32'`: the `2` gets converted to a string and is concatenated to the `'3'`
    2. `1`: the `'3'` gets converted to an integer and `2` is subtracted from it
    3. `3`: `null` is considered `0` as an integer
    4. `'3null'`: here `null` is registered as the string `'null'` and then concatenated to `'3'`
    5. `4`: the `true` is converted to a `1` as an integer
    6. `0`: both `false` and `null` are considered `0` as integers
    7. `'3undefined'`: the `undefined` gets converted to a string and is concatenated to the `'3'`
    8. `NaN`: the `'3'` is converted to a number but you cannot subtract `undefined` from a number
14. 
    1.  `true`: the `'2'` is converted to an integer for the comparison
    2.  `false`: the ASCII value of `'2'` is greater than that of the characters `'12'`
    3.  `true`: the `'2'` is converted to an integer for the comparison
    4.  `false`: the triple equals checks datatype as well and as they are not the same, the comparison returns `false`
    5.  `false`: `true` is equivalent to `1` which is not equal to `2`
    6.  `true`: `2` as a boolean is `true`, which is the same datatype and value as `true`
15. The double equals operator (`==`) checks for equality of value disregarding datatype whereas the triple equals operator (`===`) checks for both equality of value and datatype. 
17. The function returns `[2,4,6]`. This happens because each value in the passed array is passed in the callback function which returns twice that value, and then that result is stored in the new array.
19. The output of the code is `1`, `4`, `3`, `2`, where each value is printed on a new line.

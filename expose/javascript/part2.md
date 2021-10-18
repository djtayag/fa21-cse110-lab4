1. The function prints 3 because the for-loop incrememnts i from 0 up until the length of the prices array which is 3.
2. The function will print 150 because the for-loop will access the last price in the array (300) and half it to 150, and since the variable discountedPirce is of type var, it has scope within the function and can be accessed outside of the for-loop, so the function will print 150. 
3. The function will print 150. For the same reason as question 2, the variable finalPrice has scope within the function so it cna be accessed outside of the for-loop. The for-loop will access the last price in the array (300) and apply the discount, so finalPrice will update and store 150, so line 14 will print 150.
4. This function will return an array containing 3 discounted prices: [ 50, 100, 150 ] to the caller. This is because the function goes through the original prices array and applies the discount to each of the prices and stores them in an array called discounted. This discounted array is returned to the caller. Since the prices were [ 100, 200, 300 ], after the half-off discount is applied to each of them, the new discounted array will be [ 50, 100, 150 ].
5. This code will return an error because in line 12 we are trying to access the variable i, but i is of variable type let, so it is only accessible within the block it is defined in. i is defined in the for-loop but not within line 12's scope, so this code causes an error.
6. This code will cause an error for the same reason in question 5. the discountedPrice variable is of type let so it will only be accessible within the block that it is defined in. It is defined within the for-loop but no where after, so line 13 cannot access the variable. Therefore, line 13 will cause an error.
7. The code will print 150. Since finalPrice doesn't have a variable type, it is automatically initialized to be a global variable so it is accessible throughout the function. The for-loop will add the 50% discount to the final price in the array. So the result printed is 150 (50% of 300).
8. This function will return an array containing 3 discounted prices: [ 50, 100, 150 ] to the caller. This is because the function goes through the original prices array and applies the discount to each of the prices and stores them in an array called discounted. This discounted array is returned to the caller. Since the prices were [ 100, 200, 300 ], after the half-off discount is applied to each of them, the new discounted array will be [ 50, 100, 150 ].
9. This code will return an error because in line 11 we are trying to access the variable i, but i is of variable type let, so it is only accessible within the block it is defined in. i is defined in the for-loop but not within line 11's scope, so this code causes an error.
10. Line 12 will print 3. The length is a const variable and holds the length of the prices array which is 3. So the code will print 3.
11. This function will return an empty array because the discounted array defined at the start of the function is of type const and is initialized as empty. This variable cannot be changed so the function will return an empty array. 
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. 32; if one of the operands is a string then all operands are converted to strings too (for addition operator) so 2 is converted to string '2' and concatenated
    B. 1; the string '3' is converted to a number 3
    C. 3; null has a value of 0
    D. 3null; null is converted to string 'null' and concatenated to '3'
    E. 4; true has value 1
    F. 0; false and null both have value 0
    G. 3undefined; undefined is converted to string 'undefined' and concatenated with '3'
    H. NaN; undefined becomes NaN 
14. A. true; '2' becomes the number 2
    B. false; the strings are compared lexicographically, since '2' is greater than the '1' in '12', the expression returns false
    C. true; string '2' becomes 2
    D. false; strict quality check comparing types, string is not the same as number so it returns false
    E. false; true becomes 1 and 1 does not equal 2
    F. true; true and Boolean(2) are both of type boolean so expression is true
15. === is a strict equality operator, it checks the equality without type conversion, so if the operands are of different types, it will return false, whereas == is a regular equality check and it will convert operands of different types into operands of the same type.
16. check part2-question16.js
17. Result: the newArr will be returned to the caller updated as [ 2, 4, 6 ]. The array [1,2,3] and the function doSomething get passed into the modifyArray function as parameters. In the for-loop of the function, we iterate through the parameter array and multiple each of the elements by 2 from the doSomething function. These updated elements are pushed into the newArr and then returned by the modifyArray function.
18. see part2-question18.js 
19. 1
    4
    3
    2


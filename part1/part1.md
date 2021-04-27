## Part 1a:
1. values added: 20
2. final result: 20
3. values added: 20
4. ReferenceError because result is not within the scope outside of the if statement.
5. error because we tried to change the value of a const variable.
6. error because we tried to chande the value of a const variable.

## Part 1b:
1. 3 will be printed because the i starts at 0 and increments until the length of prices, which is 3.
2. 150 will be printed because the last number, 300, got discounted by 0.5.
3. 150 will be printed because the last number, 300, got discounted by 0.5 then will be rounded and multiplied by 100 then divided by 100.
4. the function will return the array with all of the values discouted.
5. ReferenceError because i is not within the scope outside of the for loop.
6. ReferenceError because discountedPrice is not within the scope outside of the for loop.
7. 150 will be printed because the last number, 300, got discounted by 0.5 then will be rounded and multiplied by 100 then divided by 100 and is within the scope of the console.log.
8. the function will return the array with all of the values discouted.
9. ReferenceError because i is not within the scope outside of the for loop.
10. ReferenceError because discountedPrice is not within the scope outside of the for loop.
11. the function will return the array with all of the values discouted.
12. 1. student.name
    2. student["Grad Year"]
    3. student.greeting();
    4. student["Favorite Teacher"].name
    5. student.courseLoad[0]
13. 1. 32 -the string 3 is concatenated to the 2
    2. 1 -3 is coverted from string to int since there is no concatenate with a -
    3. 3 -null is converted into 0 when added
    4. 3null -the string 3 is concatenated to null
    5. 4 -true is converted into 1 when added
    6. 0 -false and null are converted to 0 when added
    7. 3undefined -the string 3 is concatenated to undefined
    8. NaN -3 is converted to an int, but int-undefined is not possible, therefore NaN
14. 1. true -string is converted to int 2 before comparison
    2. false -it checks the first character of both strings then compares
    3. true -the string is converted to the int then compared
    4. false -with the strict comparison, it compares type first
    5. false -2 does not converted to either true or false
    6. true -using the Boolean() function, any non empty string is true
15. The == operator converts the type of the value before comparison. The === operator does not make any type conversion before it checks for equality, so it will return false if there are different types present.
16. js
17. The function would return an array with values [2,4,6]. The array [1,2,3] gets passed through the parameter then in modifyArray, we iterate through the array and call the callback funtion with each value of the array. The callback function doSomething will multiply each value by 2 and return it, meaning the new array will have [1*2,2*2,3*2] = [2,4,6].
18. js
19. 1
    4
    3
    2
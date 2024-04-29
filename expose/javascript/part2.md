1. 3 will be printed, since `i` is in scope and has a value of 3.
2. 150 will be printed, since the last value of `discountedPrice` is `prices[2]*(1-discount) = 150`.
3. 150 will be printed, since the last value of `finalPrice` is `Math.round(discountedPrice*100)/100 = 150`.
4. This function returns `[50,100,150]`, because it calculates the 50% discount of all the prices given in `prices` and adds them to the list to be returned.
5. There will be an error as `i` is not in scope.
6. There will be an error as `discountedPrice` is not in scope.
7. 150 will be printed, since the last value of `finalPrice` is 150 and it is in scope.
8. The function returns `[50,100,150]`, because that is the content of `discounted` when it is returned.
9. There will be an error as `i` is not in scope.
10. 3 will be printed, since the length of `prices` is 3.
11. `[50,100,150]`
12. 
    1. student.name
    2. student['Grad Year']
    3. student.greeting()
    4. student['Favorite Teacher'].name
    5. student.courseLoad[0]
13. 
    1. 32, because 2 is mapped to a string
    2. 1, because '3' is mapped to an integer
    3. 3, because null is mapped to an integer
    4. 3null, because null is mapped to a string
    5. 4, because true is mapped to 1
    6. 0, because both null and false are mapped to 0
    7. 3undefined, because undefined is mapped to a string
    8. NaN, likely because undefined cannot be converted into a number.
14. 
    1. True, because '2' is mapped to an integer.
    2. False, because '2' is greater than '12' alphabetically
    3. True, because '2' is mapped to an integer.
    4. False, because '2' and 2 are not the same type
    5. False, because `true` maps to 1, not 2
    6. True, because both `true` and `Boolean(2)` are booleans with value `true`.
15. == checks for value equality without types, and === checks that both the values and the types are the same (e.g. '3' == 3 is true, '3' === 3 is false).
16. See corresponding .js file
17. `[2,4,6]` is returned, since `newArr` is filled with the elements of `array` after the function `doSomething` is performed on them.
18. See corresponding .js file
19. `1 4 3 2` (but in separate lines. I put them all on the same line because I'm a little lazy).
1. prints 3 because the for loop on line 5 increments i three times before it exits. Since i is declared var it can be accessed outside of the loop.
2. prints 150 because discountedPrice take the value of the last discounted price in the list which is 150
3. prints 150 because discountedPrice takes discountedPrice which is 150 and multiplies it by 100 and then divides by 100
4. returns [50, 100, 150]. The function takes the list of prices [100, 200, 300] and then applies a 0.5 discount and then returns the array back.
5. error because i is declared as let i and can only be accessed within the scope of the for loop. So i cannot be accped at line 12 since it is outside the scope.
6. error because discountedprice is declared with let and can only be accessed inside the scope of the for loop which line 13 is not.
7. 150 because finalPrice is declared in the same scope and it returns the last price on the list which is 150.
8. [50, 100, 150] since it returns all of the discounted prices
9. error because i is declared as let, so it's scope is the for loop and line 11 is outside of the scope of the for loop
10. 3 because length is set to the length of the prices array and it is also const
11. [50, 100, 150] because the function returns the list of prices after puting the discount on them
12. Q12
    1.  student.name;
    2.  student['Grad Year'];
    3.  student.greeting();
    4.  student['Favorite Teacher'].name;
    5.  student.courseLoad[0];
13. Q13
    1.  '32' because 2 is mapped to its string representation which is '2' and is concateneated to '3'
    2.  1 because integers can be subtracted, so '3' becames 3 and then 3-2=1
    3.  3 because null becomes 0 and 3+0=3
    4.  '3null' because null becomes the string 'null' and is then concatenated to '3'
    5.  4 because true becomes 1 and 1+3=4
    6.  0 because false becomes 0 and null becomes 0 so 0+0=0
    7.  '3undefined' because undefined becomes the string 'undefined' and then is concatenated to '3'
    8.  NaN because undefined becomes NaN when it is changed to a number. '3' is also changed to 3 and 3-NaN becomes NaN.
14. Q14
    1.  True because '2' is converted to an integer since we are comparing two different types of variables and 2>1
    2.  False because we are comparing the strings lexographically, '2'<'12' is false
    3.  True because '2' is converted to an integer since we are comparing two different types of variales and 2==2
    4.  False because === checks for equality without a type conversion and 2 is not the same type as '2'
    5.  False because true becomes 1 but 1 does not equal 2
    6.  True because Boolean(2) becomes true and true === true
15. == compares if two values are the same after converting the variables to the same type  while === checks if the value and the type are the same
16. check other file
17. [2, 4, 6] is returned. First the modifyArray is called with the arugments [1, 2, 3] and doSomething is set as the callback function.  Then in the for loop we can see we are iterating through the array [1, 2, 3] and each time we are using the callback function each value and pushing the result onto a new array. The callback is calling the doSomething function which is doubling each value and returning it. This results in [2, 4, 6].
18.  check other file
19.  1 4 3 2
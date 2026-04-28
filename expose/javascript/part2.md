1. At line 12, 3 is printed since the variable i was declared with var. This means that var i is useable throughout the function and remains as 3 after the loop finishes.
2. At line 13, 150 is printed because discountedPrice is a var variable so after the loop finishes the value still exists within the function and the last value was 150.
3. At line 14, 150 is printed since finalPrice is a var variable so the value exists within the function after the loop. finalPrice's last value is 150.
4. A var array with the values 50, 100, 150 are returned. The loop iterates through every value in prices and multiplies it by 1 - discount. Since the parameter was an array of values 100, 200, 300, and the discount was 0.5, each value gets divided by 2 and added to the discounted array.
5. The code causes a not defined error since variable i was declared with let inside the the for loop. So this means the i variable does not exist outside of the loop.
6. The code causes a not defined error since variable discountedPrice was declared with let inside the for loop. So it doesnt exist outside of it.
7. Line 14 prints 150 since finalPrice was declared outside of the for loop and within the function with let, so the value still exists after the loop terminates and its final value was 150.
8. The function returns an array with values 50, 100, 150. The array discounted was declared with let outside of the loop and inside the function so the values within the loop are pushed into the array and are saved, which is then returned at the end.
9. The code causes an undefined error since i was declared with let inside of the for loop so it is not useable outside of the for loop.
10. At line 12, 3 is printed since length was declared inside of the function and outside of the loop it can be used anywhere, and the array has 3 values.
11. The function returns an array 50, 100, 150. discounted was declared inside of the function and outside of the loop so it can be manipulated within the loop and returned after the loop terminates.

12. 
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]

13.
a. 32 since one side is a string, JS turns 2 into a string and just sticks them together  

b. 1  since the - operator only works with numbers, so JS turns 3 into 3  

c. 3 since null becomes 0, so it’s basically 3 + 0  

d. 3null since  one side is a string, so null becomes null and gets added on  

e. 4 since true turns into 1, so it’s 1 + 3  

f. 0 since false is 0 and null is 0, so it’s 0 + 0  

g. 3undefined since one side is a string, so undefined becomes undefined and gets joined  

h. NaN since - tries to turn things into numbers. 3 is 3, but undefined is NaN, so the result is NaN  

14.

a. true since JS turns 2 into 2, and 2 > 1 is true  

b. false since Both are strings, so JS compares them like words. 2 is greater than 1, so 2 < 12 is false  

c. true since == lets JS convert types, so 2 becomes 2  

d. false since === doesn’t convert types, so a number and a string aren’t equal  

e. false since true becomes 1, and 1 == 2 is false  

f. true since Boolean(2) is true, so it’s true === true  

15.

== checks if values are equal after converting types if needed  

=== checks if both the value and the type match, so it’s stricter  

17. Result: [2, 4, 6]

modifyArray([1, 2, 3], doSomething) sends in the array and the function doSomething. The loop goes through each number in the array and passes it into the callback. The callback (doSomething) doubles each number, and those results get pushed into newArr. By the end, newArr becomes [2, 4, 6], and that’s what gets returned.

19. The output is shown below
```
1
4
3
2
```


1. 3 will be printed because var variables can be used outside of loops too so it runs through the for loop and when it exits at i=3 the var is still stored and accessible 
2. 150 will be printed as the last discountedPrice would be (300*0.5) = 150 and for the same reason as above 
3. 150 will be printed as the last finalPrice again was 150 rounded which is just 150
4. The function will return the array of numbers at the discounted price so in this case it would return [50, 100, 150]
5. Code produces an error because i is not defined out of the for loop so it's only accessible within it 
6. Same error for same reason as 5 (definied within a for loop)
7. Prints 150 because finalPrice doesn't use the let operator 
8. Function returns the array [50, 100, 150] of the discounted prices of the input array
9. Error produced since i is assigned let and that cannot be used outside of the for loop in this case
10. 3 is printed as length is assigned a value within the same brackets as the statement that is printing it 
11. Function would return [50, 100, 150] which is the discounted prices of the input array
12. 
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. 
    A. 32 as integers map to their exact string representation so it's '3' + '2'
    B. 1 as you can't subtract strings so '3' is converted to an int and 3-2=1
    C. 3 as null is mapped to 0
    D. 3null as null is mapped to a string and concat happens 
    E. 4 as true maps to 1 and 1+3=4
    F. 0 as both false and null map to 0 so 0+0=0
    G. 3undefined as undefined maps to a string and concats with 3 
    H. NaN as when you minus it tries to map to int but undefined maps to NaN so string - NaN = NaN
14. 
    A. true as '2' becomes an integer and 2>1 is true 
    B. false as '2' is lexicographically smaller than '12'
    C. true as '2' becomes an integer in this cases as 2 == 2 is true 
    D. false as === checks to see if the types are both the same as well
    E. false as true will map to 1 and 1 == 2 is false 
    F. true as Boolean of any integer that's not 0 is true and true === true is true 
15.  == checks the inequality without type conversion as apposed to ===
17.  When we call modifyArray while passing in [1,2,3] and doSomething it will first go into modifyArray and create a new variable newArr which is an empty array. It will then enter the for loop and iterate over [1,2,3] calling doSomething on each value in the array and multiplying the number by 2 before pushing it back into newArr. The end result will be modifyArray returning an array that is the same length as the input but with all the values multiplied by 2 
19.  1, 4, 3, 2
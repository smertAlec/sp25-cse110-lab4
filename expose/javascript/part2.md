1. It will print 3 because `i` is a var variable, meaning it can be accessed anywhere within the function. `i` will be 3 when it is accessed (after the for loop finishes).
2. It will print 150 because `discountedPrice` is a var variable, meaning it can be accessed anywhere within the function. `discountedPrice` will be 150 when it is accessed, since 300 was the last price in the list.
3. It will print 150 because `finalPrice` is a var variable, meaning it can be accessed anywhere within the function. `finalPrice` will be 150 when it is accessed, since 300 was the last price in the list.
4. The function will return [50, 100, 150]. The function will calculate the discounted price of each price in the input list and push it into the `discounted` list.
5. The code causes an error because `i` is a let variable, meaning it is local to the for loop, which it was declared within, and can't be accessed outside of it.
6. The code causes an error because `discountedPrice` is a let variable, meaning it is local to the for loop, which it was declared within, and can't be accessed outside of it.
7. It will print 150 because `finalPrice` is declared outside the for loop, meaning it can be accessed anywhere within the function.
8. The function will return [50, 100, 150]. The function will calculate the discounted price of each price in the input list and push it into the `discounted` list.
9. The code causes an error because `i` is a let variable, meaning it is local to the for loop, which it was declared within, and can't be accessed outside of it.
10. It will print 3 because `length` was set to `prices.length`, which is 3.
11. The function will return [50, 100, 150]. The function will calculate the discounted price of each price in the input list and push it into the `discounted` list. The reason it won't cause an error is because `discontinued` isn't being assigned to another list. It is just being pushed into.
12. Notations:
    * A: `student.name`
    * B: `student['Grad Year']`
    * C: `student.greeting()`
    * D: `student['Favorite Teacher'].name`
    * E: `student.courseLoad[0]`
13. Arithmetic:
    * A: '32'  
        Since 3 is a string, it will convert 2 to a string and concatenate it with '3'.
    * B: 1  
        Since there is a minus sign, the string 3 will be converted into an integer and 2 will be subtracted from it.
    * C: 3  
        Null will be converted into 0 and added to 3.
    * D: '3null'  
        Null will be converted into a string and concatenated with '3'.
    * E: 4  
        True will be converted into the integer 1 and added to 3.
    * F: 0  
        False and null will both be converted into the integer 0.
    * G: '3undefined'  
        Undefined will be converted into a string and concatenated with '3'
    * H: NaN  
        Since there is a minus sign, '3' will be converted into 3 and undefined will be converted into NaN.
14. Comparisons
    * A: true  
        '2' becomes 2 and 2 > 1.
    * B: false  
        '2' is larger than '1' by dictionary comaprison.
    * C: true  
        '2' converts to 2 and 2 == 2.
    * D: false  
        The two arguments are different data types, so under strict equality, they are not equal.
    * E: false  
        True converts to 1 and 1 != 2.
    * F: true  
        Boolean(2) is true and true === true.
15. === is strict equality, meaning the values being compared must be the same data type. == allows for different data types to be compared.  

17\. The function will return [2, 4, 6]. Every time it pushes into the `newArr` list, it will call `callback`, which is an alias for the `doSomething` function. Therefore, it will mulitply each element of the input list by 2.
19\. 1432

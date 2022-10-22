1. console.log(i) at line 12 will print out 3 because i will store the latest prices.length in the for loop, which is going to be 3 since there are three elements in the prices parameter [100, 200, 300]
2. console.log(discountedPrice) at line 13 prints out 150 because it is the latest value stored in 'discountedPrice' during the for loop which is 300 * (1-0.5) = 150.
3. console.log(finalPrice) at line 14 prints out 150 because it is the last stored discounted price in the for loop, and rounding 150 would still make the last stored finalPrice to be 150. 
4. This function will return an array of discounted prices [50, 100, 150] since the function returns 'discounted,' which is an array of discounted prices that gets formed in the function. 
5. There will be an error at line 12 because since i is a let variable, it is defined only during the for loop. 
6. There will be an error at line 13 because 'discountedPrice' is no longer defined outside of the for loop.
7. Line 14 will print out 150 because console.log(finalPrice) at line 14 is in the same scope as the let variable 'finalPrice'.
8. This function will return the array of discounted prices [50, 100, 150]
9. Code causes an error at line 11 because i is a let variable, so it is defined only during the for loop. 
10. Line will print out 3 because it console logs the const variable length which was set early on in the function.
11. This function will return the array of discounted prices [50, 100, 150] because the const variable discounted is in the same scope as the return. 
12. - A. student.name;
    - B. student.["Grad Year"];
    - C. student.greeting();
    - D. student.["Favorite Teacher"].name;
    - E. student.courseLoad[0];
<br>

13. Arithmetic
     - A. '32'. Since integers map to their exact string representation
    - B. 1. Strings are converted to numbers
    - C. 3. By numeric conversion, null becomes 0
    - D. '3null'. null becomes string because '3' is a string
    - E. 4. By numeric conversion, true becomes 1
    - F. 0. By numeric conversion, false and null both become zero
    - G. '3undefined'. undefined becomes string because '3' is a string
    - H. NaN. undefined is NaN as a number, not 0. So it becomes a Not-a-Number. 

14. Comparison
    - A. true. String '2' becomes number 2
    - B. false. String is compared using lexicoographical order starting from the first character, so '2' is bigger than '1'
    - C. true. String '2' becomes number 2
    - D. false. === checks the equality without type conversion. 
    - E. false. true equals to 1, which is not equal to 2
    - F. true. Anything except 0, an empty string, null, undefined, and NaN becomes true when converted to Boolean.

15. == is a equality test with type conversion. <br>
    === checks the equality without type conversion. 

16. See [here](part2-question16.js)
17. [ 2, 4, 6 ] would be the result. When it calls the function modifyArray on line 13 with the parameters ([1,2,3], doSomething), it creates a new array and enters the for loop, which loops array.length times. In the for loop, the callback function doSomething(num) is called for each element in the array, and stores the return value of the callback function in the new empty array. Finally, it returns this new array. 
18. See [here](part2-question18.js)
19. 1 4 3 2
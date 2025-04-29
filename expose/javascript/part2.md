### A Little More of a Challenge...
1. It prints out "3" because the keyword `var` lets it be accessed from anywhere from the function and it is incremented to 3 in the for loop.
2. It prints out "150" because the last time `discountedPrice` is reassigned is when `i=2` on line 7.
3. It prints out "150" because the last time `finalPrice` is reassigned is when `i=2` on line 8.
4. It returns an array of length 3: `[50, 100, 150]` because lines 6-10 adds the discounted values from the original prices to this new array.
5. The code returns an error because `i` is not defined because it was declared within the for loop in line 6 which is now out of scope.
6. The code returns an error because `discountedPrice` is not defined because it was defined inside the for loop in line 7, which is out of scope.
7. It prints out "150" because the last time `finalPrice` is reassigned is when `i=2` on line 8 and within the scope of the function discountPrices on line 4.
8. The overall function does not change and thus still returns the array of length 3: `[50, 100, 150]`.
9. The code returns an error because `i` is not defined because it was declared within the for loop in line 6 which is now out of scope.
10. It prints out "3" because it was assigned the length of the array prices in the parameter which was 3.
11. It returns the array of length 3: `[50, 100, 150]` despite being declared with `const` because the array wasn't reassigned but modified which is still allowed under `const`.
### Data Types
12. 
- A. `student.name`
- B. `student['Grad Year']`
- C. `student.greeting()`
- D. `student['Favorite Teacher'].name`
- E. `student.courseLoad[0]`
### Basic Operators & Type Conversion
13. 
- A. `'32'`
- B. `1`
- C. `0`
- D. `'3null'`
- E. `4`
- F. `0`
- G. `'3undefined'`
- H. `NaN`
14. 
- A. `true`
- B. `false`
- C. `true`
- D. `false`
- E. `false`
- F. `true`
15. The == operator perform type conversions before comparing whereas the === is considered 'strict' and does not.

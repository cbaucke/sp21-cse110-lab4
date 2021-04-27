- 1a:
  1. "values added: 20" is printed.
  2. "final result: 20" is printed.
  3. "values added: 20" is printed.
  4. The code will return an error here because result is only in scope inside the if statement, so it cannot be accessed from outside it.
  5. The code will return an error because result is a const and was already assigned a value on line 5, so it cannot be reassigned on line 7.
  6. The code will return the same error as in question 5, since it is trying to reassign result on line 7.
- 1b:
  1. "2" will be printed because i is a var, so it can be accessed anywhere in the function, and since line 12 is after the for loop, i will equal 1 - prices.length, which is 2.
  2. "150" will be printed because discountedPrice can be accessed anywhere in the function, and since line 12 is after the for loop, discountedPrice will equal prices[2] * (1 - .5) = 300 * .5 = 150.
  3. "150" will be printed because finalPrice will equal what it did at the end of the for loop, which is Math.round(150 * 100) / 100, which equals 150.
  4. [50, 100, 150] will be returned because discounted starts empty and pushes the current finalPrice to the end of it every iteration of the for loop, so it will push 50, then 100, then 150.
  5. This causes an error because i was declared using let, so it is only accessible in the for loop. Since line 12 is outside the for loop, i cannot be accessed and it causes an error when the code tries to.
  6. This causes an error because discountedPrice was declared using let, so it is only accessible in the for loop. Since line 13 is outside the for loop, discountedPrice cannot be accessed and it causes an error when the code tries to.
  7. "150" will be printed because finalPrice is in scope since it was declared in the highest level of the function, and the last value finalPrice had in the for loop was 150.
  8. This function will return [50, 100, 150] because discounted is in scope, and it starts empty and pushes the current finalPrice to the end of it every iteration of the for loop, so it will push 50, then 100, then 150.
  9. This will cause an error because i was declared using let so it is only accessible in the for loop. Since line 11 is outside the for loop, it cannot access i.
  10. "3" will be printed because [100, 200, 300] has 3 elements, so prices.length equals 3, so length equals 3.
  11. This function will return [50, 100, 150] because discounted starts empty and in every iteration of the for loop, the current discountedPrice gets pushed to the end of discounted, so 50, then 100, then 150 will be pushed.
  12. 
      - A. student.name
      - B. student['Grad Year']
      - C. student.greeting()
      - D. student['Favorite Teacher'].name
      - E. student.courseLoad[0]
  13. 
      - A. This outputs '32' because 2 gets converted to the string '2', then the strings are concantenated
      - B. This outputs '1' because '3' gets converted to the integer 3
      - C. This outputs 3 because null gets converted to the integer 0
      - D. This outputs '3null' because null gets converted to the string 'null'
      - E. This outputs 4 because true gets converted to the integer 1
      - F. This outputs 0 because both false and null get converted to the integer 0
      - G. This outputs '3undefined' because undefined gets converted to the string 'undefined'
      - H. This outputs NaN because '3' gets converted to 3 and undefined gets converted to NaN, so 3 - NaN = NaN
  14. 
      - A. true because '2' gets converted to the integer 2
      - B. false because the character '2' is greater than the character '1'
      - C. true because '2' gets converted to the integer 2
      - D. false because they are different types
      - E. false because true gets converted to the integer 1
      - F. true because Boolean(2) becomes true
  15. When the types of what is being compared are different, == will convert them both to numbers and then compare. On the other hand, === will just return false if the types are different.
  16. Check part1b-question16.js
  17. [2, 4, 6] will be returned because the for loop iterates over the array [1, 2, 3] and passes each index into doSomething, which just multiplies it by 2, then stores that value in newArr. 
  18. Check part1b-question18.js
  19. It outputs 1, then 4, then 3, then 2
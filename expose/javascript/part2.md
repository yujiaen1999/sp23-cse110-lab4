### 1. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^

The log() method is useful for testing purposes. At line 12, "console.log(i);" logs the value of the variable i to the console. In this case, it logs the value of i after the for loop has completed its iterations. And at this time i = 3, so the console will display the value 3.

### 2. ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^

At line 13, it logs the value of the variable discountedPrice to the console. So the console will display the value 150.

### 3. ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^

At line 14, it logs the value of the variable finalPrice to the console. So the console will display the value 150.

### 4. ^^^ What will this function return? Give a brief explanation why. If the code causes an error, explain why. ^^^

This function will return the array "discounted", which is [50, 100, 150]. Because in the for loop, the discounted prices are calculated and pushed into the discounted array.

### 5. ^^^ What will happen at line 12 and why?  If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).

It will cause an error becasue the "i" is defined as variable by "let" keyword inside the for loop. So it's not visible outside the loop. So at line 12, the "i" is not defiend.

### 6. ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^

It will cause an error becasue the "discountedPrice" is defined as variable by "let" keyword inside the for loop. So it's not visible outside the loop. So at line 13, the "discountedPrice" is not defiend.

### 7. ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^

At line 14, it logs the value of the variable finalPrice (which is defined at beginning by "let", so it is visible for all the function) to the console. So the console will display the value 150.

### 8. ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^

This function will return the array "discounted", which is [50, 100, 150]. Because in the for loop, the discounted prices are calculated and pushed into the discounted array.

### 9. ^^^ What will happen at line 11 and why? If the code causes an error, explain why. ^^^

It will cause an error becasue the "i" is defined as variable by "let" keyword inside the for loop. So it's not visible outside the loop. So at line 11, the "i" is not defiend.

### 10. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^

At line 12, it logs the value of the constant variable "length" to the console. So the console will display the value 3.

### 11. ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^

This function will return the "discounted", which is [50, 100, 150]. Because in the for loop, the discounted prices are calculated and pushed into the discounted array. Although the discountedPrice is and constant variable, but it is initialized in each time the for loop start with i++.

### 12. Answer:

 - A: student.name
 - B: student.['Grad Year']
 - C: student.greeting()
 - D: student.['Favorate Teacher'].name
 - E: student.courseLoad[0]

### 13. Answer:

 - A: '32'; Because 2 maps to a string '2'
 - B: 1; beacuase string '3' maps to a integer
 - C: 3; because null maps to integer 0
 - D: '3null'; because null maps to string 'null
 - E: 4; because true maps to 1
 - F: 0; since both false and null map to 0
 - G: 3undefined; since undefined maps to string 'undefined'
 - H: NaN; since undefiend maps to NaN, 3 subtract NaN is NaN

### 14. Answer:

 - A: true; since '2' maps to integer 2
 - B: false; since they are both string, so they will compare in lexicographical order
 - C: trur; since '2' maps to integer 2
 - D: false; since === checks the equality without type conversion.
 - E: false; since true maps to 2, and 2 != 1
 - F: true; since Boolean(2) maps to true

### 15. Explain the difference between the == and === operators.

'==' is a regular equality check, it can auto convert different type to same, but it has some probem like it cannot differentiate 0 from false;

'===' is a strict equality operator, it can check the equality without conversion.

### 16. Answer in part2-question16.js

redcars: 21
blueCars: 45
raceCars: 5
rareCars: 2

### 17. Answer of question17:

- The result id [2, 4, 6]. We input the array [1, 2, 4] and function doSomething to function modifyArray. The function doSomething take a input integer and return the doubled integer out. Inside the function modifyArray, we iterate each integer of the input array, put them into the function doSomething, then push the doubled result to the newArr array, and return the newArr as result.

### 18. Answer in part2-question18.js


### 19. What is the output of the above code?

1
4
3
2

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
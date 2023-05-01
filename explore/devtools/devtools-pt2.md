### 1. What was the bug?
The data type of num1 and num2 are string, so when we add num1 and num2, it will join them together instead of adding them together.

### 2. How would you fix it? Include a screenshot of your fix. Name it fix.png (or whatever image extension you would like to use)

I change line 11 to "let result = parseInt(num1) + parseInt(num2)". Use parseInt() to convert string type num1 and num2 to integer.
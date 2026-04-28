# Part 2 Answers

## Question 1
- Printed at Line 12: 3
- 3 is printed because var lets the scope of the variable be within the function, allowing the variable i to be accessed by console.log. Thus, i equals the iterations of the for loop which equals the length of prices: 3.

## Question 2
- If it is console.log(discountedPrice), line 13 would print: 150. This is because discountedPrice's scope is defined in the function with var. So the printed value would be the value discountedPrice holds after the last iteration.
- 300*(1-0.5) = 150.

## Question 3
- If it is console.log(finalPrice), then line 14 would print: 150. This is because finalPrice is accessible and would print the last calculated value which is 50 percent of 300.

## Question 4
- The function returns [50, 100, 150] because that is the array from the loop that contains all finalPrice values.

## Question 5
- There would be a ReferenceError because let means the variable is only within a block scope. The variable 'i' is only accessible within the for loop and not outside of it.

## Question 6
- There would be a ReferenceError because let means the variable is only within a block scope. The variable 'discountedPrice' is only accessible within the for loop and not outside of it.

## Question 7
- Line 14 would print: 150. This is because finalPrice, with the 'let' declaration, was declared outside the for-loop and is able to be accessed by console.log.

## Question 8
- The function returns [50, 100, 150] because discounted array is still accessible.

## Question 9
- There is a ReferenceError because i is not defined outside the for-loop through 'let'.

## Question 10
- Line 12 prints: 3. This is because length is perfectly fine with being declared and assigned at the same time. Legnth is not reassigned throughout code, so it successfully reaches to line 12 and outputs the length of prices, which is 3.

## Question 11
- The function returns [50,100,150] because discounted isn't specifically being reassigned when values are pushed in the array.

## Question 12
a. student.name or student['name']

b. student['Grad Year']

c. student.greeting()

d. student['Favorite Teacher'].name

e. student.courseLoad[0]

## Question 13
a. '32'

b. 1

c. 3

d. '3null'

e. 4

f. 0

g. '3undefined'

h. NaN

## Question 14
a. true

b. false

c. true

d. false

e. false

f. true

## Question 15
- The difference between == and === is that == converts the types before comparing. For example, 2 == '2' will convert the string '2' to the number 2. On the other hand, === doesn't convert types and compares whats given. === will return false if different types.

# Question 17
- The result is going to be [2, 4, 6].
- modifyArray function is called with [1,2,3] and doSomething. For each element in [1,2,3], doSomething is called, meaning each element is multiplied by 2. Then, modifyArray function pushes the result with the newly multiplied elements into newArr and returns [2,4,6].

## Question 19
- The function prints: 1 4 3 2
- console.log(1) is printed immediately because it is the first line amongst the four and there is no scheduled interval. console.log(4) would be next even though it is the last amongst the four, this is because there is no delay. Then 3 would print because it has a shorter delay with 0ms. Lastly, 2 prints with the longest scheduled interval.
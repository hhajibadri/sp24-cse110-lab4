# Part 2:

1) The program printed 3 because the i variable is function-scoped and so it retains the value after the for loop.
2) The program printed 150 because the last assignment of discountedPrices was the last element of the list which was 300 times one-half which yields 150.
3) The program also printed 150 because what it does it takes discountedPrices which is 150 multiply by 100 and then divide by 100. This effectively rounds the number to the second decimal place. In this case since 300 / 2 is a whole number no rounding occurs.
4) The program doesn't print anything since we have commented out all the console.log lines, it executes as normally.
5) The program throws an error because i is a block-scoped variable which only exists in the for loop.
6) The program throws an error again because discountedPrices is a block-scoped variable that only exist in the for loop.
7) The program printed 150 because finalPrice because the finalPrice variable has the scope of the function.
8) The program didn't print anything because all the console.log lines were commented out.
9) The program threw an error because discountedPrice is initialized in the first iteration of the loop but throws an error because in the second iteration it is trying to reassign a value.
10) The program threw an error because discountedPrice is initialized in the first iteration of the loop but throws an error because in the second iteration it is trying to reassign a value. This is the same as the previous.
11) The program threw an error because discountedPrice is initialized in the first iteration of the loop but throws an erroe because in the second iteration it is trying to reassign a value. This is also the same because of discountedPrice.

12) .
    1) student.name
    2) student['Grad Year']
    3) student.greeting()
    4) student['Favorite Teacher'].name
    5) student.courseLoad[0]

13) .
    1) The result was 32 because it does string concatenation first and then converts it to a number.
    2) The result was 1 because it converted the string to an integer first and then did integer subtraction.
    3) The result was 3 because null gets converted to 0 before being added as integers.
    4) The result was '3null' because it converted null to the string 'null' and did string concatenation.
    5) The result was 4 because true is converted to 1 before being added as integers.
    6) The result was 0. Both false and null are converted to 0 before being added as integers.
    7) The result was '3undefined' because it converted undefined to a string and then did concatenation.
    8) The result was NaN because it converted the string '3' to an integer 3 and then did integer subtraction which NaN because undefined isn't representable as a number.

14) .
    1) The result was true because '2' is converted to the integer 2 and then 2 is obviously greater than 1.
    2) The result was false because both '12' comes before '2' due to lexigraphic ordering.
    3) The result was true because == does type conversion, so in this case it converts the string '2' to 2 and it follows that 2 is equal to 2.
    4) The result was false because === does comparisons without type conversion and it follows that a string and integer are not equal to each other.
    5) The result was false because true is converted to 1 and 1 does not equal to 2.
    6) The result was true because the Boolean constructor converts any integer not equal to 0 to true and true is equal to true.

15) The double equal operator == does type conversion before making the comparison, for example '2' == 2 is evaluated as true since '2' is converted the integer 2. On the other hand the triple equal operator does comparison without type conversion so it a strict equality test, this means that unless the values are the same type and value it will always evaluate as false.

16) ```for(let property in statistics){
    if(property.charAt(0) == 'r' || statistics[property] % 2 != 0){
        console.log(statistics[property]);
    }
}```

17) The result was that the array is [2, 4, 6]. This is because at every iteration of the for loop we are calling doSomething which returns the double of an integer and we push that to our new array and then return the array after the for loop.

18) ```function func() {
    let d = new Date();
    let time = d.toLocaleTimeString();
    console.log(time);
};

setInterval(func, 1000);```

19) The output was 1 4 3 2.


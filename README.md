# 24 Days of code i.e. A JavaScript Question bank created by [Priya Bagde](https://github.com/priya42bagde) & modified by [Ankit Jain](https://github.com/xdankit)

## Day 1

- Remove Duplicate characters from String
- Remove Duplicate characters from array of element and find the count of an elements using set
- Remove Duplicate characters from array of element using filter
- String reverse without reversing of individual words (Array of elements can be reverse with reverse() method but for string it is won't possible so required to split and then join.

## Day 2

- String reverse with reversing of individual words
- String reverse without using inbult function
- Find factorial of user input number
- Check if a string is an Anagram
- Swapping of 2 numbers with third variable
- Swapping of 2 numbers without third variable

## Day 3

- To check the string or number is palindrome or not( ex: 121,madam,anna) using reverse method
- To check the string or number is palindrome or not( ex: 121,madam,anna) using diving length by 2 and then comparing
- To find longest word from a string using (for of Loop) means iterate by an elements not by indexing
- To find longest word from a string using functions

## Day 4

- To find longest word from a string using custom code
- To find longest common string from array of strings
- To find vowels and its count in a given string
- To find character occurance from the string

## Day 5

- To find a first pair from a number array whose sum is zero
- Find all possible pairs  from a number array which some is zero.
- To find a first pair from a number array whose sum is zero using indexing
- To find the largest pair of the 2 elements using indexing with unsorted elements

## Day 6

- To find the largest pair of the 2 elements using indexing with sorted elements
- To find the index of an element from an array
- Fibonacci Series `(0,1,1,2,3,5,8,13....)`

## Day 7

- Fibonacci Series (0,1,1,2,3,5,8,13....) where keeping in array
- Finding a missing elements in an array and then add with existing elements. (-1 means if elements not found then it will return always -1 as per rule)
- Find the missing number from an array

## Day 8

- Sorting of a string/characters
- Sorting of a number array with or without inbuilt methods
- To check if given number is prime or not
- To print all the numbers from 2 to 100

## Day 9

- To find unique values from 2 arrays and keep into one array. i.e. Union.
- Find first duplicate element from an array
- Write a program that prints the numbers from 1 to 100. But for multiples of three, print "Fizz" instead of the number, and for the multiples of five, print "Buzz". For numbers which are multiples of both three and five, print "FizzBuzz"
- Uppercase of each first letter of a words
- Uppercase of each first letter of a words using Array map function

## Day 10

- To check ending of the string matches with given character/s using inbuilt function
- To check ending of the string with given character/s using custom implementation
- To find the largest elements fro the 2 dimensional array.

```javascript
const input = [
  [1, 2, 3, 4],
  [5, 6, 7, 9],
  [45, 76, 2, 1],
  [89, 90, 87, 9],
];

// Output
[4, 9, 76, 90];
```

- Print string n times using inbuilt function

## Day 11

- Print string n times in custom way using loops
- Truncate the string upto specific character. For ex ("I am priya", 3) => "I am..."
- Converting one dimensional array into n dimensional array using slice.

```javascript
const input = covertArryInOneDimension(["a", "b", "c", "d"], 2);

// Output
[
  ["a", "b"],
  ["c", "d"],
];
```

- To find only truthy values from an array.

```javascript
const input = ["priya", 0, "", false, null, undefined, "ate", NaN, 9];

// Output
["priya", "ate", 9];
```

- To find only truthy values using filter.

```javascript
const input = ["priya", 0, "", false, null, undefined, "ate", NaN, 9];

// Output
["priya", "ate", 9];
```

## Day 12

- Checking all letters of second words should present in first word, in the same order using indexOf without indexing i.e for-of loop
- Checking all letters of second words should present in first word, in the same order using indexOf with indexing
- Unique values only from 2 arrays i.e. union values

```javascript
const inputA = [1, 2, 3, 4, 5, 1];
const inputB = [1, 2, 3, 4, 5, 1, 7, 6, 4, 3, 8];

// Output
[1, 2, 3, 4, 5, 6, 7, 8];
```

- Remove Duplicates from 2 arrays using Set method

## Day 13

- Print of all numbers from start to end given number

```javascript
printSeries(1, 4);

// Output
1;
2;
3;
4;
```

- Remove or Delete elements from an array using various ways
- Spiral Matrix Printing | Print the elements of a matrix in spiral form

```javascript
// Input
var input = [
  [1, 2, 3, 4],
  [5, 6, 7, 8],
  [9, 10, 11, 12],
  [13, 14, 15, 16],
];

// Output -> Hint - Sprial in clockwise order
[1, 2, 3, 4, 8, 12, 16, 15, 14, 13, 9, 5, 6, 7, 11, 10];
```

## Day 14

- Currying function i.e sum of multiple argument functions //inner function can access outer function variables but outer functions can't able to acceess inner function.
- Find SUM, PRODUCT AND AVERAGE of the numbers //accumulation means collection
- Convert 2D/3D array into 1D using reduce function and inbuilt function i.e flat

```javascript
// input
const arr = [
  ["a", "b"],
  ["c", "d"],
  ["e", "f"],
];

// Output
["a", "b", "c", "d", "e", "f"];
```

## Day 15

- Reverse of a nuber using converting into string with or withour builtin methods
- Reverse of a number
- Check Armstrong Number
- To find the second largest number in an array
- To find the closest number in an array from the given input

```javascript
// Input
const inputArr = [1, 10, 7, 2, 4, 9];
const nearbyNumber = 5;

// Output
4;
```

## Day 16

- To check whether particular word/number present in sentence or not using inbuilt function
- To check whether particular word/number present in sentence or not using custom function
- To check wheather property exist or not in object
- To delete the property of an object
- To find the length of the array in custom way

## Day 17

- Star Pattern

```javascript
*****
****
***
**
*
```

- Star Pattern

```javascript
*****
*****
*****
*****
*****
```

- Number Pattern

```javacript
11111
2222
333
44
5
```

- Number pattern

```javascript
12345;
2345;
345;
45;
5;

// Ignore Semicolons
```

- Star Pattern

```javascript
*
**
***
****
*****
```

## Day 18

- To find the square root of every element of an array

```javascript
const output = [4, 9, 16, 25, 36];

// Output
[2, 3, 4, 5, 6];
```

- Make alternate character to upper case

```javascript
const input = "Priya Bagde";

// Output
("PrIyA BaGdE");
```

- To find the negative values in an array or 2D Array

```javascript
const input = [
  [1, -1],
  [-1, -1],
];

// Output
3;
```

- Find first repeating character with its index from an array. You need to tell which element is having the first repetation inside an array

```javascript
const input = [1, 0, 2, 3, 4, 4, 5, 7, 7];

// output
4;
```

- To find all the subsets of the set

```javascript
const input = [1, 2];

// Output
[[1], [1, 2], [2], []];
```

## Day 19

- To find the maximum repetation of the character in a string

```javascript
const input = "aaaabbaaccccccccccccccccccde";

// Output
{
    character: 'c',
    count: 18
}
```

- To find all the missing numbers from an array

```javascript
const input = [1, 2, 6];

// Output
[3, 4, 5];
```

- Adding an elements to the array when elements are consecutive numbers upto 10

```javascript
const inputA = [1, 2, 3, 4];

// Output
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

/********************************/

const inputB = [4, 2, 4, 3, 1];

// Output
("Not a consecutive since 4 is repeating");

//
```

- Create a new array by adding one to each elements of the existing array

```javascript
const input = [1, 2, 3, 4];

// Output
[2, 3, 4, 5];
```

## Day 20

- To find kth smallest or largest element in an array

```javascript
const input = findKthSmallestOrLargest[2,1,4,3,6,5,7], 3);

// Output
{
  smallest: 3,
  largest: 5,
}
```

- sort by frequency of the letters

```javascript
const input = frequencySort("cCaaAAbbbBBB"));

// Output
"bbbBBBaaAAcC"
```

- To find the occurance of the character in a string

```javascript
const input = findOccurance("cCaaAAbbbBBB")

// Output
{ c: 1, C: 1, a: 2, A: 2, b: 3, B: 3 }
```

- Find permutation of a string

```javascript
const input = perm("let");

// Output
["let", "lte", "elt", "etl", "tle", "tel"];
```

## Day 21

- To find the power of x with or without using Math function

```javascript
/**
 *
 * @param number {Number to input}
 * @param exponent {Exponent}
 * @returns number
 */
function findPowOfNumber(number, exponent) {
  // Write your logic here
}
const input = findPowOfNumber(2, 3);
```

- Grouping of an Anagram

```javascript
const input = findGroupsOfAnagram(["bag", "gab", "foo", "abg", "oof", "ofo"]);

// Output
[
  ["bag", "gab", "abg"],
  ["foo", "oof", "ofo"],
];
```

- Sort an array of an element by parity means even then odd elements

```javascript
const input = sortByParity([1, 2, 3, 4, 5, 6, 7, 8, 9]);

// Output
[2, 4, 6, 8, 1, 3, 5, 7, 9];
```

- Move all the zeroes at the end of an elements

```javascript
const input = [1, 0, 2, 0, 0, 9, 0, 6, 7];

// Output
[1, 2, 9, 6, 7, 0, 0, 0, 0];
```

- Print consecutive numbers

```javascript
const input =
  getConsecutiveNumbers(10)[
    // Output
    (1, 2, 3, 4, 5, 6, 7, 8, 9, 10)
  ];
```

## Day 22

- 4 Ways to empty an array. You need to comeup with 4 different approaches
- Create a function to calculate the sum of all the numbers in a jagged array

```javascript
const input = sumOfNestedArrayElements([1, 2, [3, [4], [5, 6]], [7]]);

// Output
28;
```

- To verify whether perfect number. Any number from 1 to n should be valid. Other input should not be a perfect integer containing 0.

- Calculate the Number of days between 2 dates

- To find todays date only
- Implement String Compression (Microsoft, Amazon etc)

```javascript
const input = stringCompression("aaaabbcaabbaa");

// Output
("a4b2c1a2b2a2");
```

## Day 23

- Given the roots of two binary trees root and subRoot, return true if there is a subtree of root with the same structure and node values of subRoot and false otherwise. A subtree of a binary tree tree is a tree that consists of a node in tree and all of this node's descendants. The tree tree could also be considered as a subtree of itself. Given trees & you need to construct these tree by yourself.

```javascript
// Given tree s:
     3
    / \
   4   5
  / \
 1   2

// Given tree t:
   4
  / \
 1   2
```

# Day 24

- Find triplets whose sum is given as a second argument

```javascript
/**
 *
 * @param inputArr {Array<Number>}
 * @param sum {Number}
 */
function findTriplets(inputArr, sum) {
  // Write your logic here
}

const input = findTriplets([-1, -4, -9, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9], 0);

// Output
-1, -4, 5;
-1, 0, 1;
-4, 0, 4;
-4, 1, 3;
-9, 0, 9;
-9, 1, 8;
-9, 2, 7;
-9, 3, 6;
-9, 4, 5;
```

- Convert an Array into an object

```javascript
const input = ["John", "Peter", "Sally", "Jane"];

// Output
{ 0: "John", 1: "Peter", 2: "Sally", 3: "Jane" }
```
# Day 1 - Solutions
// Remove Duplicate characters from String
```
const value = "abcdabcd";
const newArray = []
const seen = {}

for(let i = 0; i < value.length; i ++){
    const initValue = value[i]
    if(!seen[initValue]){
        seen[initValue] = true;
        newArray.push(initValue)
    }
}

console.log(newArray.join(''))

// Second Way
const value = "abcdabcd";
const sepValue = value.split('')
const newArray = []
const seen = {}

for(let i = 0; i < sepValue.length; i ++){
   if(!newArray.includes(sepValue[i])){
       newArray.push(sepValue[i])
   }
}

console.log(newArray.join(''))

// Third Way

const value = "abcdabcd";

const newValue = [...new Set(value)]

console.log(newValue.join(''))
```
```
// Remove Duplicate characters from array of element and find the count of an elements using set

const aArray = [1,2,3,1,4,5]
const newValue = [... new Set(aArray)]
console.log(newValue.join(''), "Count of new", newValue.length)
```
```
// Remove Duplicate characters from array of element using filter

const product = ["apple", "banana", "apple", "mango", "strawbery", "bery"]

const newArray = []
const seen = {}

const remDupValue = product.filter((value) => {
    if(!seen[value]){
        seen[value] = true;
        return true
    }
    return false
})

console.log(remDupValue.join(','))
```
```
// String reverse without reversing of individual words (Array of elements can be reverse with reverse() method but for string it is won't possible so required to split and then join.

const value = "Hello world from ChatGPT"

const splitValue = value.split(' ')

const store = []
//reverse loop my brother
for(let i = splitValue.length - 1; i > -1; i--){
    store.push(splitValue[i])
}

console.log(store.join(' '))
```

# Day 2 - Solutions

```
// String reverse with reversing of individual words

let str = "My Github username is sohail9744"

//will make it split the word
let split = str.split(' ')
//will run reverse loop for this

let aArray = []

for(let i = split.length -1; i >= 0; i--){
    aArray.push(split[i])
}

console.log(aArray.join(' '))
```
```
// String reverse without using inbult function

let str = "My Github username is sohail9744"

console.log(str.split(' ').reverse().join(' '))

```
```
// Find factorial of user input number
const num = [1,2,3,5,6]

// take one number from num
for(let i = 0; i < num.length; i++){
    let firstNum = num[i]

//find the factorial number
    let fact = 1
    for(let f = 1; f <= firstNum; f++){
        fact *= f
    }
    console.log(`factorial for ${firstNum} is ${fact}`)
}
```
```
// Check if a string is an Anagram

const findAnagram = (str, str2) =>{
    
    if(!str || !str2){
        return "Please Provide 2 arguments"
    }
    const store = []
    const strLength = str.length
    
    // spliting the str value
    for(let i = 0; i <= strLength; i++){
        let strValue = str[i] // get first value
        
        for(let k = 0; k <= str2.length; k++){
            //check str1 singal singal letter == to str2 letter
            if(strValue === str2[k]){ 
                store.push(strValue)
                break
            }
        }
    }
    // check str length is equals to store length
    if(strLength === store.length){
        return true
    } else{
        return false
    }
}

console.log(findAnagram('silent', 'listen')) // true
```
# Day 3 - Solutions

```
// To check the string or number is palindrome or not( ex: 121,madam,anna) using reverse method

const checkPalindrome = (str) => {
    str = str.toString();
    
    let reverse = str.split('').reverse().join('')
    
    return reverse === str ? 'It is palindrom' : 'It is not palindrom'

}
console.log(checkPalindrome("anna"));
```

```
// To check the string or number is palindrome or not( ex: 121,madam,anna) using diving length by 2 and then comparing

const checkPalindrome = (str) => {
    str = str.toString();
for(let i = 0; i < str.length / 2; i++){
    if(str[i] !== str[str.length - 1 - i]){
    return 'It is not a palindrome';
    }
}
    
    return 'It is a palindrome';
}
console.log(checkPalindrome("131")); // It is a palindrome
```

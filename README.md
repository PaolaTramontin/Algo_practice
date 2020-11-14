# Algo_practice
![](/ga_cog.png)

# WORD FREQUENCY

## 1
Write a function `findWordFrequencies` that takes in a sentence (string), and returns an object with each word as a key, with a value of how many times that word appears in the sentence.

eg: `{ I: 1, love: 1, lamp: 1 }`

Make it work just for sentences without commas, apostrophes, and periods. Capital letters and lowercase letters should be treated as equals: 'The' and 'the' are the same word.

## 2

Write a function `findHighestFrequency` that takes in an object and returns an object with the key that has the highest value. With this function we can see which word appeared in the sentence with the highest frequency.

If there is a tie between the two most frequent words, the first appearing one is returned.

## Examples

**"The world is all that is the case"**

```javascript
const freqs = findWordFrequencies('The world is all that is the case'));

console.log(freqs);
```

> => { the: 2, world: 1, is: 2, all: 1, that: 1, case: 1 }


```javascript
const freqs = findWordFrequencies('The world is all that is the case');

console.log(findHighestFrequency(freqs));
```

> => { the: 2 }

**"That that is is that that is not is not"**

```javascript
const freqs = findWordFrequencies('That that is is that that is not is not');

console.log(freqs);
```

> => { that: 4, is: 4, not: 2 }

```javascript
const freqs = findWordFrequencies('That that is is that that is not is not');

console.log(findHighestFrequency(freqs));
```

> => { that: 4 }

**"hi"**

```javascript
const freqs = findWordFrequencies('hi');

console.log(freqs);
```

> => { hi: 1 }


```javascript
const freqs = findWordFrequencies('hi');

console.log(findHighestFrequency(freqs));
```

> => { hi: 1 }

### Loop the Loop: 2D Array Additon

**Make a function that returns the greatest sum of a row or column from a two dimensional array**


Make a function that takes one argument, a two dimensional array, where all the arrays are the same length, and returns the greatest sum of the numbers by row and column.
```
const arr = [ [10, 20, 30],
            [40, 50, 60],
            [70, -80, 90] ];

greatestSum(arr); //180
```

### Contains Duplicate

**Given an array of integers and an integer k, find out whether there are two distinct indices i and j in the array such that `nums[i] = nums[j]` and the absolute difference between i and j is at most k.**

<br>

#### Example 1:

```js
__Input__: nums = [1,2,3,1], k = 3
__Output__: true
```

<br>

#### Example 2:

```js
__Input__: nums = [1,2,3,1,2,3], k = 2
__Output__: false
```

<br>
<hr>

## Starter Code
```
const arr = [1,0,1,1];
const k = 1;

containsNearbyDuplicate(arr, k); //true

```


## Anagrams


Check to see if two provided strings are anagrams of eachother.
One string is an anagram of another if it uses the same characters
in the same quantity. Only consider characters, not spaces
or punctuation.  Consider capital letters to be the same as lower case

## Examples
anagrams('rail safety', 'fairy tales') --> True
anagrams('RAIL! SAFETY!', 'fairy tales') --> True
anagrams('Hi there', 'Bye there') --> False

## Fizzbuzz



Write a program that console logs the numbers
from 1 to n. But for multiples of three print
“fizz” instead of the number and for the multiples
of five print “buzz”. For numbers which are multiples
of both three and five print “fizzbuzz”.

## Example
  fizzBuzz(5);
  1
  2
  fizz
  4
  buzz
  
 
  ## reverseInt
  
  Given an integer, return an integer that is the reverse
ordering of numbers.
## Examples
  reverseInt(15) === 51
  reverseInt(981) === 189
  reverseInt(500) === 5
  reverseInt(-15) === -51
  reverseInt(-90) === -9
  
  ## Steps
 
  Write a function that accepts a positive number N.
The function should console log a step shape
with N levels using the # character.  Make sure the
step has spaces on the right hand side!
--- Examples
  steps(2)
      '# '
      '##'
  steps(3)
      '#  '
      '## '
      '###'
  steps(4)
      '#   '
      '##  '
      '### '
      '####'
  



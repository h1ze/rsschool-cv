# Kirill Burnov

## My Contact Info:
* Phone: 89991589741
* Email: h1ze163@gmail.com
* Telegram: @kir163
* Github: <https://github.com/h1ze>
***
## About me:
I am 32 years old, I work in the applied information systems support group. I like to solve logical puzzles and brainteasers, learn new knowledge and skills to put it into practice.
My worst enemy is procrastination, I try to fight it with all my might, but it often wins.
***

## My skills:
+ HTML
+ CSS
+ JavaScript
+ Git
***

## Code example:
**Find the missing letter KATA from CODEWARS:** *Write a method that takes an array of consecutive (increasing) letters as input and that returns the missing letter in the array.
You will always get an valid array. And it will be always exactly one letter be missing. The length of the array will always be at least 2.
The array will always contain letters in only one case.*

```
function findMissingLetter(array) {
  for (let i = 0; i < array.length; i++)
    if (array[i].charCodeAt(0) !== array[i + 1].charCodeAt(0) - 1) {
      return String.fromCharCode(array[i].charCodeAt(0) + 1);
    }
}
```
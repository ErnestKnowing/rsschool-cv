## rsschool-cv
# Ernest Rakhimov
1. Contacts:
* Discord: Ernest#9083
* E-mail: e3050901@gmail.com
2. About myself:
I like to discover new horizons of knowledge, so I’m here. I like it when the brains strain, so I’m here. I like to program, so I’m here.
3. Code example:
Write a function that checks if a given string (case insensitive) is a palindrome. A palindrome is a word, number, phrase, or other sequence of symbols that reads the same backwards as forwards, such as madam or racecar, the date and time 12/21/33 12:21, and the sentence: "A man, a plan, a canal – Panama".
```javascript
function isPalindrome(x) {
  let xReverse = x.split('').reverse().join('')
  return xReverse.toUpperCase() === x.toUpperCase()
}
isPalindrome("aba")
```
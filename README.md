# Anagram-Finder

**Algorithm Practice for June 24, 2020** by *@rangen*

**Clone down or fork this repo and write your function in solution.js**

1. The function checkIsAnagram accepts two arguments, word and baseline.
1. Assume both are valid strings.
The order of the two words essentially does not matter as you are checking to see if they are anagrammable.
1. Your function should return true if the words are anagrams of each other, and false if they are not.

* If you write the function correctly, the file index.html will automatically render any anagrams found in a 178,000+ word list for you beneath the input field.
* Otherwise, the phrase "No anagrams found!" will be displayed.
* As there is no Submit button, your function will run with the text field's onInput event, so every time the field's content is changed!
* I can't vouch for the speed of all working solutions, but the solution I came up with runs beween 8 and 300ms despite searching against 178,000 words everytime.
* **HINT  For the solution I came up with, word results are returned and rendered very quickly (<100ms) up to about 6 characters, moving closer to 300ms around 9 characters, before quickly becoming fast operations again the longer the word gets. Introspect (word from Learn.co labs) about why this would be.**

*Granted, some of y'all are wild and have 162 windows open on your computer, so your timing may vary*

Good luck!!!

![Sample](/src/sample.png)
![Sample](/src/sample2.png)

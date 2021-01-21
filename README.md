Pig Latin
==================
[Pig Latin](http://en.wikipedia.org/wiki/Pig_Latin) is a language game where words are "translated" according to the following rules:  

1. For words that are all consonants, simply add "ay" to the end of the word. Thus, "try" becomes "tryay".  
2. For words that begin with vowels, simply add "way" to the end of the word. Thus, "a" becomes "away"; "at" becomes "atway"; "ermine" becomes "ermineway."  
3. For words beginning with "qu," move the "qu" to the end of the word and add ay. Thus "question" becomes "estionquay".  
4. For words that begin with consonants, move the leading consonant(s) to the end of the word and add "ay." Thus, "ball" becomes "allbay"; "button" becomes "uttonbay"; "star" becomes "arstay"; "three" becomes "eethray";  

Comparing letters of a `String`
-----------------------------

For this assignment you will need to test the letters of a `String` one letter at a time for vowels. There are at least two ways to access one letter of a `String`, `substring` and `charAt`:  
* `sWord.substring(0,1).equals("a")` will test if the first letter of `sWord` is an `'a'`   
* `sWord.charAt(0) == 'a'` will also test if the first letter of `sWord` is an `'a'`


Suggested steps to complete this assignment
-------------------------------------------

1. Complete the following custom codingbat problems: [`findFirstA()`](http://codingbat.com/prob/p279261?parent=/home/simona1@sfusd.edu), [`findFirstAorB()`](http://codingbat.com/prob/p207840?parent=/home/simona1@sfusd.edu), [`findFirstVowel()`](http://codingbat.com/prob/p200508?parent=/home/simona1@sfusd.edu). Don't forget to log in to codingbat! 
2. Fork and clone down this repository. (If you are working online with a Chromebook fork this [Pig Latin project on repl.it](https://repl.it/@MrSimonLowell/PigLatinDemo#Sketch.java), or just copy and paste the code and change line 3 to `String[] lines = {"beast","dough","happy","question","star","three","eagle","try"};`)
3. Run the program. You should see the following (incorrect) output:  
there are 8 lines  
beastay  
doughay  
happyay  
questionay  
staray  
threeay  
eagleay  
tryay  
4. The output is incorrect because you need to finish the two methods `findFirstVowel` and `pigLatin.` You can use your solution from the codingbat problem to complete [`findFirstVowel`](http://codingbat.com/prob/p200508?parent=/home/simona1@sfusd.edu). It returns the position of the first 'a', 'e', 'i', 'o' or 'u'. If the word contains no vowels (like "try"), the method should return -1.
5. Now, modify the `pigLatin()` method to implement all four rules of pig latin shown above. Rule 1 has already been implemented for you. When you've implemented all four rules correctly, the output should be:  
eastbay  
oughday  
appyhay  
estionquay  
arstay  
eethray  
eagleway  
tryay  
6. Since there is no website for this assignment, submit the URL of your finished PigLatin repository to Google Classroom. The URL will have the form ```http://github.com/ your github username /PigLatin```

Extensions
----------

If you have extra time, you could try to modify the program to convert entire passages of English to Pig Latin, like the one below.

The Lowell Hymn:
----------------

With heads bared we stand,  
In tribute to thee,   
Our Alma-Mater Lowell,   
All true to thee we'll be.   
  
Unfurled red and white,   
None shall thee decry,   
They name we love,   
Oh Lowell High.  

The Lowell Hymn in Pig Latin:
-----------------------------

Ithway eadshay aredbay eway andstay,  
Inway ibutetray otay eethay,  
Ourway Alma-Materway Owelllay,  
Allway uetray otay eethay e'llway ebay.  

Unfurledway edray andway itewhay,  
Onenay allshay eethay ecryday,  
Eythay amenay eway ovelay,  
Ohway Owelllay Ighhay.  

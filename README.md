Pig Latin
==================
[Pig Latin](http://en.wikipedia.org/wiki/Pig_Latin) is a language game where words are "translated" according to the following rules:  

1. For words that are all consonants, simply add "ay" to the end of the word. Thus, "try" becomes "tryay".  
2. For words that begin with vowels, simply add "way" to the end of the word. Thus, "a" becomes "away"; "at" becomes "atway"; "ermine" becomes "ermineway."  
3. For words beginning with "qu," move the "qu" to the end of the word and add ay. Thus "question" becomes "estionquay".  
4. For words that begin with consonants, move the leading consonant(s) to the end of the word and add "ay." Thus, "ball" becomes "allbay"; "button" becomes "uttonbay"; "star" becomes "arstay"; "three" becomes "eethray";  

Note that this assignment does not use graphics. Just like Old MacDonald and the Google Billboard, you will push to the master branch, not gh-pages

Suggested steps to complete this assignment
-------------------------------------------

1. Fork and clone down this repository.
2. Run the program. You should see the following output:  
there are 8 lines  
beastay  
doughay  
happyay  
questionay  
staray  
threeay  
eagleay  
tryay  
3. You need to finish the two methods `findFirstVowel` and `pigLatin` so that the program will correctly translate the words into Pig Latin.
4. Start by completing the custom codingbat problem [`int findFirstVowel(String sWord)`](http://codingbat.com/prob/p200508?parent=/home/simona1@sfusd.edu). It returns the position of the first 'a', 'e', 'i', 'o' or 'u'. If the word contains no vowels (like "try"), the method should return -1.
5. Now, modify the `pigLatin()` method to implement all four rules of pig latin shown above. Rule 1 has already been implemented for you. When you've implemented all four rules correctly, the output should be:  
eastbay  
oughday  
appyhay  
estionquay  
arstay  
eethray  
eagleway  
tryay  
6. Submit the URL of your finished PigLatin repository to the school loop drop box.

Comparing letters of a String
-----------------------------

There are two ways to compare one letter of a String, 'charAt' and 'substring':  
`sWord.charAt(0) == 'a'` will test if the first letter of `sWord` is an `'a'`
`sWord.substring(0,1).equals('a')` will also test if the first letter of `sWord` is an 'a'


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

# Anagrams

(1) This homework deals with anagrams. An anagram is a rearrangement of the letters in a word to form one or more new words.

     Your job is to write a function anagrams(), which takes as input a phrase and an optional argument, shortest, which is an integer          that specifies the shortest acceptable word. Your function should return a set of all the possible combinations of anagrams.

     Your function should not return every permutation of a multi word anagram: only the permutation where the words are in alphabetical        order. For example, for the input string 'ANAGRAMS' the set that your function returns should include 'AN ARM SAG', but should NOT          include 'ARM SAG AN', or 'SAG AN ARM', etc...
      
(2) Readwordlist: Write a function, readwordlist, that takes a filename as input and returns a set of all the words and a set of all the prefixes in that file, in uppercase. For testing, you can assume that you have access to a file called 'words4k.txt'
